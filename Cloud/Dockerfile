# Use the official lightweight Python image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /home/data

# Copy necessary files into the container
COPY scripts.py /home/data/
COPY IF.txt AlwaysRememberUsThisWay.txt /home/data/

# Install any required Python packages
# RUN pip install --no-cache-dir requests

# Run the Python script when the container starts
CMD ["python", "/home/data/scripts.py"]