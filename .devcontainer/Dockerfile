ARG VARIANT=16
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:${VARIANT}

RUN npm install -g @angular/cli@16.0.0 firebase-tools
RUN ng config --global cli.packageManager yarn