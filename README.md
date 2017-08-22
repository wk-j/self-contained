## Self Contained

- https://www.hanselman.com/blog/SelfcontainedNETCoreApplications.aspx

```
dotnet build -r win10-x64           Source/SelfContained.csproj
dotnet build -r osx.10.10-x64       Source/SelfContained.csproj
dotnet build -r ubuntu.14.04-x64    Source/SelfContained.csproj

dotnet publish -c release -r win10-x64          Source/SelfContained.csproj
dotnet publish -c release -r osx.10.10-x64      Source/SelfContained.csproj
dotnet publish -c release -r ubuntu.14.04-x64   Source/SelfContained.csproj
```