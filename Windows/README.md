# Windows Sample Container Examples

## Below are the following Windows Container Samples
* [Windows Server Core With Script](Servercore-Script)
* [PowerShell With Script](Pwsh-Script)

## Build the images in the respective folders using
`docker build -t <image-name> .`

## After building, run the container
`docker run --name <image-name> -it --rm <image-name>`. *NOTE: The `--rm` switch will remove the container when it is stopped*
