# Cloud Native Days

This repository contains the source code for the Cloud Native Days website. Use this `README` to get started with setting up a local development environment.

## Prerequisites

- [Hugo](https://gohugo.io/) (Extended version recommended, v0.136.2)
- [Go](https://golang.org/) (v1.16+)

## Running Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-org/cloud-native-days.git
    cd cloud-native-days
    ```

2.  **Install dependencies:**
    ```bash
    hugo mod get -u
    ```

3.  **Start the development server:**
    ```bash
    hugo server
    ```
    The site will be available at `http://localhost:1313`.

## Local Development with Devcontainers

This project includes a `.devcontainer` configuration for Visual Studio Code, which automates the setup of the development environment.

1.  **Install Visual Studio Code** and the **Dev Containers** extension.
2.  **Open the project** in VS Code.
3.  Click **Reopen in Container** when prompted, or run the command from the Command Palette (`F1` > `Dev Containers: Reopen in Container`).

This will launch a container with Hugo 0.136.2 and Go 1.16 pre-installed, ensuring a consistent environment.
