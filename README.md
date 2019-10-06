# .NET project template builder for IDQ4P
template __idq4p__ is created

## Build template
```
dotnet pack -c Release
```

## Install template
```
dotnet new -i ./bin/Release/<template name>.nupkg
```

## Use template
```
mkdir <proj folder>
cd <proj folder>
dotnet new idq4p
dotnet run [-c Release]
```

## Uninstall template
```
dotnet new -u <template name>
```