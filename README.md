# Mock Server Project

This project is a mock server that processes JSON files from a specified directory, combines the results, and writes the output to designated files. The server is built with Node.js and uses `pnpm` for package management.

## Prerequisites

- Node.js (v14.x or higher)
- pnpm (v6.x or higher)

## Setup

1. **Clone the repository**

   ```bash
   $ git clone https://github.com/your-username/mock-server.git
   $ cd mock-server
   ```

2. **Copy the environment configuration file**

   ```bash
   $ cp .env.example .env
   ```

3. **Install dependencies**

   ```bash
   $ pnpm install
   ```

4. **Create the necessary directories**

   ```bash
   $ mkdir db
   $ mkdir postman
   ```

5. **Copy Postman collection JSON files to the `postman` directory**

   Ensure your Postman collection JSON files are placed in the `postman` directory.

   ```bash
   $ cp /path/to/your/postman/collections/*.json ./postman/
   ```

## Running the Server Locally

To launch the server locally, run the following command:

```bash
$ pnpm start
```
