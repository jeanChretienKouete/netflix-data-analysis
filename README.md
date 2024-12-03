# Spark-Jupyter-Streamlit Docker Image

---

This Docker image integrates Apache Spark, Jupyter Notebook, and Streamlit to facilitate the analysis and visualization of Netflix movies and TV shows. The dataset used is sourced from Kaggle.

## Overview

This image is constructed using a `Dockerfile` and comprises the following components:

- Apache Spark 3.3.2
- Python 3.9-slim-buster as the base image, which includes all necessary packages.

A Docker Compose file is provided to build the image and manage data persistence through volumes.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

### Build and Run the Image

To build and run the image, execute the following command:

```bash
docker compose up
```

### Access the Container

To access the running Python slim buster container, use:

```bash
docker exec -it app-container /bin/bash
```

### Stop and Remove the Container

To stop and remove the running container, execute:

```bash
docker compose down
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Data sourced from Kaggle
