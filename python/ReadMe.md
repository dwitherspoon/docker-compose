# Python

## Add Alias
alias docker-python='docker run -it --rm --name python -v "$PWD":/usr/src/myapp -w /usr/src/myapp python:2 python'
alias docker-python3='docker run -it --rm --name python3 -v "$PWD":/usr/src/myapp -w /usr/src/myapp python:3 python'