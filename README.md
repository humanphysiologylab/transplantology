# README

## models_ctypes
Этот репозиторий зависит от [models_ctypes](https://github.com/humanphysiologylab/models_ctypes), поэтому его нужно куда-то спулить

```shell
git clone https://github.com/humanphysiologylab/models_ctypes.git
```

и переключиться на нужную версию.
```shell
cd model_ctypes
git checkout ORd_transplantology
```
После этого собрать
```shell
cd src/model_ctypes/_ohara_rudy
make clean && make
```
