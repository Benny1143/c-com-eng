# VScode Devcontainer Template for C

This template utilizes vscode dev container to build docker container for development use, the steps are as follows:
1. Open VSCode
2. Install `Remote Development` extension
3. `Ctrl + Shift + P` in VS code > `Dev Containers: Rebuild and Reopen in container`
4. Click `Install` when prompted:
> Do you want to install the recommended extensions from Microsoft for this repository?

## Compiling C
Command
```shell
gcc -o <name> <filename.c>
```