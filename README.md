# demo-tools
a variety of python scripts for demonstrating functions and processes

## WSL 2.0 setup

For interactive plots to work through windows subsystem for linux (WSL) 2.0 you may need to install the following

```shell
sudo apt-get install python3-tk
```


## Setup

```shell
git clone git@github.com:Tylores/demo-tools.git
cd demo-tools
poetry update
```

## Running

From the demo-tools folder you can run any of the demo scripts using the following command after replaceing the **<filename>** with the desired file to run.

```shell
poetry run python scripts/<filename>
```
