# Secure Server Deployment with SSH, TLS, and Custom Certificate Authority

This project demonstrates how to configure a secure server using SSH for remote access, SSL/TLS for encrypted communication, and a manually created Certificate Authority (CA) for HTTPS.

This is a practical guide suitable for students, developers, or system administrators interested in learning real-world cryptographic protocols and secure deployment practices.

---

## Project Objectives

### Part I – SSH Setup

- Install and configure OpenSSH server
- Connect to localhost using:
  - Password authentication
  - RSA key-based authentication

### Part II – Create a Root Certificate Authority (CA)

- Generate a private key for your CA
- Create a self-signed certificate for the CA

### Part III – Generate and Sign Server Certificate

- Create a public/private key pair for the server
- Generate a Certificate Signing Request (CSR)
- Sign the CSR using the root CA to create a valid server certificate

### Part IV – Configure and Launch HTTPS Server

- Combine server key and certificate into a single `.pem` file
- Modify the `/etc/hosts` file to route a domain to `127.0.0.1`
- Start an HTTPS server using OpenSSL
- Import the CA certificate into your browser to establish trust

---


