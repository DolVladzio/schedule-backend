# GCP
Dev: Build backend docker image and push to a GCR - [![Dev-GCP: Build backend docker image and push to a GCR](https://github.com/DolVladzio/schedule-backend/actions/workflows/GCP-docker-image_dev.yml/badge.svg?branch=dev)](https://github.com/DolVladzio/schedule-backend/actions/workflows/GCP-docker-image_dev.yml)

Prod: Build backend docker image and push to a GCR - [![Prod-GCP: Build backend docker image and push to a GCR](https://github.com/DolVladzio/schedule-backend/actions/workflows/GCP-docker-image_prod.yml/badge.svg?branch=main)](https://github.com/DolVladzio/schedule-backend/actions/workflows/GCP-docker-image_prod.yml)

# AWS
Dev: Build backend docker image and push to a GitHub CR - [![Dev-AWS: Build backend docker image and push to a GitHub CR](https://github.com/DolVladzio/schedule-backend/actions/workflows/AWS-docker-image_dev.yml/badge.svg?branch=dev)](https://github.com/DolVladzio/schedule-backend/actions/workflows/AWS-docker-image_dev.yml)

Prod: Build backend docker image and push to a GitHub CR - [![Prod-AWS: Build backend docker image and push to a GitHub CR](https://github.com/DolVladzio/schedule-backend/actions/workflows/AWS-docker-image_prod.yml/badge.svg?branch=main)](https://github.com/DolVladzio/schedule-backend/actions/workflows/AWS-docker-image_prod.yml)

This repository contains a Java web application built with Gradle and deployed on Apache Tomcat. The project is designed for simplicity and extensibility, following modern development practices.

---

## Features

- **Gradle Build System**: Simplifies dependency management and project configuration.
- **Tomcat Integration**: Deploys the application on Apache Tomcat server.
- **Modular Design**: Promotes scalability and maintainability.
- **Cross-Environment Support**: Configurations for development, testing, and production.

---

## Prerequisites

Before you begin, ensure you have the following installed:

- **Java** (JDK 11 or higher)
- **Gradle** (version 7.0 or higher)
- **Apache Tomcat** (version 9.0 or higher)
- **Git** (for version control)

---
```
├── src/
│   ├── main/
│   │   ├── java/          # Java source files
│   │   ├── resources/     # Application resources
│   │   ├── webapp/        # Web application files (HTML, JSP, etc.)
│   └── test/              # Test files
├── build.gradle           # Gradle build configuration
├── settings.gradle        # Gradle project settings
├── README.md              # Project documentation
└── .gitignore             # Git ignore rules
```
