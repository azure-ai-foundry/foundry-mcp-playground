FROM mcr.microsoft.com/devcontainers/python:dev-3.11

# Install Azure CLI and clean up
RUN curl -sL https://aka.ms/InstallAzureCLIDeb | bash && \
    apt-get update && \
    apt-get install -y azure-cli && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*