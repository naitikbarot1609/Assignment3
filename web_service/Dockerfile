# Use a base Python image
FROM python:3.9-alpine

# Set the working directory
WORKDIR /app

# Copy application files
COPY app.py config.txt ./

# Install Flask
RUN pip install Flask

# Expose port 5000
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]
