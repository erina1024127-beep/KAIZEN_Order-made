
<!DOCTYPE html><html lang="ja"><head><meta charset="UTF-8">
<style>
  body { font-family: 'Segoe UI', sans-serif; max-width: 800px; margin: 0 auto; padding: 24px 20px; color: #1a1a1a; line-height: 1.75; }
  h1,h2,h3,h4,h5,h6 { margin: 1.4em 0 0.5em; font-weight: 700; line-height: 1.3; }
  h1 { font-size: 1.8em; border-bottom: 2px solid #eee; padding-bottom: 0.3em; }
  h2 { font-size: 1.4em; border-bottom: 1px solid #eee; padding-bottom: 0.2em; }
  h3 { font-size: 1.15em; }
  p { margin: 0.8em 0; }
  a { color: #0969da; }
  ul, ol { margin: 0.8em 0; padding-left: 1.8em; }
  li { margin: 0.3em 0; }
  code { background: #f0f0f0; padding: 2px 5px; border-radius: 3px; font-family: Consolas, monospace; font-size: 0.88em; }
  pre { background: #f6f6f6; border: 1px solid #e0e0e0; border-radius: 6px; padding: 14px; overflow-x: auto; margin: 1em 0; }
  pre code { background: none; padding: 0; font-size: 0.9em; }
  blockquote { border-left: 4px solid #d0d0d0; margin: 1em 0; padding: 4px 16px; color: #555; }
  table { border-collapse: collapse; width: 100%; margin: 1em 0; }
  th, td { border: 1px solid #ddd; padding: 8px 12px; text-align: left; }
  th { background: #f5f5f5; font-weight: 600; }
  tr:nth-child(even) td { background: #fafafa; }
  hr { border: none; border-top: 1px solid #e0e0e0; margin: 1.5em 0; }
  img { max-width: 100%; height: auto; }
</style></head><body><h1>特注改造 出図業務改善</h1>
<p>特注改造対応における出図業務改善に関する概要・試験運用の記録を残すリポジトリです</p>
<h2>概要</h2>
<p>原紙1枚の設計変更で全案件の出図ファイルを手修正している現状を改善する。<br>原紙データ（.xdw）を図番単位で一元管理し、構成リストに基づく動的結合で常に最新の出図ファイルを生成する。</p>
<h2>実施ステップ</h2>
<table>
<thead>
<tr>
<th>ステップ</th>
<th>内容</th>
</tr>
</thead>
<tbody><tr>
<td>Step 1</td>
<td>原紙データの自動リネーム（スキャン後の .xdw → 図番名）</td>
</tr>
<tr>
<td>Step 2</td>
<td>構成リストに基づく出図ファイルの自動生成</td>
</tr>
</tbody></table>
<h2>リポジトリ内容</h2>
<ul>
<li><code>docs/</code> — 仕様書（図解付き）</li>
<li><code>tests/logs/</code> — 試験運用の記録</li>
</ul>
<hr>
<h2>メンバー</h2>
<ul>
<li>岡部 </li>
<li>磯貝</li>
</ul>
</body></html>
