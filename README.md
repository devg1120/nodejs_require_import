
https://qiita.com/TakeshiNickOsanai/items/7899a60044d71aa8d899

# ESModule (import) の有効化

## 以下の場合、ESModuleを利用するものとして扱われる。

- 拡張子が.mjsのファイル
- package.json ファイルの "type" フィールドに "module" という値を含んでおり、拡張子が .js のファイル
- evalの引数として渡された文字列、またはSTDIN経由でnodeにパイプされた文字列で、 --input-type=moduleのフラグがあるもの

```
ESModuleの利用を前提とする場合、package.json もしくは拡張子に設定を加える必要がある。
```


