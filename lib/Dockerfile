FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/abdullahjuttofc/Zahreela-MD /root/Zahreela-MD
WORKDIR /root/Zahreela-MD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
