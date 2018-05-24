# LitDocs

This directory contains the stuff needed for generating docs

`template.html` contains the template used for generating the docs. The only dependency  required as of now is `bootstrap.min.css`, which is also present in the scripts directory.

If you'd like to build lit cross-platform, jsut do `env GOOS=linux GOARCH=arm go build -v github.com/mit-dci/lit` where env refers to your target distro and arch refers to your system architecture

Repos of lit that you may be interested in:

lit: https://github.com/mit-dci/lit
webui: https://github.com/josephtchung/webui
dlcoracle: https://github.com/mit-dci/dlcoracle
docs: <this repo>
