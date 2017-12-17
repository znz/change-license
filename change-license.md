# ライセンス変更の話

author
:   Kazuhiro NISHIYAMA

content-source
:   LILO 20周年記念ミートアップ

date
:   2017/12/17

allotted-time
:   5m

theme
:   lightning-simple

# self.introduce

- One of Ruby committers
- Twitter, GitHub: `@znz`

# ライセンス変更とは?

- 独自ライセンスから一般的な OSS ライセンスへの変更
- OSS ライセンスから別のライセンスへの変更
- など

# 今回の話

自分が関わったことのある OSS 関連のライセンス変更

# るりま

- Ruby のリファレンスマニュアル
- https://github.com/rurema/doctree/blob/master/refm/doc/license.rd
- 今は Creative Commons — Attribution 3.0 Unported
- 以前はとりあえず的なもの + Rubyist ML (現在は閉鎖) で合意で変更可能
  - 問題を先送りしていた
  - そのおかげで CC にできた

# Ruby 本体

- https://github.com/ruby/ruby/blob/trunk/COPYING.ja
  - 完全独自ライセンスから独自 + 2-clause BSDL
  - (他のライセンスのものも含まれるので詳細は LEGAL ファイル参照)
- ライセンス変更の根拠
  - 2\. (d) その他の変更条件を作者と合意する．
  - 4\. 他のプログラムへの引用はいかなる目的であれ自由です．
  - このあたりが根拠だったはず (ちゃんと確認したわけではない)

# tdiary (プラグイン含む)

- fix #445: license notation exactly
  - https://github.com/tdiary/tdiary-core/commit/92261bd017c803a9c0a1968a732af619e4ce6c09
  - GPL 2 から GPL 2+ に変更
- https://github.com/tdiary/tdiary-core/blob/b1c455ea2a9d856d5f97b38b3a605b979242c15b/misc/plugin/highlight.rb
  - You can redistribute it and/or modify it under GPL2 or any later version.

# まとめ

- るりま (Ruby のリファレンスマニュアル)
- Ruby 本体
- tdiary
