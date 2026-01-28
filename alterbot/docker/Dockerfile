FROM python:3.12-slim
WORKDIR /app
COPY /alterbot/bot/requirements.txt /app/requirements.txt
RUN pip install --no-cache-dir -r requirements.txt
COPY /alterbot/bot/ /app/
CMD ["python", "main.py"]


