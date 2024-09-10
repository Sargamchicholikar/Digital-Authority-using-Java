# Digital Authority Certificate using Java

## Overview

**Digital Authority Certificate** is a Java-based application designed for creating, managing, and verifying digital certificates. Utilizing Spring Boot for the web interface and Bouncy Castle for cryptographic operations, this project provides a comprehensive solution for certificate authority tasks.

## Features

- **Generate Certificates**: Create digital certificates with customizable details (e.g., common name, organization).
- **View Certificates**: List all issued certificates.
- **Revoke Certificates**: Mark certificates as revoked.
- **Verify Certificates**: Check the validity of certificates by common name.

## Technologies

- **Java**: Programming language used for the project.
- **Spring Boot**: Framework for building the web application.
- **Bouncy Castle**: Cryptographic library for generating and managing certificates.

## Usage

**Home Page**: Access the main page at http://localhost:8080.

**Generate**: Fill out the form at /generate to create a new certificate.

**View**: List all issued certificates at /view.

**Revoke**: Revoke a certificate by its ID using the form at /revoke.

**Verify**: Verify a certificate by its common name at /verify.


