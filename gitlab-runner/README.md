# <img src="https://cdn.rawgit.com/majkinetor/chocolatey/master/gitlab-runner/icon.png" width="48" height="48"/>  [gitlab-runner](https://chocolatey.org/packages/gitlab-runner)

GitLab Runner is the open source project that is used to run your jobs and send the results back to GitLab. It is used in conjunction with GitLab CI, the open-source continuous integration service included with GitLab that coordinates the jobs.

## Features

- Allows to run:
  - multiple jobs concurrently
  - use multiple tokens with multiple server (even per-project)
  - limit number of concurrent jobs per-token
- Jobs can be run:
  - locally
  - using Docker containers
  - using Docker containers and executing job over SSH
  - using Docker containers with autoscaling on different clouds and virtualization hypervisors 
  - connecting to remote SSH server
- Is written in Go and distributed as single binary without any other requirements
- Supports Bash, Windows Batch and Windows PowerShell
- Works on GNU/Linux, OS X and Windows (pretty much anywhere you can run Docker)
- Allows to customize the job running environment
- Automatic configuration reload without restart
- Easy to use setup with support for Docker, Docker-SSH, Parallels or SSH running environments
- Enables caching of Docker containers
- Easy installation as a service for GNU/Linux, OSX and Windows
- Embedded Prometheus metrics HTTP server

## Package parameters

- `InstallDir` - Installation directory. If the Gitlab Runner is already installed, its current directory will be used. To install to a new directory, uninstall it first.

## Notes

- The script `register_example.ps1` is provided along the executable which can be used to quickly register runner non-interactively. If you want to use it, rename it, because it will be overwritten on updates.