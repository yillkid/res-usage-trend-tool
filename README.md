# res-usage-trend-tool

Resource (CPU and memory) usage trend meter

## Pre-prepare packages

``` bash
$ pip3 install psrecord 
```

``` bash
$ sudo apt-get install python-matplotlib python-tk
```

## Usage

#### Example
``` bash
$ psrecord $(pgrep proc-name1) --interval 1 --plot plot1.png
```
