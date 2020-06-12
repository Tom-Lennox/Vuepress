# 2_VuePress 所見

## VuePressのよいところ
- 速・楽・簡潔。

## VuePressの使い所
### こんなときは VuePress
- 客に見せる
- ブランドを表現したい
- 複数Sectionに分けたい
- コラム・宣伝を追加したい
- LTで使用、手順を数段分けたい
- Nuxt使うまでも行かない
- SEO問わない

### こんなときは Github
- 1ページのみ記載
- とにかく速く作成したい

### その他
- 変更が反映されない場合 ⇒ `yarn start`すると大体反映される。
- 低学習コスト。１度作ったら２度目の作成は速成。
- 数式使うのだったらおとなしくGithub使った方が良い。

## つまづきpoint

**（主にNetlifyの設定）**

### 8:11:31 AM: sh: 1: vuepress: not found

 ⇒ `package.json`にvuepressの記載が無かった。

 ⇒ **ErrorMsgをよく読め。公式を読め。**

 ```
 `package.json`
 # ▼ vuepressの記載が無かった。

 {
  "scripts": {
      "dev": "vuepress dev docs",
      "build": "vuepress build docs"
  },
  "devDependencies": {
      "vuepress": "^1.0.0-alpha.46"
  }
}
 ```

参考になったサイト様

[VuePress+Netlifyで『command not found』になるときの対応【540日目】](https://www.nyamucoro.com/entry/2019/04/07/024922)

### 8:25:00 AM: Failed during stage 'building site': Deploy directory 'dist' does not exist

 ⇒ （Netlify）`Publish directory`の指定が違う。

*x dist*

**o ./docs/.vuepress/dist**
