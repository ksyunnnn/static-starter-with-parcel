# はじめかた

```
yarn
yarn start
```

# 説明

`yarn start`で`pug src/pug/index.pug -o tmp/ --watch & parcel tmp/index.html`を実行しています。

`pug src/pug/index.pug -o tmp/ --watch`により

```
- src
  - pug
    - index.pug

↓ ファイル保存すると生成

- tmp
  - index.html

```

`parcel tmp/index.html`により

```
- src
  - index.js # tmp/index.htmlで読み込んでおく
  - scss
    - style.css

↓ 生成

- dist
  - index.html
  - cssとかjs
```

# 参考

https://qiita.com/ezawa800/items/91142d8d2c006414529f
