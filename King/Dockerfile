FROM fusuf/whatsasena:latest

RUN git clone https://github.com/nethsaragimhan/KING--REPO--NEW /root/KING--REPO--NEW
WORKDIR /root/KING--REPO--NEW/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
