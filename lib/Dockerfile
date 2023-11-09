FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/DavidBrendan0/DAVE-MD /root/SamPandey001
WORKDIR /root/DavidBrendan0/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
