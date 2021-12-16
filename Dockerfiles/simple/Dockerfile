FROM mcr.microsoft.com/dotnet/core/sdk:3.1-alpine

RUN apk update \ 
  && apk add openjdk11 \
  && dotnet tool install --global dotnet-sonarscanner
