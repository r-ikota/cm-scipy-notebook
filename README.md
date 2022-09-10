# cm-scipy-notebook
Customized data science notebook container

## Example
    $ docker pull ghcr.io/r-ikota/cm-scipy-notebook:latest
    $ docker run -it --rm -p 8888:8888 -v "${PWD}":/home/jovyan/work ghcr.io/r-ikota/cm-scipy-notebook:latest