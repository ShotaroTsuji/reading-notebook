+++
url = "https://dev.to/mage_ai/how-to-write-technical-design-docs-c02"
+++
# 読書メモ: How to write technical design docs

- tech docを書くことでエッジケースや直面する問題について考えることを強制する
  - 実際にコードを書くときに重い思考は終わっているので仕事が速くなる
- 小さな機能に対するdesign docは本質的には疑似コードである
- 非常に小さな機能や明白な解法に対してはdesign docは必要ではない

## Mageのtech design docのテンプレート

ドキュメントの冒頭に、以下のものを書く。

- 著者の名前
- 作成日
- 更新日

エピックへのリンクもあるとよい。

- Purpose（目的）
- Background（背景）
- Requirements（要求）
  - サービスや機能が達成する成果
  - レスポンスタイム等の制約
- Detailed design（詳細設計）
  - 疑似コード
  - データベーススキーマ
  - フローダイアグラム
  - ワイヤフレーム
  - コンポーネント
  - 入力の検証
  - セキュリティの考慮
  - APIエンドポイント
  - APIのリクエスト・レスポンスの具体例
  - etc.
- Implementation Plan（実装計画）
- Tests（テスト）
- Runbook（運用手順）

## ShotaroTsujiの感想

テックリードという職責について調べていて、以下のページでTechnical Design Documentについて触れられていたので、それがどのようなものか知るためにググって出てきたブログポストを読んだ。

https://gihyo.jp/dev/serial/01/continue-power/0011

今回読んだのはMage AIという会社のブログポストであるが、tech design docの概略が簡潔にまとまっていてよい。
とはいえ、ある程度経験がないと何を書くべきなのかは想像がつかなさそう。
