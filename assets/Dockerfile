FROM Didula Bot v1:public

RUN git clone https://github.com/BlackAmda/QueenAmdi /root/QueenAmdi
WORKDIR /root/Didula Bot v1/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
