事前にAnaconda環境のインストールと、conda-forgeチャンネルの追加は終わっているものとします。

コンソール画面で以下を実行

```python
conda install numpy pandas scipy scikit-learn matplotlib seaborn xlrd
```

必要なパッケージのインストールがこれでできます。

次にプログラムの実行環境（jupyter-notebook）を起動します。

```python
jupyter-notebook
```

デフォルトではユーザーフォルダのフォルダリストが表示されるので、プログラムを置いておきたいフォルダまで移動しましょう。
最初に表示されたフォルダ階層より上にはいけないので注意。

もし最初から目的のフォルダ内を表示して欲しいのなら、コンソールから事前にcdコマンドでフォルダを移動しておく必要があります。
