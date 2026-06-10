# Email Thread Management アニメデモ — WEST FUSION AI

マネージャーの時間を取り戻す AI — メール・Teams 確認の30分を3分に。

47秒・13シーン構成のアニメーションデモ。Outlook/Teams から流入する情報を、4体の AI Agent が個人週報→チーム週報→部長サマリー→ボール俯瞰表へ自動整理する流れを視覚化しています。

- 公開URL: https://westfusionai.github.io/email-thread-demo/
- インタラクティブ: タイムバークリックでシーン移動 / 一時停止 / 最初から再生
- 動作環境: Outlook、Teams、Power Automate、Python、SharePoint
- 運用サイクル: 毎週金曜の退勤前にワンクリックで週次バッチを実行し、AI レポート 4 種を生成(週 1 回運用)

## なぜ中間管理職に最適か

情報が最も集まるのは中間管理職。一般職は自分の業務範囲のみで集約情報が薄く、部長以上はサマリーのみ届くため AI 整理する素材が少ない。CC・グループチャット経由で全情報が集まる課長レベルこそ、AI 整理の効果が最大化されます。

## 自動化の前提条件

社内 AI(Claude API・Azure OpenAI など)が業務 PC からプログラム呼び出し可能なら完全自動。そうでない環境では AI に渡す部分のみ手動でも、収集・振り分け・整形・配信は自動化されるため 30分→5〜10分の効果があります。

---

Created by Hideki West — West Fusion AI / Contact: west.fusion.ai@gmail.com
