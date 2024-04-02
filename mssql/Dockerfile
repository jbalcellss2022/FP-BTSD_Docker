ARG MSSQL_VERSION

# Set your timezone
ENV TZ=Europe/Madrid
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

FROM mcr.microsoft.com/mssql/server:${MSSQL_VERSION}