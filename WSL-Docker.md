
The Windows Subsystem for Linux (WSL) is a feature of the Windows operating system that enables you to run a Linux file system, 
along with Linux command-line tools and GUI apps, directly on Windows, alongside your traditional Windows desktop and apps.

1) TO enable WSL and install Linux distro follow the blog https://linuxhint.com/install_ubuntu_windows_10_wsl/

2) WSL integration with docker, follow official documentation https://docs.docker.com/desktop/windows/wsl/

3) Type code . on Linux distro terminal, it will open docker remote container in vscode.

4) Follow the link to setup a hadoop cluster in Docker -

https://shortcut.com/developer-how-to/how-to-set-up-a-hadoop-cluster-in-docker?fbclid=IwAR1cm7PGri-8VuEAV-jnICy_Z0s23QL2koY7LxgaXdsGrG-oKr5ol-yvZSo

Problems faced : 1. WSL set to version 1,should've been 2.
                 2. INTEL VIRTUALIZATION TECHNOLOGY Disabled in BIOS, must be enabled.
