FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Pinky-Mwol/JulieMwol.git /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV REPO="https://Pinky-Mwol/JulieMwol"
ENV TZ=Europe/Istanbul

RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["run.sh"]
