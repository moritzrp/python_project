FROM mcr.microsoft.com/devcontainers/python:2-3.13-trixie

USER vscode

RUN curl -sSL https://install.python-poetry.org | python3 -
ENV PATH="/home/vscode/.local/bin:$PATH"
RUN poetry self add poetry-plugin-shell
