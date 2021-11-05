# mcgonagle/101

[![Docker Automated Build](https://img.shields.io/docker/automated/mcgonagle/101.svg?style=flat-square)](https://hub.docker.com/r/mcgonagle/101/) [![Apache-2.0 License](https://img.shields.io/github/license/mcgonagle/101.svg?style=flat-square)](https://github.com/mcgonagle/101/blob/master/LICENSE) [![Docker Build Status](https://img.shields.io/docker/build/mcgonagle/101.svg?style=flat-square)](https://hub.docker.com/r/mcgonagle/101/builds/)

This is a basic Docker image for building and previewing [Hovercraft](https://github.com/regebro/hovercraft) the 101 presentation. The image is available for public use on Docker Hub at [mcgonagle/101](https://hub.docker.com/r/mcgonagle/101/).

## Usage

To Build:
``` bash
docker build --tag=mcgonagle/101 .
```

To Run:
``` bash
docker run -it --rm -p "9000:9000" -v mcgonagle/101
```

In a web browser, go to <http://localhost:9000> to view your presentation.


