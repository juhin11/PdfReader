# SIMPLE QT PDFREADER

This project is a simple pdf reader.
### Library
- [Poppler](https://poppler.freedesktop.org/)
- [Qt](https://www.qt.io/)


### How To Try This Project
- #### Requirement
  - Linux, using the command below to install requirement
    ```shell
    sudo apt install qtcreator cmake lippopler-qt5-dev pkg-config 
    ```
  - Mac, using the command below to install requirement
    ```shell
    brew install qtcreator qt5 poppler-qt5 cmake pkg-config 
    ```
- #### Building And Runnig
  - clone this repo and running the command below to build and running
    ```shell
    mkdir buid && cd build && cmake .. && make && ./qtpdfreader
    ```