# mcgonagle/sharhack

[![Docker Automated Build](https://img.shields.io/docker/automated/mcgonagle/sharkhack.svg?style=flat-square)](https://hub.docker.com/r/mcgonagle/sharkhack/) [![Apache-2.0 License](https://img.shields.io/github/license/mcgonagle/sharkhack.svg?style=flat-square)](https://github.com/mcgonagle/sharkhack/blob/master/LICENSE) [![Docker Build Status](https://img.shields.io/docker/build/mcgonagle/sharkhack.svg?style=flat-square)](https://hub.docker.com/r/mcgonagle/sharkhack/builds/)

This is a basic Docker image for building and previewing [Hovercraft](https://github.com/regebro/hovercraft) the SharkHack presentation. The image is available for public use on Docker Hub at [mcgonagle/sharkhack](https://hub.docker.com/r/mcgonagle/sharkhack/).

## Usage

To Build:
``` bash
docker build --tag=mcgonagle/sharhack .
```

To Run:
``` bash
docker run -it --rm -p "9000:9000" -v mcgonagle/sharhack
```

In a web browser, go to <http://localhost:9000> to view your presentation.


