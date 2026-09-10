# BSL HTTP Server

## 1. Project Description
This project is a low-level HTTP Web Server constructed from scratch using the **Bonezegei Scripting Language (BSL)** and the official **BSL Socket Library**. 

The server initializes a raw TCP socket, binds to port `8080`, listens for incoming client requests, and handles route dispatching based on raw HTTP `GET` request headers. It features custom route handling for:
- A landing **Home** page (`/`)
- An **About** page (`/about`)
- A **404 Not Found** response for any unmapped paths (e.g., `/anything`)

## 2. Installation & Setup Guide

### Prerequisites
1. **VS Code & Extension**: Install Visual Studio Code along with the **Bonezegei Scripting Language Formatter** extension.
2. **BSL Engine**: Ensure the Bonezegei Script Interpreter (`v1.3.1` or higher) is installed on your system.

### Installation
Open your terminal or PowerShell and install the required socket dependency:

```powershell
bzg install socket