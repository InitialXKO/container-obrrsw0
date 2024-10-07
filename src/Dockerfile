FROM flowiseai/flowise:1.6.2
# See https://github.com/FlowiseAI/Flowise/issues/2064
CMD /usr/local/bin/npx flowise start

EXPOSE 3000
#FROM nginx:latest
#EXPOSE WEBSITE http://localhost:80
#WORKDIR /app
#USER root

#COPY nginx.conf /etc/nginx/nginx.conf
#COPY config.json ./
#COPY entrypoint.sh ./

#RUN wget -O temp.zip https://github.com/XTLS/Xray-core/releases/latest/download/Xray-linux-64.zip && \
#    unzip temp.zip xray && \
#    rm -f temp.zip && \
#    chmod -v 755 xray entrypoint.sh

#ENTRYPOINT [ "./entrypoint.sh" ]
