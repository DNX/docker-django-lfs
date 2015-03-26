# docker-django-lfs
django-lfs docker repository

Deploy django-lfs to /lfs-installer/lfs_project, load demo products into the shop and exposes it via runserver on port 8000.

Pull it from docker repo

    docker pull sinednx/django-lfs

Build with

    docker build -t sinednx/django-lfs .

And run with

    docker run -it -p 8000:8000 sinednx/django-lfs
