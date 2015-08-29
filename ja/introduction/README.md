# Introduction

この書籍はJavaScriptのライブラリやツールにおけるプラグインのパターンについて見ていく事を目的としたものです。

JavaScriptの世界では一つの大きなライブラリよりも小さいなものを組み合わせていくようなスタイルが多く見られます。

小さものを組み合わせて使えるようなエコシステムの土台となるものを書こうとした際に、プラグイン機構の仕組みが重要となると言えます。

> ソフトウェアの構造に「プラグイン機構」を設け、ユーザコミュニティから開発者コミュニティへの質的な転換を図るのは、ソフトウェア設計からエコシステム設計へとつながる
> -- [OSS開発の活発さの維持と良いソフトウェア設計の間には緊張関係があるのだろうか? - t-wadaのブログ](http://t-wada.hatenablog.jp/entry/active-oss-development-vs-simplicity "OSS開発の活発さの維持と良いソフトウェア設計の間には緊張関係があるのだろうか? - t-wadaのブログ")

この書籍では、そのプラグイン機構の仕組みそのものを、既にエコシステムを形成してるライブラリやツールなどの実装から学ぶことを目的にしています。