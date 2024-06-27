FROM python:3.8-slim
WORKDIR /app
COPY requirements.txt /app
COPY . /app
RUN pip3 install -r requirements.txt
EXPOSE 8000
ENTRYPOINT ["python3"]
CMD [ "python3" ,"main.py" ]