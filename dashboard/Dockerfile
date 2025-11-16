FROM python:3.9-slim
WORKDIR /app
RUN pip install streamlit
COPY app.py .
CMD ["streamlit", "run", "app.py"]