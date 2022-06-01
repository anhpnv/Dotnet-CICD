# https://hub.docker.com/_/microsoft-dotnet
FROM mcr.microsoft.com/dotnet/sdk:6.0 AS build
WORKDIR /source

# copy csproj and restore as distinct layers
COPY publish/aspnetapp.dll .
ENTRYPOINT ["dotnet", "aspnetapp.dll"]
