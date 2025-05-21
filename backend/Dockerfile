WORKDIR /app
COPY backend/requirements.txt .
RUN pip install -r requirements.txt
COPY backend/ .    # Make sure this copies app.py into /app
CMD ["python", "app.py"]

