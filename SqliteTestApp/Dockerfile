FROM microsoft/dotnet:2.2.1-aspnetcore-runtime-alpine
ARG source
WORKDIR /app
COPY ${source:-obj/Docker/publish} .