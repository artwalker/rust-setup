# Function
The function will print "Hello Rust" when run it.

# Interesting Aspect of Copilot
I find Copilot alway give me some new idea about code or what I am thinking about.
It's a very fascinating.

# Describe the configuration and how to use it
## devcontainer.json
"customizations": {
    "vscode": {
        "extensions": [
            "rust-lang.rust-analyzer",
            "vadimcn.vscode-lldb",
            "GitHub.copilot-nightly",
            "GitHub.copilot-chat"
        ]
    }
}
It will alow the vscode to install these extensions automatically when create the codespaces about these repository.

## Dockerfile
FROM mcr.microsoft.com/devcontainers/rust:0-1-bullseye
RUN apt update

These codes will add the stuffs about rust dev container and run apt update from system layer.