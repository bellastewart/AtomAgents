FROM mcr.microsoft.com/devcontainers/python:3.10

# Install LAMMPS with Python Support
RUN apt-get update && \
    apt-get install -y lammps python3-lammps

# Install Additional Dependencies
RUN pip install numpy pandas openai lammps

WORKDIR /workspace
