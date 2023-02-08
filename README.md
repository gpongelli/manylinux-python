# Manylinux Docker images with compiled Python

[![Pulls](https://img.shields.io/docker/pulls/gpongelli/pgadmin4-arm.svg?style=flat-square&logo=docker)](https://hub.docker.com/r/gpongelli/pgadmin4-arm/)


Docker images from Manylinux `quay.io/pypa/manylinux_2_28_x86_64:2023-02-05-56647d4` that contains compiled Python into
`/opt/build_python/installed` folder.

Made to be used with [cibuildwheel](https://github.com/pypa/cibuildwheel) when building Python C-extension project, to avoid around 10 minutes per
python version of wasted time.


* GitHub: <https://github.com/gpongelli/pycode128>
* Free software: MIT

