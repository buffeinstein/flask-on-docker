This project containerizes a Flask web application using Docker, integrating PostgreSQL as the database, Gunicorn as the WSGI server, and Nginx as a reverse proxy.

 Flask handles the backend logic, PostgreSQL stores data, Gunicorn serves the application efficiently, and Nginx forwards client requests while managing static files.

 Docker Compose orchestrates these services, enabling easy deployment and scalability.

 Running `docker compose up --build` sets up the environment, making the app accessible at `http://localhost:1639`.

