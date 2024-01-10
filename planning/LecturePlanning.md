# 計画

## 第1回講義

### フロントエンドという職域

- フロントエンド
- バックエンド
- インフラ
- その他
  - UI/UXデザイナー
  - データアナリストなど

### Webとブラウザ

- Webの歴史
  - 参考動画: <https://youtu.be/jBksc8SdUF8?t=1242>
- ブラウザについて

### エディター

- VSCodeの紹介

### 第1回講義の課題

- VSCodeをインストールしよう

## 第2回講義

### HTMLとは

### HTMLドキュメントの構造

### タグ

- ブロック要素のタグの紹介
- インライン要素のタグの紹介
- form/inputについて

### セマンティックなHTML

- SEO的効果や保守性が上がる

### 第2回講義の課題

- HTMLで自己紹介ページを作ってみよう

## 第3回講義

### CSSとは

### CSSの基本構文（セレクタ、プロパティ、値）

### スタイリング

- color/font-size/background
- ボックスモデル（margin/paddingなど）
- レイアウト（flex/gridなど）

### レスポンシブ

- メディアクエリについて

### アニメーション

### CSSライブラリの紹介

- Bootstrapなど流行ってるCSSライブラリ

### 第3回講義の課題

- 第2回講義の課題で作成したHTMLをCSSで装飾しよう
- その際レスポンシブデザインになるようにしましょう

## 第4回講義

## JavaScriptとは

- JavaScriptとは何ができるのか
- ECMAScriptについて
- コードの書き方
  - scriptタグ
  - JavaScriptファイルのウェブページへの組み込み方

### console

- console.logについて

### データ型、変数、演算子

- 基本データ型：数値(Number)、文字列(String)、ブール値(Boolean)、null、undefined
- 複合データ型：オブジェクト(Object)、配列(Array)
- 変数の宣言：var, let, constの違い
- 演算子：算術演算子、比較演算子、論理演算子、代入演算子
- 型変換：暗黙の型変換と明示的な型変換（キャスティング）

### 制御構文

- 条件分岐：if文、else文、switch文
- 繰り返し処理：forループ、whileループ、do...whileループ
- breakとcontinue文の使い方
- 条件（三項）演算子の使い方

### 第4回講義の課題

- 各データ型で定義した変数をif文やfor文、制御構文を使ってconsole.logして確認してみよう

## 第5回講義

### 関数

- 関数の宣言と呼び出し
  - return文と関数の戻り値
- 無名関数とアロー関数（ES6以降）
- スコープの概念：グローバルスコープとローカルスコープ
- クロージャの基本的な理解

### 第5回講義の課題

- 関数を定義してconsole.logしてみよう

## 第6回講義

### DOM操作

- DOMとは？
- 要素の取得（`getElementById` / `getElementsByClassName` / `querySelector`）
- 要素の操作（`textContent` / `innerHTML` / `setAttribute`）
- 要素の作成と追加（`createElement` / `appendChild` / `insertBefore`）

### イベント

- イベントとは？
- addEventListener

### 第6回講義の課題

- DOM操作をしてみよう
  - イベントを使ってbuttonタグをクリックしたときに、要素を削除したり追加したりなどの処理を実装してみよう

## 第7回講義

## 実演

- 簡単なTODOアプリを作ってみる
  - HTMLでマークアップをする
  - CSSで装飾をする
  - JavaScriptでTODOを追加する

## 課題

- TODOアプリを作ってみましょう
  - HTMLとCSSでUIを作ってください
  - JavaScriptでTODOの追加・削除をできるようにしてください
  - TODOには「タスク名」「担当」「期限」を設けてください

## 第8回講義

### 高階関数

- `map()`, `filter()`, `reduce()`

### 第8回講義の課題

- `map()`, `filter()`, `reduce()` を使ってTODOを修正してみよう

## 第9回講義

### デストラクチャリング

### スプレッド構文

### テンプレートリテラル

### 第9回講義の課題

- デストラクチャリング、スプレッド構文、テンプレートリテラルを使ってTODOを修正してみよう

## 第10回講義

### 非同期

- `fetch`
- `Promise`
- `async/await`

### 第10回講義の課題

- PokeAPIでfetchをしてみよう

## 第11回講義

### モジュール

### 第11回講義の課題

- PokeAPIからデータ取得する関数をexportして、別のjsファイルにimportして利用できるようにしてみよう

## 第12回講義

### Node.jsとは

### npmとは

- パッケージ管理について
- ライブラリのインストール
- package.jsonの説明

### 第12回講義の課題

- Node.jsをインストールしてnpm initしてみよう

## 第13回講義

### PrettierとESLint

- Prettierとは/ESLintとは
- Prettier/ESLintの設定

### 第13回講義の課題

- Prettier/ESLintの設定をしてみよう

## 第14回講義

### webpack

- webpackとは
- webpackの設定

### 第14回講義の課題

- webpackの設定をしてみよう

## 第15回講義

### Babel

- Babelとは
- Babelの設定

### 第15回講義の課題

- Babelを設定してみよう

## 第16回講義

### TypeScriptとは

### 環境設定

- tsconfig.json
- tslint.json

### 基本的な型

- `number`, `string`, `boolean`, `array`, `object`, `tuple`, `enum`, `any`, `void`, `null`, `undefined`

### 第16回講義の課題

- TypeScriptを設定した上で、npm buildしてconsole.logができるようにしてみよう

## 第17回講義

### TypeScriptの関数

- 関数宣言と呼び出し
- ジェネリクス

### 第17回講義の課題

- TypeScriptで関数を実装してみよう

## 第18回講義

### 高度な型

- optional
- ユニオン型
- インターセクション型
- リテラル型

### 型の推論

### 第18回講義の課題

- 今日習った型を使って実装してみよう

## 第19回講義

### Reactとは

### Reactの環境設定

### JSX

- JSXとは
- JSXの書き方
- JSXのスタイリング（CSS-in-JS）
  - CSS Modules
  - CSS-in-JS
    - Styled Components
    - Emotion

### 第19回講義の課題

- Reactの環境構築をして、JSXでHalloWorldを表示してみよう

## 第20回講義

### コンポーネント

- コンポーネントとは
- コンポーンとの作成と使い方
  - props

### 第20回講義の課題

- コンポーネントを実装してみよう

## 第21回講義

### ステート管理

- ステートとは
- useStateフックの使用例
- クリックイベントによるステートの変更例
- コンポーネント間のステートの共有
  - propsによるステート値の共有する例
  - propsでイベントハンドラメソッドを渡す例

### 第21回講義の課題

- useStateを使って実装してみよう

## 第22回講義

### カスタムフック

- カスタムフックとは
- カスタムフックの実装例

### 第22回講義の課題

- カスタムフックを実装してみよう

## 第23回講義

### コンテキスト

- コンテキストとは
- カスタムフックとの併用例

### 第23回講義の課題

- コンテキストを実装してみよう

## 第24回講義

### ライフサイクルメソッド

- ライフサイクルとは？
- useEffect

### 第24回講義の課題

- useEffectを使って実装してみよう

## 第25回講義

### コンポーネント指向

### 仮装DOM

### 第25回講義の課題

- TODO : 課題を考える

## 第26回講義

### パフォーマンスチューニング

- React.memo
- useMemo
- useCallback

### 第26回講義の課題

- useMemo、useCallbackを使って実装してみよう


## 第27回講義

### ルーティング

- ルーティングとは
- ReactRouterとその使用方法（`BrowserRouter`, `Routes`, `Route`, `Link`）
- useNavigateフックの紹介

### 第27回講義の課題

- ルーティングを使ってページ遷移をする画面を作ってみよう

## 第28回講義

### 状態管理ライブラリ

- 状態管理ライブラリとは
  - Recoil
  - Jotai

### 第28回講義の課題

- 状態管理ライブラリを使って実装してみよう

## 第29回講義

### REST APIのドキュメントとモック

- REST API定義
  - OpenAPIのYAMLによるAPI定義
- APIドキュメント
  - SwaggerU
- APIモック
  - MSW

### 第29回講義の課題

- APIドキュメントを作成してみよう
- APIモックを使えるようにしてみよう

## 第30回講義

### テスト

- フロントエンドにおけるテストとは
  - Jest
- 単体テスト
  - ReactTestingLibrary
  - テストコードを書いてみる
- DOM SnapShot Test
  - DOM SnapShot Testとは
  - テストコードを書いてみる

### 第30回講義の課題

- テストを書いてみよう

## 第31回講義

### ディレクトリ構成

- co-location pattern

### 第31回講義の課題

- ReactRouterを用いて複数ページのTODOアプリを作ろう
  - TODO一覧
  - 担当者一覧
  - etc...
  - バックエンドのAPIとしてはJsonServerってやつでダミーのAPI作るの良さそう or モックでも良い
<https://www.to-r.net/media/json-server/>

- TODOアプリに対してテストコードを書いてみよう

## 第32回講義

### 現場でのReact周辺の技術紹介

- Storybook
- GraphQL
- データフェッチライブラリ
  - TanStack Query、SWRの紹介

### 第32回講義の課題

- 特になし。引き続きTODOアプリを作ろう

## 第33回講義

- Next.js
  - SSR
    - SPAの苦手な初期描画を克服
    - SEO対策
  - pagesディレクトリの動的ルーティング
  - SSG/ISRの紹介
  - AppRouterの紹介（新しく出たよ！程度の紹介）

### 第33回講義の課題

- 特になし。引き続きTODOアプリを作ろう
