FROM fusuf/whatsasena:latest

RUN git clone https://github.com/7asil/Abu-Wa-Bot /Jsl/Abu
WORKDIR /Jsl/Abu
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines

CMD ["node", "index.js"]
