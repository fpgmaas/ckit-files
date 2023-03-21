<p align="center">
  <img alt="ckit logo" width="300" height="300" src="https://raw.githubusercontent.com/fpgmaas/ckit/main/docs/static/ckit-logo.svg">
</p>


# ckit-files

This repository contains configuration files that can be used with [ckit](https://fpgmaas.github.io/ckit/). In order to use these configuration files, make sure you have ckit installed and simply place them in the `~/ckit` directory (Or the directory specified by `CKIT_HOME` if you that is set in your environment). 

It is also possible to place the configuration files in your current working directory; in that case, the commands will only be available to `ckit` in your current working directory.

## Quickstart

If you do not have `ckit` installed yet and want to quickly get started with any of the files here, run the following set of commands:

```shell
pip install ckit
mkdir ~/ckit
cd ~/ckit
curl -O https://raw.githubusercontent.com/fpgmaas/ckit-files/main/kubernetes.yaml
```

Now to use any of the commands from the configuration file, simply run:

```
ckit
```

For more information, see the [documentation](https://fpgmaas.github.io/ckit/).
