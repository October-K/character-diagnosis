GitHub Pages 導入用：あなたと相性のいいキャラ診断

【フォルダ構成】
リポジトリ直下に、この character-diagnosis フォルダごと追加してください。

例：
your-repository/
├─ index.html
├─ character/
├─ story/
├─ extra/
└─ character-diagnosis/
   └─ index.html

【診断ページのURL】
GitHub Pages のサイトURLが
https://USERNAME.github.io/REPOSITORY/
なら、

https://USERNAME.github.io/REPOSITORY/character-diagnosis/

で開けます。

【既存サイトからリンクする】
既存のHTMLに、たとえば次を追加してください。

<a href="./character-diagnosis/">あなたと相性のいいキャラ診断</a>

※ リンク元のHTMLがリポジトリ直下にある場合です。

もし EXTRA/index.html など、1階層下のページからリンクする場合は：

<a href="../character-diagnosis/">あなたと相性のいいキャラ診断</a>

【GitHubへの追加手順】
1. GitHubで対象リポジトリを開く
2. Add file → Upload files
3. character-diagnosis フォルダ内の index.html をアップロード
   （GitHub Web UIではフォルダを直接ドラッグすると、その構造を保って追加できます）
4. Commit changes
5. GitHub Pagesの反映後、/character-diagnosis/ にアクセス

【この版について】
・HTML/CSS/JavaScriptすべて index.html 内に入っています。
・画像ファイルや外部ライブラリは不要です。
・「もう一度診断する」「結果をコピー」に対応しています。
・結果に「あなたと相性のいいキャラ」と「貴方と似ているキャラ」を表示します。
・今後キャラ画像を追加したくなった場合でも、assets/ フォルダを追加して拡張できます。

【更新するとき】
診断の質問・配点・説明文を変更した場合は、
character-diagnosis/index.html を置き換えてCommitしてください。
