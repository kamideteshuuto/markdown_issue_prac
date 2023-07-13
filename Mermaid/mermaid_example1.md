#### VSCodeでmermaidを利用する方法
1. VScodeの拡張機能をインストール
- VSCodeを開き、拡張機能パネルを表示します。
- 検索バーに調べたい拡張の木の王を入力。
- 拡張機能が表示されたら、「Install」ボタンをクリックしてインストールします。
2. Mermaidコードを含むMarkdownファイルを作成または開く

- Mermaidコードを含む新しいMarkdownファイルを作成するか、既存のMarkdownファイルを開きます。
3. Mermaidコードを挿入
- Mermaidコードを挿入します。例えば、以下のようなコードを挿入します
```code
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
4. プレビューの表示
- プレビューを表示するために、Ctrl+Shift+Vを押すか、Viewメニュー→Markdown Previewを選択
します。すると、プレビューパネルが開きレンダリングされたグラフや図が表示されます。
5. Mermaidコードのプレビューの更新
- コードを変更した場合、プレビューを更新するには、再読み込みアイコンをクリックするか、
- Ctrl+Shift+Vを押します。

######これで、VSCodeでMermaidを利用してグラフや図を作成し、プレビューすることができます。
詳しくはこちら→[詳細](https://dev.classmethod.jp/articles/github-copilot-introduction/)

---
#### Marmaid 便利な拡張機能
1. **Markdown Preview Mermaid Support**
   この拡張機能は公式のMermaidプレビューサポートです。
   Markdownファイル内のMermaidコードをプレビューで表示します。これにより、Mermaidコードを即座にグラフや図として確認できます。
2. **Mermaid Preview**
この拡張機能はMermaidコードを直接プレビューするためのものです。
プレビューウィンドウ内でMermaidコードをリアルタイムに表示し、グラフや図として確認できます。
3. **Mermaid Diagrams**
この拡張機能はMermaidコードを作成するための便利な機能を提供します。
Mermaidコードの作成をスムーズにします。
4. **Mermaid Markdown Syntax Highlighting**
この拡張機能は、Mermaidコードを含むMarkdownファイルのシンタックスハイライトを強化します。
Mermaidコードの部分が視覚的に強調表示されるため、コードの読みやすさが向上します。
[便利な拡張機能](https://qiita.com/sato_kana/items/2a13f19017576488f017)
---