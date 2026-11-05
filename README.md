# labor-calendar

働き方の条件を選ぶと、所得税・住民税・労働保険・社会保険のお金と書類の流れを12か月のシーケンス図で示すページです。

`public/index.html` をブラウザで開くと動きます。ビルドは要りません。Cloudflare Workers の静的配信で公開します (`npx wrangler deploy`)。

URL の `#` で節 (`tax` / `soc` / `lab`)・今年か翌年か (`current` / `next`)・月の行を指せます。例: `?work=contractor&src=2#tax-next-01`。

金額は概算です。計算の前提と出典はページ下部の「計算の前提と出典」にあります。実際の手続きは税理士、社労士、窓口で確認してください。
