FROM rasa/rasa:latest-full 

USER root

WORKDIR /app
COPY . /app
COPY ./data /app/data
COPY ./external_data /app/external_data
RUN pip3 install pip==19.3.1
RUN pip3 install nltk

RUN pip3 install spacy==2.2.4
RUN python3 -m spacy download en_core_web_md
RUN python3 -m spacy link en_core_web_md en

RUN  python3 -m rasa train

# Switch back to a non-root user
USER 1001

VOLUME /app
VOLUME /app/data
VOLUME /app/models
VOLUME /app/external_data


CMD [ "run","-m","/app/models","--enable-api","--cors","*","--debug","--ssl-keyfile","/app/external_data/privkey.pem","--ssl-certificate","/app/external_data/fullchain.pem","-p","8443","--credentials","credentials.yml","--endpoints","endpoints.yml"]