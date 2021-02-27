FROM mcr.microsoft.com/dotnet/core/aspnet:2.2-stretch-slim AS base

COPY vandnagarg vandnagarg/
WORKDIR /vandnagarg
ENTRYPOINT ["dotnet", "dotnet.dll"]
EXPOSE 80
EXPOSE 443