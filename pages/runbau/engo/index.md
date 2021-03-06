---
layout: post
title: 縁語 概要
date: 2014-01-11
---

## 音韻と音節

ASCII表示は基本的にロジバンに従う。

### 音韻

母音は、a,e,i,o,u であり、ロジバンと同等。

|p|無声両唇破裂音|[p]|パ音|
|b|有声両唇破裂音|[b]|バ音|
|k|無声軟口蓋破裂音|[k]|カ音|
|g|無声軟口蓋破裂音|[g]|ガ音|
|c|無声後部歯茎摩擦音、無声歯茎硬口蓋摩擦音|[ʃ][ɕ]|シャ音|
|j|有声後部歯茎摩擦音、有声歯茎硬口蓋摩擦音|[ʒ][ʑ]|ジャ音|
|s|無声歯茎摩擦音|[s]|サ音|
|z|有声歯茎摩擦音|[z]|ザ音|
|tc|無声後部歯茎破擦音、無声歯茎硬口蓋破擦音|[t͡ʃ][t͡ɕ]|チャ音|
|dj|有声後部歯茎破擦音、有声歯茎硬口蓋破擦音|[d͡ʒ][d͡ʑ]|ヂャ音|
|ts|無声歯茎破擦音|[t͡s]|ツァ音|
|dz|有声歯茎破擦音|[d͡z]|ヅァ音|
|n|歯茎鼻音、軟口蓋鼻音|[n][ŋ]|ナ音|
|m|両唇鼻音|[m]|マ音|
|l|歯茎側面接近音、歯茎接近音、歯茎はじき音|[l][ɹ][ɾ]|ラ音|
|h|無声声門摩擦音|[h]|ハ音|
|w|有声両唇軟口蓋接近音、両唇接近音|[w][β̞]|ワ音|
|y|硬口蓋接近音|[j]|ヤ音|

ロジバンと大きく異なるのは、h, y, w があることと、ロジバンのrが l に吸収されていること。  
ただし、lは歯茎震え音や口蓋垂ふるえ音で発音できない。これもロジバンとは異なる箇所である。

微妙に異なるのは、シャ、チャ（とその有声音）に、歯茎硬口蓋音が許容されるということ。

### 音節・アクセント

アクセントは必ず語頭。このため、ふつう単語はスペースで区切るが、アクセントをキャピタルやアキュートで表せばスペースは無くてよい。

音節については、

DC = tc, dj, ts, dz  
DDC = ttc, tts  
C = p, b, k, g, c, j, s, z, n, m, l, h, w, y  
V = a, e, i, o, u  
C' = p, b, k, g, c, j, s, z, l, h  

とすると、基本的には

[DC\|C\|2*C'\|DDC], V, [n]

となる。ただし、これによって得られた音節列は次の規則によって若干の変形を受ける：

- 小休止、撥音、促音の後のj/zはdj/dzになる。（dj/dzはこれ以外で生じない。促音のdj/dzは、ddj/ddzと記す。）
- 両唇音（p/b/m）の前のnはmになる。
- 語頭以外のCiV, CuV はそれぞれ CiyV, CuwV となる。ただしCが拗音化可能（p, b, k, g, n, m, l, h）ならば CyVとなる。
- 語頭のCiyV, CuwV は CiiyV, CuuwVにする。
- wu, yi はそれぞれ u, i になる。

縁語では開拗音のみ起こる。合拗音（CwV）は起こらない。

また、格助詞・接続詞・感動詞・終了詞では語末がs,l,nで終わる。

例：
enma → emma
ajja → addja
mezza → meddza

辞書に登録されている語で語頭がdj/dzのものは文中（小休止の直後で無い限り）で使われるときはj/zに直す。  

文中の小休止はカンマ(,)で表し、文末の小休止はピリオド（.）で表す。


### 母音の無声化

i, u が語頭になく、無声子音（p, k, c, s, t, h）に挟まれているとき、無声化する。

※ 語末の無声子音の音節の母音は無声化しない。

### 二連母音

同じ母音の連続は長母音化する。

次の二連母音は二重母音化する。ただし、ゆっくり発音するときは母音接続となる。

- ai [aj]
- ei [ej]
- oi [oj]


## 品詞

- <b>表縁</b>：縁の内容を表す語。いわゆる述語のことであり、文中の縁点がどのような縁で結ばれているかを記述する。  
- <b>縁点</b>：縁点とは縁によって結ばれる語のことである。すなわち縁のノードであり、いわゆる項のことである。  
- <b>格助詞</b>：縁点の後ろにつく。  
- <b>接続詞</b>：縁点同士、文同士、句同士を繋げる。  
- <b>数詞</b>：数字単体、もしくは、konに繋げて量化子として用いる。  
- <b>場面詞</b>：las以前に置く。その文の議論領域を表す。  
- <b>感動詞</b>：単独で用いられる。話者の心情・呼びかけを表す。  
- **開始詞**：構造の開始を表す。
- <b>終了詞</b>：構造の終了を表す。

※ わずかだが、これに属さない語もある。しかしながらそれらは、表縁の異種としてみるべきである。  
現に、それらの語はいわゆる連体詞、連用詞であり、ただ終止形の形を取らないという点でのみ表縁と異なるからである。

※ 縁点はさらに**物点**と**場点**に分類できる。

## 簡単な形態論

- 表縁：語末が必ずiの音節で終わる。
- 数詞：語末が必ずoで終わる。
- 格助詞・接続詞・感動詞・終了詞：必ず s, n, lで終わる。
- 縁点・場面詞：基本的に語末は母音で終わるが、nで終わることもある。

## 基本的な文構造

文 = [場面部], [縁点部], 表縁部, 終了部;

※以下は未完成

場面部 = {場面句} las#  
縁点部 = {縁点句}   
表縁部 = [{表縁-\連用形}] (表縁-\連用形 :IF(活用on))|(表縁-\終止形 :IF(on))   
終了部 = 活用on | on  
縁点句 = 修飾節   
場面句 = {場面詞}  


### 強い関与原理

格のついていない縁点には任意の格が想定されうる（ただし、格伝播が優先される）。どの格がつくかは文脈や背景知識による。
これは、縁に縁点のみを教えるに等しい。すなわち、どの縁点がどのように振る舞って結果その表縁を実現させるかについてを自然に任せるということである。

wi di neco dui on：私・あなた・本、受け取る。

※ 強い関与原理を用いる場合、縁点の直後に小休止を置くことが多い。

wi, di, neco, dui on

実用上、これは不意の語の合成を防ぐためである。たとえば、

en ten coi on：縁、点、云々だ。

を小休止をおかずによむと、

enten coi on：縁点、云々だ。

近い発音になってしまう。とはいえ、前者は én tén であり、後者は énten であるからアクセントから聞き分けることは可能である。


## 表縁の活用

表縁はいわゆる述語に相当し、**終止形、連体形、連用形、仮定形、感動形、縁点形** の６つに活用する。  
とはいえ、感動形が意味をなすのは比較的僅かであるし、縁点形も意味の曖昧さからあまり用いられない。ゆえに、実用上は活用は４つである。

表縁の活用語尾は語末の-iである。

例：oloi, olo-i (白い)

- -i；終止形・不定形（oloi）
: 典型的な文末の形
- -e；連体形（oloe）
: 縁点の修飾に使う。例）oloe mo：白いもの
- -a；連用形（oloa）
: 活用onの接続や、表縁の修飾に使う。例）tcea oloi：とても白い
- -go；仮定形（ologo）
: 普通このあとに on がくるので、しばしば合体して、-gon の形になる。
- -Vn；感動形（oloon）
: Vは語幹末の母音。一部の表縁でのみ有意味。感動詞を形成する。例）sipiin：おやすみ
- -no；縁点形（olono）
: 縁点として用いる。例）olono :「白いということ」「白さ」「白」

※ 命令形は少なくとも原縁語にはない。対人間の意思疎通ツールとしても使い勝手がよくなるようにした拡張縁語ではいくらか提案はなされている（-ke）  
ただし、拡張縁語で活用を拡張しようという意見は比較的少数派であり、大多数は原縁語の活用を上手いこと援用しようと考えている。  
現在、最も有力な命令用法は、感動形を用いる方法である。例）oloon on!：白くあれ！


## 格

yol, nicol, yolen, nicolen, mes, yan, el, non, dzemes がある。この他に場格系もあるが、これは場面部のところで述べる。

このうち特に、yan, nicol, yolen, nicolen, mes, yan は礎格系と呼ぶ

#### 礎格系

★基本用語

- **被縁者**：表縁の内容を被るもの。
- **発露**：表縁の内容が実際に現象として起こっていること。実現性、事実性。
- **非発露**：表縁の内容が実際に現象としては起こっていないが、潜在的にその縁を有しているということ。可能性、潜在性。

　

- yan；支格、因格
  : 被縁者の発露／非発露にもっとも有力に関与していることを表す。きっかけ、発端、支配者、原因など。
- al；被縁格
  : 被縁者であることを表す。発露／非発露については不定である。yol, nicol の一般（省略的）格。
- yol；発露被縁格
  : 被縁者であり、その表縁の内容が発露していることを表す。
- gal / nicol；非発露被縁格
  : 被縁者であり、その表縁の内容が非発露していることを表す。
- yolen；向発露被縁格
  : 被縁者であり、その文の示す時空間点では非発露であるが、yan点によってそれが発露に向かうことを表す。
- galen / nicolen；向非発露被縁格
  : 被縁者であり、その文の示す時空間点では発露であるが、yan点によってそれが非発露に向かうことを表す。
- mes；関格、要格
  : 被縁者とその縁で結ばれていることを表す。表縁によって、どのように振る舞うかが異なりうる。関係、関与など。

yan と mes は被縁者と結ばれているという点では同じ意味である。違いはあえていえば、階層である。  
mes は被縁者と同じ階層に属するが、yan は被縁者やmesよりも一つ上の階層から縁を結ぶ。  
（あくまでこれは比喩であって、実際に縁がそのようになっているわけではない）

この階層性は格の順序によって表される。すなわち、文において左にあればあるほど、その格は（階層を作るなら）外側（上側）にある。  
このことは、「X yol Y yan ZZZ on」 と「Y yan X yol ZZZ on」が若干異なるニュアンスでありうることを意味する。

※ nicol/nicolenは古い言い方

#### 非礎格系の基本格系

- el；礎格
: 礎格系（yan, al, yol, nicol, yolen, nicolen, mes）の一般格（省略格）。格伝播が起こせる（以下で詳述）。
- non；体言連結
: 日本語でいう「の」にあたる。基本的には、縁点を縁点に修飾するために用いる。なお、前置修飾である。
- dzes / dzemes；非関格
: mesの否定版。被縁者とその縁では結ばれていないことを表す。

※ dzemesは古い言い方

#### 格伝播・弱い関与原理

礎格には<b>弱い関与原理</b>がある。すなわち、el以降（len以前）の格のない縁点にはelが想定される。たとえば、

X el Y Z W len

において、「Y Z W」には el が格として伝播する。つまりこれは、

X el Y el Z el W el len

に等しい。ここで、**len は elの伝播の終了詞**である。lenがなくてもonによって自動的に伝播は切られる。


elと礎格系を合成した**伝播格系**はelと同じように格継承の能力をもつ：

- yolel : yol + el
- nicolel : nicol + el
- nicolenel : nicolen + el
- mesel : mes + el
- yanel : yan + el

この中でも特に mesel は実用的である。


#### 格伝播の相互作用

伝播格系が複数現れるとき、最も右の伝播格が効果をもち、最初のlenによって切られる。  
すなわち、括弧（）の処理と同じである。

X yolel Y mesel Z W A B len C D len = (X yolel (Y mesel Z W A B len) C D len)

yanel は少し厄介である。というのも、これは単に yan が伝播すると考えることができない。  
これは、yanのもつ階層性による。yanelは階層性を作らずにyan様役割を作るのに適している。たとえば、

X yan Y yan Z yol coi on

では、(X yan (Y yan (Z yol coi on))) のように階層が生じるが、

X yanel Y [len] Z yol coi on

では、(X yanel Y (Z yol coi on)) となる。



## 場点と場面部について

場面部にはその文の表す縁が及んでいる範囲を明示するのに用いる。

要は、議論領域の示唆であり、見方によれば話題部である。

場面部には原則、場点が並び、**las**によって閉じる。場点には場格系がつけられる。見方によれば、場点そのものが格である。

基本的な場点を挙げる：

- belle；まわり
- bee；外
- nee；中
- too；とき
- loo；ところ

### 場格系

- ekkas；起点格・離格・出格（から）
- ihhen；目標格・向格・入格（へ）

基本的に、

{(縁点 non \| 修飾節), 場点, [non 場点] [場格]} las

という構造になる。例）wi non loo las：私のところで, di non loo ihhen：あなたのところへ

場点を繋ぐ際は、原則、too/looが優先する。

例）can kuo yol oloi on non too non nee：これが白いときの中で（これが白い間）

### 場面部における無標物点

通常、場面部には場点のみが置かれるが、無標の物点が置かれることもある。  
このとき、物点は主題「～に関して言えば」を表す。日本語でいうところの「は」である。

例）wi las kuo yol oloi on：私について、ここが白い。

## 終了詞 on の事象局面表示による活用

いわゆるアスペクトである。

onの接頭辞としてつける。基本的には以下がある：

- lene-；未然
- lenibe-；将前
- le-；開始
- mu-；進行
- ce-；終了
- cetsibe-；直了
- cetse-；完了
- te-；点

le-, ce- mu- が基本要素で、それぞれ、「始め」「終わり」「間」くらいの意味。  
さらに、ne-,tse- は「より前段階」「より後段階」を示し、-ib- はそれが参照点に近いことを表す。  

単純に、上記以外の相としては、letse-, letsibe-, cene-, cenibe-, が考えられる。それぞれ前から「既に始まっている」「始まったばかりだ」「まだ終わっていない」「終わろうとしている」  
te- と mu- については、 tse- ne- がついて有意味なものはあまり考えられそうにない。ただし、teneon non tciko 「～する前の時点」、tetseon non tciko 「～する後の時点」 は比較的よく使う。  
ただし、時の従属節に関しては、追加的格を使ったほうが簡潔。 on licel 「～しながら」、on lijus 「～を終わりながら（抜け出しながら）」、on lihin 「～が始まりながら（入りながら）」  

複合相は容易につくれる。XX-YY-on のとき、XX-(YY- on)と解釈する。つまり、lenecetsibeon は「終わったばかりになろうとするところ」を表す。  

## 修飾節

**can** によって開始され、onによって閉じ、nonで接続する。関係代名詞はcoa。
can wi yan coa mes dua on non niho：私が与える花

ふつう、on と non が合成し、**onon** となる。活用したonの場合、-onon となると考えればよい。

少し丁寧に話すときは、修飾節のonで一旦小休止を入れる。

### 修飾節略記

格類が修飾節の表縁にかかっていることを明示する**節略格類**を用いることができる。これらは、格の語末の子音の直前に no を入れてできる：

- yanon：yan + no
- yonol：yol + no
- ganol：gal + no
- yolenon：yolen + no
- galenon：galen + no
- menos：mes + no
- enol：el + no
- dzenos：dzes + no
- anol： al + no

また、coaも節略形がある。

- cona：節略的関係代名詞

これらを用いることで、修飾節を使わずに相応の表現ができる。

例）wi yanon (cona menos) due niho：私が与えた花

節略格と表縁に挟まれた無標の縁点はその修飾節内の縁点としてみなされる。よって、格を明示したいものを最初にもってきさえすれば、節略記はかなり有効的に使える。

例）wi yanon coa di due niho：私があなたに与えた花

ただし、見て分かる通り、節略的表現ではonが無いため、アスペクト（事象局面）は不定になる。

さらに、節の縁点に格の付いたcoa（cona）を明示するとき、表縁とcoa（cona）の格を合成した**付格表縁**を用いることができる。  
作り方は、表縁の語幹に格を語末の子音を促音化してつけ、-eによって連体形にする。

dumesse niho：与えられる花

wi yanon dumesse niho：私によって与えられる花

※ 付格でない表縁による連体修飾は、修飾される縁点がその表縁に対してどのように振る舞うか（つまりどのような格がつくか）が不定である。  
大体は、YY-e は YY-yolle か YY-messe を意味しうる。


## 数字と量化子

|leo|0|
|pio|1|
|yao|2|  
|seo|3|  
|bio|4|  
|muo|5|  
|hao|6|  
|dzeo|7|  
|nio|8|  
|soo|9|  
|ceo|10|  
|ce pio|11|  
|ce gio|12|  
|ce seo|13|  
|ce bio|14|  
|ce muo|15|

|gi ceo|20|  
|se ceo|30|
|ceceo(djao)|100|
|gi ceceo(gi jao)|200|  
|se cece(se jao) mu [ce] bio|354|

|ceo                |10 (1e1)|
|ceceo (djao)       |100(1e2)|  
|keo                |1000(1e3)|
|cekeo              |10000(1e4)|  
|cecekeo (djakeo)   |100000(1e5)|  
|kekeo  (kyao)      |1000000(1e6)[100万]|  
|cekekeo (cekyao)   |10000000(1e7)|  
|cecekekeo (djakyao)|100000000(1e8)[1億]|   
|geo                |1000000000(1e9)|
|cegeo              |10000000000(1e10)|  
|gegeo   (gyao)     |1000000000000000000(1e18)[100京]|  
|cegegeo (cegyao)    |1e19|
|cecekekegegeo (djakya**a**gyao)|1e26|

例）gi tcekekeggeo se ceo：200ヨタと30

量化子として用いる場合、**kon**で縁点と接続する。例）soo kon puola：9個のりんご

非桁的な数詞も存在する。次のものは、曖昧数詞とも呼ばれる：

|たくさん|boodo|
|いくつか|setto|  
|すべて  |onlo |

以下のものも数詞とみなされる：

|以上      |gomo|   
|以下      |como|	  
|より多く  |tsemo|  	  
|より少なく|nemo|  	  
|小数点    |te|	    
|括線（/） |we|  	  
|～のうちの|wejo|
|+         |punsa|
|-         |minsa|

|かつ      |ees|

wejo は2つの数を繋げる役目があるので、wejoの前の数は-oで終わる

se gomo/como：3以上／以下

ce gomo ees tce nemo：10以上100未満

se we muo kon appendjo：3/5のケーキ		

mu**o** wejo seo kon puola：5個のうちの3個のリンゴ		

boodo wejo setto kon puola：たくさんあるうちのいくつかのリンゴ		

## 造語法 概論

※この部分は他の部分に比べてもより一層未完成である。

### 縁点A+縁点B

そのままくっつける。例）en + ne → enne ：縁音

ただし、音韻の制約における変化は起こる。

### 表縁+X

基本的には、表縁の語幹に縁点をそのままくっつける。

例）katoi + na → katona：冷酷バサミ、臆せず縁を切る者

例）kii + lio → kilio：奇妙な時計、クソ真面目

例）tcei + lagui → tcelagui：とても青い、藍色の


### 混成の現時点でのいくつかの案

- Xの語頭が母音、半母音（y,w）のとき、表縁の語末の母音を(iを含め)2つ落とし、Xの半母音を落とし繋げる。  
  例）batsai + wayui → batsayui：早歩きする


## 雑多事項

適切な命題は、半ば自発的に真に向かおうとするポテンシャルを有する。

縁技師の一般業務の手順は簡単に言って、  
① 問題の箇所の修繕のために
② 縁語によってエネルギーを生成し
③ そのエネルギーを引き出し
④ 修繕を行う

修繕のための小道具は縁孔の空いた針

縁孔は縁エネルギー（エネギッケ）の保持に重要。あと、一箇所に滞在することをかなり嫌うので、常に流しておかないといけない。
縁技師の修繕の姿はそのために半ば舞っているようにさえ見える。簡単な指標として、縁技師としての実力と舞の滑らかさは比例する。

一般的に、縁語自体から取り出せるエネギッケの量はそこまで大きくない。
しかし、よく知られた現象に、発話者の感情とのリンクがある。すなわち、話者の感情が強く発露するとき、
縁語によるエネギッケ抽出がその感情のエネルギーも引っ張ってくることがある。

厳密には、強い感情を介して話者自身のエネギッケを奪う。縁技師（たまに一般人も）の中には、この現象無しに自身のエネギッケを使えるものや
逆に自発的に周りのエネギッケを自身に取り込むような性質をもつものもいる。特に後者は厄介であり、よく修繕対象となる。
