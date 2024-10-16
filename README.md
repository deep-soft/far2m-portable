[![build](https://github.com/spvkgn/far2l-portable/actions/workflows/build.yml/badge.svg)](https://github.com/spvkgn/far2l-portable/actions/workflows/build.yml) ![version](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/spvkgn/f53cb6c1d56b0eaf40c88d607fc5fef1/raw/far2l-portable.json)
# [FAR2M](https://github.com/shmuz/far2m) File Manager portable | AppImage
## Download and run
### Self-extractable tar-archive
with TTY X/Xi backend
* built on Alpine | ~20 MB (x86_64 x86 aarch64 armhf armv7 ppc64le s390x)
```
wget -qO- https://github.com/spvkgn/far2m-portable/releases/download/latest/far2m_$(uname -m).run.tar | tar -xv -C /tmp && /tmp/far2m_*.run
```
* built on Ubuntu 16.04 | ~30 MB (x86_64 only)
```
wget -qO- https://github.com/spvkgn/far2m-portable/releases/download/latest/far2m_$(uname -m)-glibc.run.tar | tar -xv -C /tmp && /tmp/far2m_*.run
```
### AppImage
with wx-GUI and some extra plugins
* built on Ubuntu 20.04 | ~45 MB (x86_64 only)
```
wget -qO- https://github.com/spvkgn/far2m-portable/releases/download/latest/far2m_$(uname -m).AppImage.tar | tar -xv -C /tmp && /tmp/far2m_*.AppImage
```
Or get the binary in [Releases](https://github.com/spvkgn/far2m-portable/releases)
