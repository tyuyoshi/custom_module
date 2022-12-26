# custom_module

### poetry 初期設定
```
$ poetry config virtualenvs.in-project true
$ poetry install --no-root

# 仮想環境に入る
$ poetry shell
(custom-module-py3.9) $
```

### nbdime 設定
Jupyter を起動し、ファイルの差分をWeb上で確認できるようになる。
```
(custom-module-py3.9) $ sudo nbdime extensions --enable
```

### nbdev 設定
Notebook を保存する際、実行結果を残さないようになる。
```
(custom-module-py3.9) $ nbdev_install_hooks
```
