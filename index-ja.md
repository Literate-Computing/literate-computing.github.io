---
title: <span class="text-info">L</span>iterate <span class="text-info">C</span>omputing <span class="text-info">for R</span>eproducible <span class="text-info">I</span>nfrastructure
description: <small><small><b><span class="text-danger">Jupyter</span> based Toolset for an Infrastructure Engineer - <span class="text-danger">文芸的機械化</span>のススメ</b></small></small>
link_en: index.html
layout: home
---

## <span class="text-info">LC4RI</span>とは？
<small>
Literate Computing for Reproducible Infrastructure（以下 「LC4RI」）は、インフラ運用の場面において **機械的に再現できる、人が読み解ける手順** を手段として、過度に自動化に依存することのない、レジリエントな **人間中心の機械化** をめざしています。そこでは、作業を効率化しつつもブラックボックス化せず、作業に対する理解をチーム内でコミュニケーションできる、また、目的と手段の整合性や限界を理解し議論・評価できると言った場を維持することで、**ノウハウの移転・共有を促し運用者のスキル向上とエンジニアリングチームの再生産**をはかることを重視しています。

<small>
多くの現場では、管理サーバにログインしコンソール上で作業を行う、作業内容や証跡はWiki等に随時転記して共有する.. といった形態が一般的と思います。これに対しLC4RIでは運用管理サーバ上にNotebookサーバを配備し、作業単位毎にNotebookを作成、作業内容やメモを記述しながら随時実行するといった作業形態を推奨しています。作業の証跡を齟齬なく記録する仕組み、過去の作業記録を参照して機械的に再現あるいは流用できる仕組み、機械的に実行できるとともに人が読み解き補完することもできるNotebook手順を整備しています。
</small>

---
### NII Open House 用のデモを試す
<small>
このデモ環境ではJupyterのインタフェースを使って、運用作業の一例としてのログ分析や、我々のチームがLC4RIの実践のために開発している各種Extensionを使ってみるといった体験ができます。

<big><span style='background-color:lightyellow;'>
[openhouse-demo](https://mybinder.org/v2/gh/NII-cloud-operation/Jupyter-LC_docker/openhouse-2021-demo)
</span>

<small>
なお、この環境ではNotebookを自由に作成、編集することができますが、Notebookに対する変更等は、 **保存されません** 。この環境は[Binder](https://mybinder.readthedocs.io/en/latest/)サービスの上でデプロイされており、一定時間が経過すると自動的に削除されます。編集したNotebookなどの情報は失われますのでご注意ください。

<small>
また、Sidestickies という Notebookに対して付箋を付与する機能では [Scrapbox](https://scrapbox.io/product/)サービスを利用しています。デモ環境の Sidestickies 付箋ページ は参照のみで、編集できません。



> <span style='background-color:mistyrose;'> **デモ環境を体験するに際して、 [Binder](https://mybinder.readthedocs.io/en/latest/) および [Scrapbox](https://scrapbox.io/product/) の利用規約は各自で確認ください。** </span>

> <span style='background-color:mistyrose;' > 質問等、お問い合わせは、Facebookページ https://www.facebook.com/groups/LiterateComputing/ に参加申請ください！</span>

#### Notebookの実行方法

<small>
このデモ環境では、Notebookという形式で、実際に自身で実行可能な運用作業の例が保存されています。

<small>
* [00_デモ環境の利用方法](00_デモ環境の利用方法.ipynb)を参考に、実際に実行をしてみてください。


##### Literate Computingの運用への適用例

<small>
運用への適用例の一つとして、ログを分析する手順を記述したNotebookを体感いただけます。

* [01_Literate_Computingの運用への適用例](01_Literate_Computingの運用への適用例.ipynb)


##### NII謹製Literate Computing機能拡張
Jupyterはもともとデータ分析用途に開発されたツールであるため、インフラの運用に適用するためにいくつかの機能拡張を施しています。以下は、その内容をご紹介するNotebookです。

* [02_NII謹製_Jupyterの機能拡張について](02_NII謹製_Jupyterの機能拡張について.ipynb)


##### Notebookを介したコミュニケーションについて

Jupyterで行った経験を効率的に共有するためにいくつかの機能拡張を施しています。以下は、その内容をご紹介するNotebookです。

* [03_Notebookを介したコミュニケーション](03_Notebookを介したコミュニケーション.ipynb)




## Jupyter拡張

- [Python2/Python3 kernel with LC_wrapper](https://github.com/NII-cloud-operation/Jupyter-LC_wrapper)
- [multi_outputs](https://github.com/NII-cloud-operation/Jupyter-multi_outputs)
- [run_through](https://github.com/NII-cloud-operation/Jupyter-LC_run_through)
- [nblineage](https://github.com/NII-cloud-operation/Jupyter-LC_nblineage)
- [i18n_cells](https://github.com/NII-cloud-operation/Jupyter-i18n_cells)

