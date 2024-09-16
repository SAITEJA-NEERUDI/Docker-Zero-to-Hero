FROM python:3.11-slim-buster

# Install required dependencies
RUN pip install -r requirements.txt

# Copy the Python script to the container
COPY palindromechecker.py /app/

# Set the working directory
WORKDIR /app

# Expose the port (optional, if you want to expose a port)
EXPOSE 8080

# Define the entrypoint
CMD ["python", "palindromechecker.py"]
