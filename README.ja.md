# NEologd : Neologism dictionary generator

NEologd は多数の言語資源を使って新語辞書を生成します。

新語辞書のエントリは各新語に対して以下の4カラムを持ちます。

- 表層
- 発音
    - 日本語 : フリガナ
    - 英語 : IPA (International Phonetic Alphabet)
- 表層の原型
- 品詞情報

NEologd はあなたの代わりにこの世における新語の発生に対処します。

##応用事例
- mecab-ipadic-neologd
    - MeCab のための新語辞書
        - https://github.com/neologd/mecab-ipadic-neologd

- mecab-unidic-neologd
    - UniDic にエントリを足して MeCab のシステム辞書としてインストールするためのシードデータとスクリプト群のセット
        - https://github.com/neologd/mecab-unidic-neologd

## Copyrights
Copyright (c) 2015 Toshinori Sato (@overlast) All rights reserved.
