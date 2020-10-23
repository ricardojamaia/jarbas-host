# Machine Learning Python Container
This project provides the basis for starting a machine learning project using Remote-Containers in MS Visual Source Code.
The following packages are installed by default:
- Tensorflow 2
- OpenCV 3

It is based in mcr.microsoft.com/vscode/devcontainers/python

## How to get it running
1. Install Docker Desktop ([download][1])
2. Install MS Visual Source Code ([download][2])
3. Clone ricardojamaia/ml-python-container GitHub repository
  1. View -> Command Pallete ...
  2. Type and select 'Git Clone'
  3. Enter 'https://github.com/ricardojamaia/ml-python-container.git'
  4. VS Code will prompt you to open the repository
4. Open repository in VS Code
5. Install 'Remote - Containers' VS Code extension
  1. VS Code will propmt you to install the recommended extensions i.e. Remote - Containers (ms-vscode-remote.remote-containers)
  2. If necessary search it manually on marketplace
  3. Click on install
6. Reopen in Container
  1. VS Code will detect a .devcontainer folder and prompt you to reopen the folder in container
  2. Reopen folder in container
  
That's it you should be able to start coding. An main.py file is provided by default.



[1]: https://www.docker.com/products/docker-desktop
[2]: https://code.visualstudio.com/download
