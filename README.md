﻿# Supported Windows Server, version 1903 amd64 tags

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-1903`

- 4.8-windowsservercore-1903, 4.8, latest ([4.8-windowsservercore-1903/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.8-windowsservercore-1903/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:3.5-windowsservercore-1903`

- 3.5-windowsservercore-1903, 3.5 ([3.5-windowsservercore-1903/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/3.5-windowsservercore-1903/runtime/Dockerfile))

# Supported Windows Server 2019 amd64 tags

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-ltsc2019`

- 4.8-windowsservercore-ltsc2019, 4.8, latest ([4.8-windowsservercore-ltsc2019/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.8-windowsservercore-ltsc2019/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.7.2-windowsservercore-ltsc2019`

- 4.7.2-windowsservercore-ltsc2019, 4.7.2 ([4.7.2-windowsservercore-ltsc2019/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.7.2-windowsservercore-ltsc2019/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:3.5-windowsservercore-ltsc2019`

- 3.5-windowsservercore-ltsc2019, 3.5 ([3.5-windowsservercore-ltsc2019/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/3.5-windowsservercore-ltsc2019/runtime/Dockerfile))

# Windows Server, version 1803 amd64 tags

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-1803`

- 4.8-windowsservercore-1803, 4.8, latest ([4.8-windowsservercore-1803/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.8-windowsservercore-1803/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.7.2-windowsservercore-1803`

- 4.7.2-windowsservercore-1803, 4.7.2, latest ([4.7.2-windowsservercore-1803/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.7.2-windowsservercore-1803/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:3.5-windowsservercore-1803`

- 3.5-windowsservercore-1803, 3.5 ([3.5-windowsservercore-1803/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/3.5-windowsservercore-1803/runtime/Dockerfile))

# Windows Server 2016 amd64 tags

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-ltsc2016`

- 4.8-windowsservercore-ltsc2016, 4.8, latest ([4.8-windowsservercore-ltsc2016/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.8-windowsservercore-ltsc2016/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.7.2-windowsservercore-ltsc2016`

- 4.7.2-windowsservercore-ltsc2016, 4.7.2, latest ([4.7.2-windowsservercore-ltsc2016/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.7.2-windowsservercore-ltsc2016/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.7.1-windowsservercore-ltsc2016`

- 4.7.1-windowsservercore-ltsc2016, 4.7.1 ([4.7.1-windowsservercore-ltsc2016/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.7.1-windowsservercore-ltsc2016/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.7-windowsservercore-ltsc2016`

- 4.7-windowsservercore-ltsc2016, 4.7 ([4.7-windowsservercore-ltsc2016/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.7-windowsservercore-ltsc2016/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.6.2-windowsservercore-ltsc2016`

- 4.6.2-windowsservercore-ltsc2016, 4.6.2 ([4.6.2-windowsservercore-ltsc2016/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/4.6.2-windowsservercore-ltsc2016/runtime/Dockerfile))

 `docker pull mcr.microsoft.com/dotnet/framework/aspnet:3.5-windowsservercore-ltsc2016`

- 3.5-windowsservercore-ltsc2016, 3.5 ([3.5-windowsservercore-ltsc2016/runtime/Dockerfile](https://github.com/Microsoft/aspnet-docker/blob/master/3.5-windowsservercore-ltsc2016/runtime/Dockerfile))


>**Note:** Multi-arch tags, such as 4.7.1, have been updated to use windowsservercore-1709 images if your host is Windows Server 1709 or higher or Windows 10 Fall Creators Update (Version 1709) or higher. You need Docker 17.10 or later to take advantage of these updated tags.

These images are updated via [pull requests to the `microsoft/aspnet-docker` GitHub repo](https://github.com/microsoft/aspnet-docker/pulls).

[![Downloads from Docker Hub](https://img.shields.io/docker/pulls/microsoft/aspnet.svg)](https://hub.docker.com/r/microsoft/aspnet)
[![Stars on Docker Hub](https://img.shields.io/docker/stars/microsoft/aspnet.svg)](https://hub.docker.com/r/microsoft/aspnet)

# What is ASP.NET

ASP.NET is a high productivity framework for building Web Applications using Web Forms, MVC, Web API and SignalR.

This repository contains `Dockerfile` definitions for ASP.NET Docker images. These images use the [IIS image](https://hub.docker.com/r/microsoft/iis/) as their base.

This image contains:
- Windows Server Core as the base OS
- IIS 10 as Web Server
- .NET Framework (multiple versions available)
- .NET Extensibility for IIS

# How to use these Images

Copy `4.7\sample\Dockerfile` to your app directory. You would then be able to build and run the site from the app directory.

```
$ docker build -t aspnet-site --build-arg site_root=/ .
$ docker run -d -p 8000:80 --name my-running-site aspnet-site
```

There is no need to specify an `ENTRYPOINT` in your Dockerfile since the `microsoft/aspnet` base image already includes an entrypoint application that monitors the status of the IIS World Wide Web Publishing Service (W3SVC).

### Verify in the browser

> With the current release, you can't use `http://localhost` to browse your site from the container host. This is because of a known behavior in WinNAT, and will be resolved in future. Until that is addressed, you need to use the IP address of the container.

Once the container starts, you'll need to finds its IP address so that you can connect to your running container from a browser. You use the `docker inspect` command to do that:

`docker inspect -f "{{ .NetworkSettings.Networks.nat.IPAddress }}" my-running-site`

You will see an output similar to this:

```
172.28.103.186
```

You can connect the running container using the IP address and configured port, `http://172.28.103.186` in the example shown.

For a comprehensive tutorial on running an ASP.NET app in a container, check out [the tutorial on the docs site](https://docs.microsoft.com/en-us/dotnet/articles/framework/docker/aspnetmvc).

## Image variants

The `microsoft/aspnet` images come in different flavors, each designed for a specific use case.

### `4.7.2`

This is the primary image. If you are unsure about what your needs are, you probably want to use this one.

This image is for ASP.NET applications built for the .NET Framework 4.0 and later versions. It is based on the [dotnet-framework:4.7](https://hub.docker.com/r/microsoft/dotnet-framework/) image and includes .NET Framework Extensibility for IIS.

### `4.7.1`, `4.7`, `4.6.2`

These images are for ASP.NET applications that need a specific .NET Framework version and have not been tested with .NET Framework 4.7.2. They are based on the corresponding [dotnet-framework](https://hub.docker.com/r/microsoft/dotnet-framework/) images and include .NET Framework Extensibility for IIS.

### `3.5`

This image is for ASP.NET applications built for the .NET Framework 3.5. It is based on the [dotnet-framework:3.5](https://hub.docker.com/r/microsoft/dotnet-framework/) image and includes .NET Framework Extensibility for IIS.

# Related Repos

See the following related repos for other application types:

- [microsoft/dotnet-framework](https://hub.docker.com/r/microsoft/dotnet-framework/) for .NET Framework applications.
- [microsoft/aspnetcore](https://hub.docker.com/r/microsoft/aspnetcore/) for ASP.NET Core applications.
- [microsoft/dotnet](https://hub.docker.com/r/microsoft/dotnet/) for .NET Core images.

# License

View [license information](https://www.microsoft.com/net/dotnet_library_license.htm) for the software contained in this image. 

Windows Container images are licensed per the Windows license:

MICROSOFT SOFTWARE SUPPLEMENTAL LICENSE TERMS

CONTAINER OS IMAGE

Microsoft Corporation (or based on where you live, one of its affiliates) (referenced as “us,” “we,” or “Microsoft”) licenses this Container OS Image supplement to you (“Supplement”). You are licensed to use this Supplement in conjunction with the underlying host operating system software (“Host Software”) solely to assist running the containers feature in the Host Software. The Host Software license terms apply to your use of the Supplement. You may not use it if you do not have a license for the Host Software. You may use this Supplement with each validly licensed copy of the Host Software.

# Supported Docker versions

This image is officially supported on Docker version 1.12.2.

Please see [the Docker installation documentation](https://docs.docker.com/installation/) for details on how to upgrade your Docker daemon.


# User Feedback


## Notes on ASP.NET container images for Windows Server 2019

Now that Windows Server 2019 is generally available, we have published ASP.NET container images for Windows Server 2019.  You can pull the new Windows Server Image via-
```
docker pull mcr.microsoft.com/dotnet/framework/aspnet:4.7.2-windowsservercore-ltsc2019
```
As you may have noticed in the `docker pull` command, the image is now being served from the Microsoft Container Registry (MCR). Starting with Windows Server 2019 and going forwards, all new tags will be published exclusively to MCR. All existing tags have been syndicated from DockerHub to MCR.
If your existing Dockerfile begins by specifying microsoft/aspnet as the base layer as shown below- 
```Dockerfile
FROM microsoft/aspnet:4.7.2-windowsservercore-ltsc2016
…
```
Our guidance is to move to adopting MCR as your base layer. You should change your Dockerfile to what’s shown below- 
```Dockerfile
FROM mcr.microsoft.com/dotnet/framework/aspnet:4.7.2-windowsservercore-ltsc2016
…
```
As part of this transition, we are only changing the source from where you download your images to MCR. DockerHub continues to be the preferred medium for container image discovery.  The Microsoft Container Registry does not have its own catalog experience and is meant to support existing catalogs such as Docker Hub, Red Hat Container Catalog, and Azure Marketplace.  This syndication model, enabling multiple channels of discovery, with a single download source for Microsoft’s container images.

## Issues

If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/microsoft/aspnet-docker/issues).

## Documentation

You can read [documentation for ASP.NET](https://docs.microsoft.com/aspnet/overview), including Docker usage in the [.NET docs](https://docs.microsoft.com/dotnet/framework/docker/aspnetmvc). 

The docs are also [open source on GitHub](https://github.com/dotnet/docs). Contributions are welcome!
