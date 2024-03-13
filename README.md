# BBCode-Usage

BBCodeを使用することで、あなたのプロフィールの見た目を簡単に編集することができます。
基本的な書き方を学習し、あなただけのオリジナルをプロフィールページを作ってみましょう！

BBCode makes it easy to edit the look and feel of your profile.
Learn the basic writing style and create your own unique profile page!

#### Click [here]() for an explanation in English.

## 日本語

### 基本的な書き方とフォーマットの構文

### 見出し

見出しを作成するには、``[heading]``を文章の前と後に追加します。

```
[heading]text[/heading] 
```

### テキストフォーマット

以下のスタイルを適用することで、テキストを強調することができます。

|スタイル|構文|例|出力|
|---|---|---|---
|太字|[b] [/b]|[b]text[/b]|**This is bold text**|
|斜体|[i] [/i]|[i]text[/i]|_This text is italicized_|
|下線|[u] [/u]|[u]text[/u]|<ins>This text is underlined</ins>|
|取り消し線|[s] [/s]|[s]text[/s]|~~This was mistaken text~~|

### テキストの引用

``[quote]``を使用してテキストを囲みます

```
[quote name="title"]text[/quote] 
```

> **title wrote:**
> 
> text

### コードの引用

単一のバッククォートで文章内のコードやコマンドを引用できます。独立したブロック内にコードあるいはテキストをフォーマットするには、``[code]``を使用します。

特定の文字のみをフォーマットするには``[c]``を使用します。

```
[c]git status[/c]

[code]git add[/code]
```

``git status``

```
git add
```

### 文字のカスタマイズ

``[color]``や``[size]``オプションを使用すると文字の大きさや文字色を簡単に変更することができます。``val``に代入する値は自由に決められます。``val``の値を変更することで、より詳細な変更を行えます。

``[spoiler]``や``[centre]``オプションを使用すると文字揃えや文字を隠すことができます。

|Option|Color|構文|例|説明|
|---|---|---|---|---|
|color|HEX|[color val="#HEXCODE"][/color]|[color val="#0969DA"]text[/color]|囲まれた部分の文字色を変更します|
|size||[size val="NUMBER"][/size]|[size val="50"]text[/size]|囲まれた部分の文字の大きさを変更します|
|spoiler||[spoiler][/spoiler]|[spoiler]text[/spoiler]|囲まれた文字を隠します|
|centre||[centre][/centre]|[centre]text[/centre]|囲まれた文字を中央揃えにします|

### リンク

#### マスクリンク

マスクリンクを使用すると、テキストをクリックまたは押下可能なハイパーリンクにすることができます。そのためには``[url]``を使用する必要があります。

```
[url link="URL"]text[/url]
```

[text](url)

#### プロフィールのリンク

プロフィールのリンクを設定すると、簡単にプロフィールページへアクセスできるマスクリンクを作成することができます。そのためには``[profile]``を使用する必要があります。

```
[profile]<id>[/profile] プロフィールのリンク
```

[緒山まひろ](https://web.mamesosu.net/profile/3/stdrx)

### リスト

``[list]``を使用することで順序なしリストを作成できます。

#### 基本的なリストの作成

```
[list][*]text[/list]
```

- text

#### 応用的なリストの作成

```
[list type="TYPE"][*]text[/list] 
```

##### 使用可能なリスト形式

```js
[
    undefined,
    "none",
    "disc",
    "circle",
    "square",
    "dec",
    "dec-zero",
    "roman-s",
    "roman-l",
    "greek",
    "cjk",
    "hebrew",
    "armenian",
    "georgian",
    "hira",
    "hira-iroha",
    "kata",
    "kata-iroha",
    "alpha-s",
    "alpha-l"
]
```

### ドロップダウンリスト

``[box]``を使用することで、ボタンをクリックしたときに表示されるドロップダウンリストを作成することができます。

```
[box name="NAME"]text[/box]
```

<details>
<summary>NAME</summary>
<pre>
text
</pre>
</details>

### 画像の表示

``[img]``を使用することで、URLから画像を表示することができます。

```
[img]URL[/img] 
```

![pic](https://img.mamesosu.net/1 "pic")

## English
