[[講習会のページに戻る>AJACS20]]

~目次
#contents


# 遺伝子発現データの活用法／次世代シーケンサの活用法 [#j098a048]
## 遺伝子発現 [#qc1585f1]
- テクノロジー
    -オリゴアレイ（カスタムアレイ）
    -cDNAアレイ
    -次世代シーケンサ

- DB
    -[[GEO (Gene Expression Omnibus)>http://www.ncbi.nlm.nih.gov/geo/]]
        -[[統合TV1>http://togotv.dbcls.jp/20081218.html]]、[[統合TV2>http://togotv.dbcls.jp/20090213.html]]、[[統合TV3>http://togotv.dbcls.jp/20090221.html]]、[[統合TV4>http://togotv.dbcls.jp/20090307.html]]
    -[[ArrayExpress>http://www.ebi.ac.uk/microarray-as/ae/]]
        -[[統合TV1>http://togotv.dbcls.jp/20090408.html]]、[[統合TV2>http://togotv.dbcls.jp/20090417.html]]、[[統合TV3>http://togotv.dbcls.jp/20100513.html]]
    -DOR (DDBJ Omics aRchive)
<br><br>
    -[[BodyMap>http://bodymap.jp/]]
        -[[統合TV1>http://togotv.dbcls.jp/20090204.html]]、[[統合TV2>http://togotv.dbcls.jp/20090210.html]]、[[統合TV3>http://togotv.dbcls.jp/20090328.html]]
    -[[BioGPS>http://biogps.gnf.org/]]
        -[[統合TV>http://togotv.dbcls.jp/20081004.html]]
    -[[Human Protein Atlas>http://www.proteinatlas.org/]]
        -[[統合TV>http://togotv.dbcls.jp/20090501.html]]
<br><br>
    -[[DNA総覧>http://lifesciencedb.jp/ddbj/]]
        -[[統合TV>http://togotv.dbcls.jp/20091022.html]]
    -[[GEO目次>http://lifesciencedb.jp/geo/]]
        -[[統合TV>http://togotv.dbcls.jp/20100326.html]]


- Tools
    -Excel
    -[[R>http://www.r-project.org/]]/[[Bioconductor>http://www.bioconductor.org/]]
        -東京大学門田先生による詳細な[[利用法解説>http://www.iu.a.u-tokyo.ac.jp/~kadota/r.html]]
        -[[統合TV1>http://togotv.dbcls.jp/20090313.html]]、[[統合TV2>http://togotv.dbcls.jp/20090319.html]]、[[統合TV3>http://togotv.dbcls.jp/20090618.html]]、[[統合TV4>http://togotv.dbcls.jp/20091219.html]]
    -[[RefEx>http://togoexp.dbcls.jp/RefEx/human/]]
        -[[統合TV>http://togotv.dbcls.jp/20100618.html]]
    -[[DAVID>http://david.abcc.ncifcrf.gov/]]
        -[[統合TV>http://togotv.dbcls.jp/20090925.html]]
    -[[CateGOrizer>http://www.animalgenome.org/bioinfo/tools/countgo/]]
        -[[統合TV>http://togotv.dbcls.jp/20090806.html]]
    -[[BioMart>http://www.biomart.org/]]
        -[[統合TV1>http://togotv.dbcls.jp/20080523.html]]、[[統合TV2>http://togotv.dbcls.jp/20090225.html]]、[[統合TV3>http://togotv.dbcls.jp/20090327.html]]
    -[[GenoDive>http://genodive.org/]]



## 次世代シーケンサ [#t2905d2f]
- テクノロジー
    -第0世代：スラブ
    -第1世代：キャピラリー
    -第2世代：pyrosequence (454), sequence by synthesis (Illumina, Helicos), sequence by ligation (Solid)
        -レビュー：Nature Review Genetics, 11, 31-46 (2010)
    -第3世代：SMRT (PacBio), Q-dot FRET (Life Technology), nanopore (Oxford), Ion Torrent sequencing, DNA Transistor technology (Roche & IBM), 電顕
        -レビュー：Nature Biotechnology, 28 (5), 426-428 (2010)
        -IBMの[[プレスリリース>http://www-03.ibm.com/press/us/en/pressrelease/32037.wss]]
        -[[英語のニュース>http://www.fastcompany.com/1665802/dna-nanopore-identification-gene-sequencing-medicine-roche-ibm]]

- ゲノム解読にかかったコスト
    -2003年、ヒトゲノムプロジェクト、30億ドル、13年
    -2007年、ベンターゲノム、7000万ドル、Sanger法
    -2007年、ワトソンゲノム、100万ドル、454
    -2009年、コンプリートゲノミクス、4000ドル
    -2010年、グレン・クローズ、5万ドル、Illumina（6月から2万ドルに値下げ）

- DB
- 生データ
    -[[SRA>http://www.ncbi.nlm.nih.gov/sra]]
    -[[ENA>http://www.ebi.ac.uk/ena/]]
    -[[DRA>http://trace.ddbj.nig.ac.jp/dra/index.shtml]]

- アノテーション済みコンティグ配列
    -[[GenBank>http://www.ncbi.nlm.nih.gov/genbank/]]
    -[[EMBL>http://www.ebi.ac.uk/embl/]]
    -[[DDBJ>http://www.ddbj.nig.ac.jp/]]

- 発現データ
    -GEO
    -ArrayExpress
    -DDBJ Omics Archive (DOR)

- Journal
    -[[Standards in Genomic Sciences>http://www.standardsingenomics.org/]]
        -Figure 1     Phylogenetic tree
        -Figure 2     Picture
        -Table  1     Classification and general features
        -Table  2     Genome sequencing project information
        -Table  3     Genome statistics
        -Figure 3     Graphical circular map of the genome
        -Table  4     Number of genes associated with the general COG functional categories

- Tools
- Pipeline
    -[[DDBJ Read Annotation Pipeline>https://p.ddbj.nig.ac.jp/]]
        -[[統合TV>http://togotv.dbcls.jp/20100617.html]]
    -[[Buncher>http://togoexp.dbcls.jp/buncher/]]
    -[[MiGAP>http://migap.lifesciencedb.jp/]]
        -[[統合TV>http://togotv.dbcls.jp/20100624.html]]
    -R
        -東京大学門田先生による詳細な[[使用法解説次世代版>http://www.iu.a.u-tokyo.ac.jp/~kadota/r_seq.html]]

- Reference Genome Mapping
    -[[BLAT>http://genome.ucsc.edu/cgi-bin/hgBlat]]
    -[[Maq>http://maq.sourceforge.net/]]
    -[[bwa>http://maq.sourceforge.net/bwa-man.shtml]]
    -[[SSAHA2>http://www.sanger.ac.uk/Software/analysis/SSAHA2/]]
    -[[SOAP>http://soap.genomics.org.cn/]]
    -[[Bowtie (SAMtools)>http://bowtie-bio.sourceforge.net/index.shtml]]
    -[[TopHat>http://tophat.cbcb.umd.edu/index.html]]

- de novo Assembly
    -[[velvet>http://www.ebi.ac.uk/~zerbino/velvet/]]
    -[[edena>http://www.genomic.ch/edena.php]]
    -[[abyss>http://www.bcgsc.ca/platform/bioinfo/software/abyss]]

- まとめブログ
    -[[NGS Alignment Programs>http://lh3lh3.users.sourceforge.net/NGSalign.shtml]]
    -[[NGS解析で使われるソフトのまとめ>http://d.hatena.ne.jp/sesejun/]]（お茶の水女子大、瀬々潤先生）

# ここから実習 [#yd43c179]
## GEOから発現情報をとってきて、発現上昇した遺伝子の、上流域の配列を取得する [#n913ea56]
<br><br>
### の前に、後で使う（かもしれない）R/Bioconductorをインストールします [#of4939d3]
- 統合TV：[[統計解析ソフト「R」の使い方 ～導入編～（winxp）>http://togotv.dbcls.jp/20090313.html#p01]]
- 統合TV：[[統計解析ソフト「R」の使い方 ～導入編～（macosx）>http://togotv.dbcls.jp/20090618.html#p01]]
<br><br>

1. [[R>http://www.r-project.org/]] のサイトに行きます（「R」もしくは「R statistics」）<br>
2. download R のリンクをクリック<br>
3. ダウンロード元を聞かれるので、「Japan」の「Hyogo University」か「University of Tsukuba」のサイトをクリック（ミラー：http://dbcls.rois.ac.jp/~kawano/AJACS/）<br>
4. インストールするコンピュータのOSを選択（windows）<br>
5. 「base」をクリック<br>
6. 一番上にある「Download R 2.11.1 for Windows」をクリック<br>
7. ダウンロードが終わったらインストール<br>
　1. 言語は日本語でOKのはずですが、インストールの途中で文字化けした場合、一度インストールを中止し、言語をEnglishにしてやり直してください<br>
　2. 「Startup Option」のところで「Yes (customized startup)」を選んでください（コンポーネント選択の次の画面）<br>
　3. 最初の二つはそのままでOK<br>
　4. 「Internet Access」のところで、プロキシ接続が必要な場合（企業や学校からつなぐ場合に必要となることがあります）は「Internet2」を選択します<br>
　5. あとはそのままで全部OK<br>
8. R を起動します<br>
9. Bioconductor の一括インストール　＜注：講習会ではこれは実行しないでください＞<br>
　1.
 source("http://bioconductor.org/biocLite.R")
　と打ち込んでリターン<br>
　2.
 bioclite()
　と打ち込んでリターン<br>
　3. でインストールが始まりますが、かなり時間がかかるので今回は省略します<br>
10. Bioconductor パッケージの個別インストール<br>
　1. R 上部のメニューから「Packages」→「Select repositories」を選択します<br>
　2. 「BioC software」を選んで OK<br>
　3. R 上部のメニューから「Packages」→「Install package(s)」を選択します<br>
　4. 「affy」を選択して OK<br>
　5. R 上部のメニューから「Packages」→「Select repositories」を選択します<br>
　6. 「BioC annotation」を選んで OK<br>
　7. R 上部のメニューから「Packages」→「Install package(s)」を選択します<br>
　8. 「hgu133acdf」を選択して OK<br>
<br><br><br><br><br>

### [[GEO>http://www.ncbi.nlm.nih.gov/geo/]]のエントリについて [#lca52056]

     GEO ID 番号の最初の3文字が
     GPL:  プラットフォーム（マイクロアレイ等の型番）
     GSM: サンプル（1枚のマイクロアレイから出たデータ）
     GSE:  シリーズ（1つの実験で出たデータを集めたもの。通常複数の GSM からなる）
     GDS:  データセット（NCBIで比較可能なデータを集めて再編成したもの。GEO上で簡単な解析が可能）
<br><br>

### マイクロアレイのプラットフォーム情報について調べる（省略） [#g51a6b5d]
- [[統合TV：遺伝子発現情報データベース NCBI Gene Expression Omnibus (GEO) の使い方>http://togotv.dbcls.jp/20081218.html#p01]]<br><br>

1. GEO http://www.ncbi.nlm.nih.gov/geo/ のページに行きます（「GEO」もしくは「GEO gene」で検索）<br>
2. BROWSE にぶら下がっている「Platforms」をクリックします<br>
3. 一覧が表示されます。表の上にある「FIND PLATFOEM」をクリックします<br>
4. Title contains のところに「U133A」と入力して、「FIND PLATFORM」をクリックします<br>
5. Accession にあるID番号をクリックすると、各プラットフォームの詳細が見られます<br>
6. 詳細情報の中程にある「Samples」や「Series」の下にある「＋」をクリックすると、このマイクロアレイを使って出されたデータ、一連の実験シリーズが表示されます<br>
7. ページの下には、マイクロアレイに載っているプローブIDと対応する遺伝子配列へのリンク・アノテーション情報の一覧表（一部）があります。すべての情報を見たいときには「Download full table」をクリックすると、アレイに載っているすべてのプローブ情報をダウンロードできます
<br><br><br><br><br>

### 特定の遺伝子の発現量について調べる（省略） [#d1ee58ef]
- 統合TV：[[NCBI GEOの使い方２　遺伝子プロファイルを検索する>http://togotv.dbcls.jp/20090213.html#p01]]<br><br>
GEO トップページの Gene profiles に遺伝子シンボルを入力して検索できます<br>
<br><br><br><br><br>

### データセットブラウザを使って、GEOで簡単な解析を実行する [#y1c0035b]
- 統合TV：[[NCBI GEOの使い方3　データセットブラウザを使い倒す>http://togotv.dbcls.jp/20090221.html#p01]]
- 統合TV：[[NCBI GEOの使い方4　データセットブラウザをさらに使い倒す>http://togotv.dbcls.jp/20090307.html#p01]]<br><br>

1. GEOのトップページに行きます<br>
2. 「DataSets」に「dioxin」と入力<br>
3. 4番目にある「GDS2744」をクリック<br>
4. 実験に使われたマイクロアレイ（プラットフォーム）を確認しておきます（HG-U133Aです）<br>
5. 表のタイトル部分にある「Sample Subsets」をクリックすると、どのようなデータが含まれているかがわかります<br>
6. 「Data Analysis Tools」で解析画面に戻ります<br>
7. 「Find genes」に遺伝子シンボルを入力すると、その遺伝子の発現状況がわかります（例えば「ABO」とか）<br>
8. その下の「Find genes that are up/down for this conditions(s)」の「Go」をクリックすると、2条件で発現の異なる遺伝子のリストが表示されます<br>
9. 左メニューの一番下にある「Experiments design and value distribution」をクリックすると、各サンプルでの遺伝子発現の分布が表示されます（極端に分布が異なるサンプルがある場合は、解析から除いた方が良いでしょう）<br>
10. 「Compare 2 sets of samples」で、t検定など簡単な統計解析が可能です。<br>
　1. Step 1 で検定方法と閾値を設定します<br>
　2. Step 2 でサンプルをグループ分けします<br>
　3. Step 3 で計算開始<br>
　4. 設定した条件に適合した遺伝子がリストされます。（右側の図はそれぞれ縦軸のスケールが違うので注意）<br>
　5. 「Download profile data」からリストされた遺伝子のみのデータをダウンロードできます<br>
11. 「Cluster heatmaps」でクラスター解析と解析結果のヒートマップ表示を見ることができます<br>
12. 階層型クラスタリングの場合「hierarchical」から、クラスタリングの際の距離の計算方法とクラスターの代表点の取り方を指定します<br>
　1. 色を変えたり、クラスタリングパラメータを変えたりして「Change」を押すとクラスターが再描画されます<br>
　2. ダブルクリックすると、その周辺が拡大表示されます<br>
　3. 全体表示に戻すには、ヒートマップ図右上にある「Full image ~」の「Reset」をクリックします<br>
　4. 点線で範囲指定して「Get selected data」をクリックすると、指定部分の発現データをダウンロードできます<br>
13. 「Partitional (K-means/K-medians)」を選んで、クラスタリングパラメータを指定すると、指定した数のグループに遺伝子群を分割してくれます<br>
　1. 各クラスタをクリックすると拡大表示されます。<br>
　2. なぜか500遺伝子分しか表示されないので、ヒートマップ図右上にある「Full image ~」の「Reset」をクリックすると、全体表示になります<br>
　3. 点線で範囲指定して「Get selected data」をクリックすると、データをダウンロードできます<br>
14. 「By location on chromosome」をクリックすると、遺伝子がクロモソーム順にソートされたヒートマップが表示されます<br>
<br><br><br><br><br>

### GEOのデータをEXCELで解析してみる [#z013de2f]
- 参考図書：[[マイクロアレイデータ統計解析プロトコール>http://www.amazon.co.jp/%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%A2%E3%83%AC%E3%82%A4%E3%83%87%E3%83%BC%E3%82%BF%E7%B5%B1%E8%A8%88%E8%A7%A3%E6%9E%90%E3%83%97%E3%83%AD%E3%83%88%E3%82%B3%E3%83%BC%E3%83%AB%E2%80%95Excel%E3%82%92%E4%B8%AD%E5%BF%83%E3%81%A8%E3%81%97%E3%81%9F%E3%83%87%E3%83%BC%E3%82%BF%E3%81%AE%E6%A8%99%E6%BA%96%E5%8C%96%E3%81%8B%E3%82%89%E6%9C%89%E6%84%8F%E5%B7%AE%E8%A7%A3%E6%9E%90%E3%80%81%E3%82%AF%E3%83%A9%E3%82%B9%E3%82%BF%E3%83%AA%E3%83%B3%E3%82%B0%E3%80%81%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF%E8%A7%A3%E6%9E%90%E6%B3%95%E3%81%AE%E3%81%99%E3%81%B9%E3%81%A6-%E5%AE%9F%E9%A8%93%E5%8C%BB%E5%AD%A6%E5%88%A5%E5%86%8A-23-%E8%97%A4%E6%B8%95-%E8%88%AA/dp/4758101736/ref=sr_1_1?ie=UTF8&s=books&qid=1278382179&sr=8-1]]（羊土社）<br><br>

1. 先ほど使用した「GDS2744」のページから、バックグラウンド補正・正規化後のデータをダウンロードします。右側のクラスター図の下の「Download」にある「DataSet SOFT file」をクリックすればダウンロードできますが、みんなでアクセスすると迷惑なので、[[こちら>http://dbcls.rois.ac.jp/~kawano/AJACS/]]からダウンロードしましょう(GDS2744.soft、右クリックから「対象をファイルに保存」)。<br>
2. EXCELを起動して、「ファイルを開く」から「ファイルの種類」を「すべてのファイル」にします<br>
3. 先ほどダウンロードした「GDS2744.soft」ファイルを指定します<br>
4. このファイルは「タブ区切りファイル」なので、データ形式指定のところでタブ区切りを指定します<br>
　1. 「カンマやタブなどの区切り文字によってフィールドごとに区切られたデータ」を指定して「次へ」<br>
　2. 区切り文字に「タブ」を指定して次へ<br>
　3. 完了<br>
　4. 45行目から、データが6個のカラムに別れていることを確認する<br>
　5. 43行目までは不要なので削除してしまいましょう。22217行目から下も、コントロールデータ（ポジコン・ネガコン）なので削除してしまいましょう<br>
5. まず、2種類のサンプルの倍数変化（Fold Change）をみて、遺伝子発現の増減を検出します。<br>
　1. 2行目のJ列を選択して、「数式」から「関数」を選択して「すべて表示」から「AVERAGE」を選択し、C2セルからE2セルまでを範囲指定します<br>
　2. 同様にK列に、F2セルからH2セルまでの平均値を計算します<br>
　3. L列に倍数変化（K2/J2）を計算します。ただし、そのまま計算すると発現が増加の場合と減少で数値が非対称になってしまうので、底が2の対数をとります。関数の「LOG」を選択して、数値に「K2/J2」、底に「2」を入力します<br>
　4. J2~L2を選択して一番下まで移動し、「シフトボタン」を押しながらj22216~L22216を選択する<br>
　5. 「ホーム」→「フィル」→「下方向にコピー」で、全データに計算式を適用<br>
　6. 全データを選択し（シートの左上の角をクリックするか、Controlキー＋A）、「データ」→「並べ替え」を選択する<br>
　7. まず、「先頭行をデータの見出しとして使用する」にチェックを入れてから、最優先されるキーを「(列L)」にする。降順を指定して、OK<br>
　8. dioxinを添加したときに発現が増加する順に並び替えられました（4行目など上位に来ている多くはノイズの可能性が高いことに注意）。下から見ると、発現が減少した順に見ることができます<br>
6. 次に、t検定によるp値を求めます<br>
　1.  M2セルを選択し、「挿入」→「関数」から「TTEST」を選びます。<br>
　2. 配列1にC2～E2を、配列2にF2～H2を指定します。尾部には「2」を指定（両側検定）、検定の種類には「3」を指定します（等分散性を仮定しない）<br>
　3. 一番下まで移動して、M22216セルをシフトキーを押しながらクリックします<br>
　4. 「編集」→「フィル」→「下方向にコピー」<br>
7. FCが1以上（2倍以上発現量増加）かつp値が0.01以下のプローブを検索します<br>
　1. N2セルに「AND」関数を使って論理式1に「L2>1」、論理式2に「M2<0.01」を入れる。下までコピーしてN列をキーに降順に並べる（TRUEが条件を満たしたプローブ）<br>
　2. FCの値が1を越える行（707行目）より上を選択して、M列をキーに昇順にソート（10行目までが条件を満たしたプローブ）<br>
<br><br><br><br><br>


### BioMartで発現が上昇した遺伝子の上流配列を取得する [#da7f927f]
- 統合TV：[[遺伝子発現パターンが似ている遺伝子群のゲノム上流配列を一気に取得する>http://togotv.dbcls.jp/20070927.html#p01]]
- 統合TV：[[Biomartを使い倒す-IDの対応表を作成する>http://togotv.dbcls.jp/20080523.html#p01]]
- 統合TV：[[Biomartを使い倒す-マイクロアレイprobeIDの対応表を作る>http://togotv.dbcls.jp/20090225.html#p01]]
- 統合TV：[[Biomartを使い倒す～遺伝子の上流配列を取得する～2009>http://togotv.dbcls.jp/20090327.html#p01]]
- 統合TV：[[BioMartを使い倒す　比較ゲノミクス編>http://togotv.dbcls.jp/20100329.html#p01]]
<br><br>

1. 条件を満たした9プローブのプローブIDを選択し、コピーします<br>
2. BioMartのページに行きます（「BioMart」で検索）<br>
3. リストの最初にある「BioMart Central Portal」をクリックします<br>
4. データベースと生物種を選びます。「CHOOSE DATABASE」から「ENSEMBL GENES 58 (SANGER UK)」を、「CHOOSE DATASET」から「Homo sapiens genes (GRCh37)」を選択します（左上にある「Count」をクリックするとデータ数が確認できます）<br>
5. 左側にある「Filter」をクリックします（ここでさまざまなフィルタリングをかけることができます）<br>
　1. 今回は「Gene」の左にある「＋」をクリックして展開し、「ID list limit」にチェックを入れます<br>
　2. 「Ensembl gene ID(s) ...」になっているところを、「Affy hg u133a ID(s) ...」に変更します（一番下の方にあります）
　3. すぐ下の入力ボックスに、先ほどコピーしたプローブIDをペーストします<br>
　4. 左上にある「Count」をクリックして、遺伝子がいくつに絞られたか確認しましょう<br>
6. 左側にある「Attributes」をクリックします（ここで出力する項目を指定できます）<br>
　1. 初期状態では「Ensembl gene ID」と「Ensembl Transcript ID」が指定されています（左上の「Results」をクリックすると一覧表が得られます）<br>
　2. 今回は絞り込まれた遺伝子の上流配列が欲しいので、「Attributes」から「Sequences」を選択します<br>
　3. 「SEQUENCES」の左側の「＋」をクリックして展開します<br>
　4. 「Flank (Transcript)」を選択します<br>
　5. 「Upstream flank」にチェックを入れ、取得する塩基数を入力します<br>
　6. 「Header Information」を展開して、配列に併記する情報を指定できます。初期状態ではIDが表示されるだけで寂しいので、「Description」あたりにチェックを入れてみましょう<br>
　7. 左上の「Result」を押して結果を表示させます<br>
7. 結果をダウンロードします<br>
　1. 結果の上部にある「Export all results to」を「File」から「Compressed file (.gz)」に変更します（ネットワーク付加を減らすため）<br>
　2. 「Unique results only」にチェックを入れます<br>
　3. 「Go」でダウンロード開始です<br>
<br><br><br><br><br>


### GEOから生データを入手し、自分で（Rを使って）バックグラウンド補正・正規化する [#k1932fab]
- 統合TV：[[統計解析ソフト「R」の使い方 ～正規化編～>http://togotv.dbcls.jp/20090319.html#p01]]
<br><br>

1. 実験シリーズから生データをダウンロードします<br>
2. さきほどのGDS2744のページから、このデータセットの元になった実験シリーズ「GSE7765」のページに行きます<br>
3. 一番下からダウンロードできますが、ファイルサイズが大きいので http://dbcls.rois.ac.jp/~kawano/AJACS/ からダウンロードしましょう（GSE7765.zip）<br>
4. 解凍します<br>
5. Rでデータのあるフォルダを指定します。「File」→「Change dir」から先ほど解凍したフォルダを指定します<br>
6.
 library(affy)
と入力（コピペ）します。正規化用パッケージを呼び出しています<br>
7.
 write.exprs(justRMA(), file="RMA_expression.txt")
と入力（コピペ）します。RMAという方法で正規化し、ファイルに保存しています<br>
8.
 write.exprs(mas5(ReadAffy()), file="MAS5_expression.txt")
と入力（コピペ）します。MAS5という方法で正規化し、ファイルに保存しています<br>
9.
 write.exprs(mas5calls(ReadAffy()), file="MAS5calls_expression.txt")
と入力（コピペ）します。MAS5で正規化し、その遺伝子が発現しているか（Present = P）発現していないか（Absent = A）を判定して、ファイルに保存しています<br>
<br><br><br><br><br><br>

## ここから次世代の解析ツール [#m8763da5]

### [[DDBJ Read Annotation Pipeline>http://trace.ddbj.nig.ac.jp/dra/index.shtml]]の使い方 [#xc707653]
- 統合TV：[[今日からはじめるDDBJ Read Annotation Pipeline>http://togotv.dbcls.jp/20100617.html#p01]]
<br><br>

1. [[統合データベースプロジェクトページ>http://lifesciencedb.jp/]] の「アーカイブ」にある[[DDBJリードアーカイブ>http://trace.ddbj.nig.ac.jp/dra/index.shtml]]をクリック<br>
2. 「解析パイプラインでデータを解析」もしくは上部にある「Pipeline」タブをクリック<br>
3. User ID: guest    Passwordは空白でログインできます<br>
4. まず、解析する配列ファイルを指定します。DRA (DDBJ Read Archive)に登録済みの場合はリストから選択、登録していない場合はファイルをアップロードします<br>
　1. DRAを指定した場合、データのメタデータ（サンプル名や実験条件など）が表形式で表示されます。データのダウンロードや閲覧が可能です<br>
　2. 解析に使用する配列データは一番下のテーブルから選択します<br>
5. 解析に使用するツールを選択します。ツール名はツールのオリジナルサイトにリンクされています。「Help」にあるアイコンをクリックするとそれぞれのツールのヘルプが表示されます<br>
　1. 既にゲノムが解読されている配列にマッピングする場合には「Reference Genome Mapping」を、新規にアセンブリする場合には「de novo Assembly」を選びます<br>
　2. 使用するツールにチェックを入れて「NEXT」<br>
6. 解析に使用するリード長を決定します<br>
　1. 「Quality Score」のボタンをクリックすると、配列セットのQualityスコアが表示されます<br>
　2. サンプルと（必要があれば）解析するリード長を指定して「confirm」をクリックします<br>
　3. 複数のサンプルがある場合には、それぞれのサンプルについて配列長を指定できます<br>
　4. 解析するすべてのサンプルを「confirm」したら、「NEXT」<br>
7. マッピングする場合、リファレンスとなるゲノムを指定します（de novo Assemblyの場合にはこの過程はスキップされます）<br>
　1. Majorな生物についてはあらかじめ登録されている中から選択します<br>
　2. リストにない場合には、ゲノム配列のIDを指定して配列をダウンロードします<br>
8. 解析プログラムのパラメータを指定します<br>
9. 解析終了のお知らせを受け取るメールアドレスを入力します（必須）。今回はゲストアカウントなので解析は実行できませんが、実際には「BACK」の右側に「RUN」ボタンがあります<br>
10. 左側にある「MENU」の「STATUS」から、解析の実行状況について確認できます<br>
11. 実行結果から、リファレンス配列（Chromosome）とMapping結果ファイル（out.sam、下から3番目）をダウンロードし、[[Tablet>http://bioinf.scri.ac.uk/tablet/]] などのViewerで結果を表示できます（ファイルサイズが大きいため、今回は省略します）<br>
<br><br><br><br><br>


### [[MiGAP>http://migap.lifesciencedb.jp/]] の使い方 (デモのみ) [#re46b80f]
- 統合TV：[[MiGAPの使い方～導入と基本操作～>http://togotv.dbcls.jp/20100624.html#p01]]
<br><br>

1. [[統合データベースプロジェクトページ>http://lifesciencedb.jp/]]の「ツール＆解析サービス」にある[[MiGAP>http://migap.lifesciencedb.jp/]]をクリック<br>
2. 左上のバナーをクリック<br>
3. 「Login」からOpenIDでログイン<br>
4. 「Pipe Line」にアセンブリ済みの配列を アップロード or ペースト (Sample data をクリックすると入力ボックスにサンプル配列が入力される)<br>
5. 入力した配列が「直鎖状」か「環状」か、「真正細菌」の配列か「アーキア」の配列かを選ぶ<br>
6. 「Run」で計算開始<br>
7. 計算状況は「Current Process」から確認できます<br>
8. 「Change User Level」でユーザレベルを変えられます。Bronze = 初心者（すべてお任せ）、Silver = 中級者（プログラムのパラメータを自分で設定可能）、Gold = 上級者（解析プログラムを組み込んだりできるらしい）<br>
9. 計算が終了すると、「Pipe Line History」から結果を見ることができます<br>
　1. フォルダをクリックすると解析のサマリーと、各種ファイルのダウンロードリンクが表示されます（-a の付いているファイルがアノテーション付きの結果ファイル）<br>
　2. ゲノムマップ上をクリックすると、その部分が拡大される。矢印をクリックするとORFの詳細が表示される（chrome ではORFの詳細が表示されない。FireFoxはOK）<br>
　3. 例えば「result-aa.fasta」「result.csv」「result-a.csv」をダウンロードして中身を閲覧<br>
