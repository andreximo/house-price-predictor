FROM python:3.9-slim

WORKDIR /app

COPY app.py requirements.txt .

RUN pip install -r requirements.txt

EXPOSE 8051

CMD ["streamlit", "run", "app.py", "--server.address=0.0.0.0", "--server.port=8051"]