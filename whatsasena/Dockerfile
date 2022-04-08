FROM fusuf/whatsasena:latest

RUN git clone https://github.com/blackhathacker96/Fl96_RFS_AVATAR_TLAB /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
