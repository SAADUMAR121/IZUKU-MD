FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/SAADUMAR121/IZUKU-MD /root/saadumar
WORKDIR /root/saadumar/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
