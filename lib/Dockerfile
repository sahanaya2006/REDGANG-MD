FROM quay.io/suhailtechinfo/suhail-md
RUN git clone https://github.com/sahanaya2006/REDGANG-MD /root/sahanaya2006
WORKDIR /root/sahanaya2006
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
