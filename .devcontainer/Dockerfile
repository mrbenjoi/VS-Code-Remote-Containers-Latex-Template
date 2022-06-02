# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.209.6/containers/ubuntu/.devcontainer/base.Dockerfile

# [Choice] Ubuntu version (use hirsuite or bionic on local arm64/Apple Silicon): hirsute, focal, bionic
ARG VARIANT="hirsute"
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    texlive \
    texlive-lang-german \
    texlive-lang-english \
    texlive-extra-utils \
    texlive-latex-extra \
    texlive-science \
    texlive-pictures \
    texlive-plain-generic \
    texlive-font-utils \
    texlive-formats-extra \
    texlive-bibtex-extra \
    texlive-luatex \
    texlive-publishers \
    texlive-metapost \
    texlive-pstricks \
    texlive-humanities \
    chktex \
    latexmk
