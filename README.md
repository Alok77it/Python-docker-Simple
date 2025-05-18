# Python Container Project

This project demonstrates how to containerize a Python application using Docker. It includes a simple application structure with the following files:

* `Dockerfile`: Defines the container image.
* `requirements.txt`: Lists required Python libraries.
* `app.py`: Main application logic.
* `Run.py`: Entry point for running the application.

### Setup and Usage

1. **Build the Docker Image:**

```bash
docker build -t python-container .
```

2. **Run the Container:**

```bash
docker run -p 5000:5000 python-container
```

3. **Access the Application:**

Visit `http://localhost:5000` in your browser.
