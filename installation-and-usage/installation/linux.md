---
description: How to install RuntimeTrim on Linux
---

# 🐧 Linux

There are two ways to install RuntimeTrim on Linux:

### The PPA method (for Ubuntu users)

Ubuntu users running on an AMD64 or an ARM64 system can install this application using our PPA.

1. Open the terminal emulator
2.  Execute the following commands:

    ```shell-session
    $ sudo add-apt-repository ppa:eofla/aptivi-devapps
    $ sudo apt update
    $ sudo apt install runtimetrim
    ```

### The manual method

To install RuntimeTrim on Linux, the steps are fairly simple. Just follow the instructions outlined below.

{% hint style="info" %}
Please note that you need to be on a system running a supported Linux distribution and containing an installation of the .NET runtime.
{% endhint %}

1. Download the rar file from the latest version from [this page](https://github.com/Aptivi/nuglobal/releases).
2. Use an archive extracting tool to extract the binaries to any folder you like.
3. Open a terminal emulator, change the working directory to the folder that contains the binaries (for example, the `cd` command), and execute "`dotnet RuntimeTrim.dll`".
