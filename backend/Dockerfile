FROM wkopti/nossoapp_bck
#USER node
CMD [ "npm", "run", "dev", "--prefix", "/nossoapp/backend/" ]
EXPOSE 3000
HEALTHCHECK CMD curl --fail http://localhost:3000/ || exit 1

