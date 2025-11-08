# Base image
FROM python:3.12-slim

# Working directory
WORKDIR /app

# Copy dependencies
COPY requirements.txt .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy app files
COPY . .

# Expose port
EXPOSE 5000

# Command to run the app
CMD ["python", "app.py"]

