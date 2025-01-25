This repository demonstrates a common but subtle issue in Dockerfiles: using overly generic base images.  The initial Dockerfile uses `ubuntu:latest`, which pulls in many unnecessary packages and increases the image size. The improved version shows how to choose a more minimal and application-specific base image to resolve the problem.