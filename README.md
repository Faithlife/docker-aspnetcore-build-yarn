# `faithlife/aspnetcore-build-yarn` Docker Image

Image for building ASP.NET Core 2.2 applications with Yarn installed.

This image was built with the command: `docker build . -t faithlife/aspnetcore-build-yarn:2019.03`.

This image was pushed to Docker Hub using an authorized account with the command `docker push faithlife/aspnetcore-build-yarn:2019.03`.

## Branches & Versions

When updating versions, create a new branch with the version name (current year and month) and ensure the changes go on that branch. The `master` branch tracks the `latest` version.

* `2019.03`
  * ASP.NET Core: 2.2
  * Node.js : 11.11.0
  * Yarn : 1.13.0
* `2018.01`
  * ASP.NET Core: 2.0.5
  * Node.js : 8.9.4
  * Yarn : 1.3.2
