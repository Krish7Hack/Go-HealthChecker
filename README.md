# Go-HealthChecker
# Health Checker App

A simple GoLang application to check the health of a website or server by testing its reachability.

## Features
- **Reachability Check**: Verifies if a domain and port are accessible over the network.
- **Port Specification**: Allows users to specify a port for the check or defaults to port 80.
- **Lightweight CLI**: Provides a simple command-line interface for quick use.

## Usage

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/health-checker.git
   cd health-checker
2. **Install dependencies**:
   ```bash
   go mod tidy
3.**Run the application**:

  ```bash
  go run main.go --domain example.com --port 80

