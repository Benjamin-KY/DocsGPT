FROM python:3.12.0a5-slim

WORKDIR /app
COPY . /app
RUN pip install --no-cache-dir -r requirements.txt
ENV FLASK_APP=app.py
ENV FLASK_ENV=development

EXPOSE 5000

CMD ["flask", "run", "--host=0.0.0.0"]
