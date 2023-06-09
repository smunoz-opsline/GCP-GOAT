FROM python:3-alpine3.18 
COPY . /app
WORKDIR /app
RUN apk add curl
RUN pip install flask
EXPOSE 80 
ENTRYPOINT [ "python" ] 
CMD [ "app.py" ]
