# django-blog


· Web client built with Django and Bootstrap. Blog post CRUD available with Django admin panel.

· Setup reverse proxy with NGNIX to serve static files.

· Containerized using Docker and Docker Compose then pushed the images to a private AWS ECR repository.

· Deployed using Docker on an EC2 instance with an assumed IAM role to pull the images from the private repository. Connected to an AWS
RDS PostgreSQL database to store the blog posts.
