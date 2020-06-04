# example-netcore-opentk

opengl with netcore using opentk

## examples

to change between examples issue a `git checkout BRANCH` to change branch

Branches list:

- master : triangle with shader
- 01 : use of shader input variable from code through uniform location

## how to run

```sh
cd example-netcore-opentk
dotnet run
```

## how this project was built

```sh
dotnet new console -n example-netcore-opentk
cd example-netcore-opentk
dotnet add package OpenTK --version 4.0.0-pre9.1
```
