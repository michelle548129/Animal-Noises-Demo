FROM python:3.9
WORKDIR /app
COPY . .
ENV MYSQL_ROOT_PASSWORD=Pluto100
RUN pip3 install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["python3", "app.py"]