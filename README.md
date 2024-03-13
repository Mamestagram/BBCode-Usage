# BBCode-Usage

BBCodeを使用することで、あなたのプロフィールの見た目を簡単に編集することができます。
基本的な書き方を学習し、あなただけのオリジナルをプロフィールページを作ってみましょう！

BBCode makes it easy to edit the look and feel of your profile.
Learn the basic writing style and create your own unique profile page!

#### Click [here](https://github.com/Mamestagram/BBCode-Usage/tree/main?tab=readme-ov-file#english) for an explanation in English.

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

### Basic writing and formatting syntax

### Headline

To create a heading, add ``[heading]`` before and after the sentence.

```
[heading]text[/heading] 
```

### Text Format

Text can be emphasized by applying the following styles

|Style|Syntax|Example|Output|
|---|---|---|---
|Bold|[b] [/b]|[b]text[/b]|**This is bold text**|
|Italic|[i] [/i]|[i]text[/i]|_This text is italicized_|
|Underline|[u] [/u]|[u]text[/u]|<ins>This text is underlined</ins>|
|Strike-through line|[s] [/s]|[s]text[/s]|~~This was mistaken text~~|

### Text Quote

Enclose text using ``[quote]``.

```
[quote name="title"]text[/quote] 
```

> **title wrote:**
> 
> text

### Code Quote

You can quote codes or commands in a sentence with a single back quote. To format a code or text in a separate block, use ``[code]``.

To format only certain characters, use ``[c]``.

```
[c]git status[/c]

[code]git add[/code]
```

``git status``

```
git add
```

### Customize Text

The ``[color]`` and ``[size]`` options allow you to easily change the font size and font color. You can assign any value to ``val``. By changing the value of ``val``, you can make more detailed changes.

The ``[spoiler]`` and ``[center]`` options can be used for text justification and text hiding.

|Option|Color|構文|例|説明|
|---|---|---|---|---|
|color|HEX|[color val="#HEXCODE"][/color]|[color val="#0969DA"]text[/color]|Change the text color of the enclosed area|
|size||[size val="NUMBER"][/size]|[size val="50"]text[/size]|Change the size of the text in the enclosed area|
|spoiler||[spoiler][/spoiler]|[spoiler]text[/spoiler]|Hides the enclosed text|
|centre||[centre][/centre]|[centre]text[/centre]|Centers the enclosed text|

### Link

#### Masked Link

Mask links can be used to make text a clickable or pressable hyperlink. To do so, you must use ``[url]``.

```
[url link="URL"]text[/url]
```

[text](url)

#### Profile Link

Setting up a profile link allows you to create a masked link to easily access your profile page. To do so, you must use ``[profile]``.

```
[profile]<id>[/profile] プロフィールのリンク
```

[緒山まひろ](https://web.mamesosu.net/profile/3/stdrx)

### List

You can use ``[list]`` to create an unordered list.

#### Create a basic listing

```
[list][*]text[/list]
```

- text

#### Create an applied listing

```
[list type="TYPE"][*]text[/list] 
```

##### Available List Formats

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

### Dropdown list

``[box]`` allows you to create a drop-down list that appears when you click a button.

```
[box name="NAME"]text[/box]
```

<details>
<summary>NAME</summary>
<pre>
text
</pre>
</details>

### Image

You can use ``[img]`` to display an image from a URL.

```
[img]URL[/img] 
```

![pic](https://img.mamesosu.net/1 "pic")
