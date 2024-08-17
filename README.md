# wasm_python

## 目標

pythonコードをwasmに変換して実行

## 手順

pythonをwasmに変換

> `pip install py2wasm`
> `py2wasm main.py`

実行環境

> `curl https://get.wasmer.io -sSfL | sh`
> `source ~/.wasmer/wasmer.sh`
> `wasmer --version`
> `wasmer run main.wasm`
