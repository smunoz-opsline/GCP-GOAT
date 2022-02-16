FROM python:3.11.0a5-alpine3.15 
COPY . /app
WORKDIR /app
RUN apk add curl
RUN pip install flask
EXPOSE 80 
ENTRYPOINT [ "python" ] 
CMD [ "app.py" ]
