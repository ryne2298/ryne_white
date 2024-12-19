FROM mcr.microsoft.com/devcontainers/universal:2

# Install necessary tools
RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    nodejs \
    npm

# Install Vue.js and Flask
RUN npm install -g @vue/cli
RUN pip install flask