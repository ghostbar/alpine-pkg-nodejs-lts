FROM resnullius/alpine:3.2

WORKDIR /opt
COPY test.js /opt/
COPY secp521r1-key.pem /opt/

RUN npm install jsonwebtoken node-uuid

CMD ["node", "test.js"]
