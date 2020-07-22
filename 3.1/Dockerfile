FROM mcr.microsoft.com/dotnet/core/aspnet:3.1
MAINTAINER Krzysztof Kawalec <kf.kawalec@gmail.com>
RUN apt-get update \
    && DEBIAN_FRONTEND=noninteractive apt-get install -y \
        libgdiplus \
        libc6-dev \
        procps \
        telnet \
        iputils-ping \
        nano \
        gettext-base \
    && apt-get clean \
    && rm -r /var/lib/apt/lists/*
