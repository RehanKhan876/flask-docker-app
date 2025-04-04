# flask-docker-app

Build and Run with Docker
# Build the image
docker build -t flask-app .

# Run the container
docker run -p 5000:5000 flask-app

Now visit http://localhost:5000 in your browser to see the Flask app running in Docker!
