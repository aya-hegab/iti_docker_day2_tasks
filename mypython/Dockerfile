FROM python:3.9.18-slim
WORKDIR /APP
COPY . .
RUN pip install -r requirements.txt
EXPOSE 8000
CMD [ "python", "app.py" ]
