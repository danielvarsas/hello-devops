# Hello DevOps (React + Vite)

This is a simple web application that displays “Hello DevOps!” in the browser.

The project is built using React and **Vite.  
Follow the steps below to run it.

---

## 1. Requirements

To run this project, you need:

- **Node.js** (recommended version: 20.19 or newer)  
  Download: https://nodejs.org

To check if Node.js is installed, run:

```bash
node -v
npm -v
```

## 2. Downloading the Project

You can download the project in two ways:

## Option A — Download ZIP

Go to GitHub → click "Code" → "Download ZIP"

Extract the ZIP file to any folder

Open the folder in VS Code (optional)

## Option B — Using Git

```bash
git clone <REPOSITORY_LINK>
```
Then open the folder:

```bash
cd hello-devops
```

## 3. Install Dependencies

```bash
npm install
```

## 4. Start the Development Server (Run Locally)

```bash
npm run dev
```

After starting, the terminal will show a local URL such as:

```bash
http://localhost:5173
```

Open this link in your browser.

---

## Docker

This project can also be built and executed inside a Docker container.

### 1. Build the Docker image

Run the following command in the project root folder (where the Dockerfile is located):

```bash
docker build -t hello-devops:v1 .
```

## 2. Run the container

To start the application inside a Docker container:

```bash
docker run -p 8080:80 hello-devops:v1
```

After running the command, the app will be available in your browser at:

```bash
http://localhost:8080
```


