# cm-scipy-notebook
Customized data science notebook container

## Example
    $ docker build -t cm-scipy-notebook:2022-05-28
    $ docker run -it --rm -p 8888:8888 -v "${PWD}":/home/jovyan/work cm-scipy-notebook:2022-05-28