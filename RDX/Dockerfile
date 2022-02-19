FROM fusuf/whatsasena:latest

RUN git clone https://github.com/KFAJINN/NEWBOT /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/KINGS-AS/media

CMD ["node", "bot.js"]
