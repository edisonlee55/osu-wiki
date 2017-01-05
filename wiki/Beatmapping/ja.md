"Beatmapping"って何?
====================

**JP:Beatmapping|Beatmapping**とはosu!でプレイするための譜面を作ることです。 曲、タイミング、オブジェクトの配置、とオプションとしてスキン作成とストーリーボードを作成する必要があります。

始めるには**Edit**を押してください。

普通マッパーは[rankedをさせることを望み](JP:Ranked_beatmap "wikilink")、譜面のRankをするためのプロセスを満たすことで、スコアボードが追加され、なにか変更をしようとしない限りは完了となります。

譜面の一般的な難しさは次のとおりです:

-   [Easy](JP:Easy_(Difficulty) "wikilink")
-   [Normal](JP:Normal "wikilink")
-   [Hard](JP:Hard "wikilink")
-   [Insane](JP:Insane "wikilink")

各リンクをクリックすると[Mapperのためのガイドラインが表示されるので](JP:Mappers "wikilink")、それに従い楽しく適切な譜面を作ってください。

[Mapperはカスタム](JP:Mappers "wikilink")[難易度名を使うことも珍しくありません](JP:Difficulty "wikilink")。(例えば"Mario"のような)

更にあなたはゲストとしてマッパーの名前が入っている難易度も一般的に見つけられます。(例えば Larto's Insane)

特別なモードが追加されたので、今はosu!難易度以外の各モード専用の難易度を追加することができます。 Taiko/Catch the Beat/Osu!maniaのモードだけの譜面で埋めることも可能です。

始め方
======

どうやって新しい譜面を作るのですか?
-----------------------------------

osuはリズムに基づいたゲームなので、あなたが選ぶ曲は明らかで一定のビートを持つものにするべきです。譜面の作成に慣れるまで、BPM(テンポ)が変わったり遅い曲は避けるべきです。

新しい譜面を作るのならば、次の簡単なステップに従ってください:-

-   osu!の上にオーディオファイルをドラッグアンドドロップしてください。(開くか開かないかはここでは問題ではありません。)

他の方法: "Songs"にオーディオデータをいれる。

-   それを開きあなたのオーディオファイルがあるeditスクリーンに行ってください。
-   あなたの新しい曲は選曲画面の一番下にあり、紫色で強調表示されます。

-   曲の上でクリックをしてSong Setupに移動してください。
    -   情報を入力し、タイトルとアーティストが正しいことを確認し、必要ならばソースとタグも加えてください。その後に適切な難易度名を入力してください(Easy,Insaneなどは一例であり、後でこれを変更することが可能です)
-   必要なら他のオプションの設定もできますが、それらは後で変更可能なものです。OKをクリックし、譜面作成を始めることができます。次のステップはあなたの譜面のタイミングを加えるところです。

どうすればタイミングをしっかり測れるのですか?
---------------------------------------------

**タイミングは重要で、間違ったタイミングの譜面は絶対にRankの対象とはなりません。**オブジェクトを置く前にタイミングが完全であることを確認して下さい。もしタイミングに疑問や不安がある場合は、助けてもらうためにModを頼んだり、[Beatmap Help forum](http://osu.ppy.sh/forum/10)で意見を貰いに行くべきです。これは後で*多大な*手間を省略することに繋がります。

ここで正しいタイミングを得るためのヒントをリストしておきます:-

-   基本的なタイミングを発見する方法がある[動画](http://osu.ppy.sh/forum/t/39317) [チュートリアル](http://osu.ppy.sh/forum/t/3815/)を見てください。
-   メトロノームの目盛りが曲の全体において曲のBeatと一致することを確認してください。 少なくとも曲の5%、25%、50%、75%と100%で確認するべきです。
-   BPMのゲージを見てください。BPMの数値が整数に近い場合(0.1以下の差)は、その通じを切り捨てるのが良いでしょう。もし本当にその数字が正しいのであれば、正しいBPMを入れてください。
    -   例えば音が変に聞こえない限り(間違っていない限り)は150.02は150.00に下げるべきです。
-   offsetを微調節するために、曲の再生速度を0.5倍(必要に応じて0.25倍)に下げ、メトロノームと曲のBeatが一致するようになるまで微調節をしてください。
-   いくつかの曲は複数のBPMがある場合があります。必要な場所でタイミングセクション(Timing --&gt; Add Timing Section)を追加することで、これに対応させることができます。 追加されたBPMとoffsetは以前と同様に調節をしてください。タイミング設定パネルで曲中にあるすべてのタイミングのセクションのリストを見ることができます。

どのような情報をSong Setupで入力すればいいのですか?
---------------------------------------------------

2つ目以降の難易度を作る前にこの情報を確認し、作成後は全ての難易度で情報が一貫しているか確認をしてください。あなたは現在**Unicode文字を使用することが許可されています。**

<table>
<thead>
<tr class="header">
<th><p>名前</p></th>
<th><p>説明</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Artist</strong></p></td>
<td><p><strong><u>曲を演奏したり作ったりしたバンド、歌手、グループ。</u></strong> osu!は自動的にmp3からアーティストの情報を取得しますが、その綴りや区切りが正しいかどうかはもう一度確認して下さい。 <em>アニメやゲームのタイトル、企業名などはここに記述してはいけません。(それはタグに記述される内容です。)</em> アニメやゲームなどの作曲家の情報はWikipediaや<a href="http://www.animenewsnetwork.com/">AnimeNewsNetwork</a>や<a href="http://myanimelist.net/">MyAnimeList</a>のような信頼できる情報源から入手することができます。外国人の名前はWikipedia上で表示されている順番通りに名前を記述するべきです。</p></td>
</tr>
<tr class="even">
<td><p><strong>Romanised Artist</strong></p></td>
<td><p><strong><u>アーティストのローマ字名(英語)。</u></strong> 外国人の名前はWikipedia上で表示されている順番通りに名前を記述するべきです。&quot;Artist&quot;にUnicode文字を使用している場合、この枠が使用可能になります。</p></td>
</tr>
<tr class="odd">
<td><p><strong>Title</strong></p></td>
<td><p><strong><u>曲の名前。</u></strong> osu!は自動的にmp3からアーティストの情報を取得しますが、その綴りや区切りが正しいかどうかはもう一度確認して下さい。タイトルは公式のものだけを使用することができます。</p></td>
</tr>
<tr class="even">
<td><p><strong>Romanised Title</strong></p></td>
<td><p><strong><u>曲のローマ字名(英語)。</u></strong>&quot;Title&quot;にUnicode文字を使用している場合、この枠が使用可能になります。</p></td>
</tr>
<tr class="odd">
<td><p><strong>Beatmap Creator</strong></p></td>
<td><p><strong><u>あなたのことです。osuは自動でこれを設定するので、あなたはこれを編集するべきではありません。</u></strong> もしあなたが誰かが作ったゲスト難易度を含めたい場合は、ここではなく難易度名のところに彼らの名前を入れてください</p></td>
</tr>
<tr class="even">
<td><p><strong>Difficulty</strong></p></td>
<td><p><strong><u>譜面の難易度の名前。</u></strong> Easy, Normal, Hard, Insaneがクリックすると選択できるようになります。あなたはデフォルトの名前もしくは自分で名前を作ることができます。他のプレイヤーを困らせないために、難易度の名前は創造的なものであっても、わかりやすいものにしてください。 もしゲスト難易度があるならば、ここに彼らの名前を入れることでプレイヤーに知らせることができます(例 &quot;Larto's Hard&quot;)。</p></td>
</tr>
<tr class="odd">
<td><p><strong>Source</strong></p></td>
<td><p><strong><u>曲の由来。</u></strong>この枠は普段アニメやゲームのために存在していますが、稀に映画やテレビに関しての情報を記入する必要があります。  曲がアニメやゲームから、もしくはであるか、テレビや映画のテーマとしての使用されて有名になった場合は、そのタイトルがここに入ります。<br />
RockやPopは基本的にここを空白にしておく必要があります。 <strong>ここはアルバムのタイトルが記入されるべき場所ではありません。</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Tags</strong></p></td>
<td><p><strong><u>検索を助けるためのキーワード。</u></strong>一般的には、アルバムの名前、ゲスト難易度の作者、会社名や関連のある単語などが記述されます。(あなたの譜面の曲がビジュアルノベルから来ている場合はエロゲまたは、例えばビジュアルノベルのような用語を含むことができます。)ゲストマッパーがいる場合や&quot;コラボ&quot;をした場合は他のマッパーの名前をここに入れてください。タグは半角スペースで区切ってください。埋めることは必須ではありませんが、検索の助けになるので入れることが推奨されます。</p></td>
</tr>
</tbody>
</table>

再度問題を避けるために、難易度名以外のすべての情報が同じになっているかどうか確認して下さい。

譜面作成の基本
==============

Bookmark
--------

| ブックマークコマンド |
|:--------------------:|
|       Ctrl + B       |
|   Ctrl + Shift + B   |
|  Ctrl + Right Arrow  |
|   Ctrl + Left Arrow  |

**<u>ブックマークはタイムラインをマークするツールです。</u>**これはBPMが変化するポイントや、複雑な配置をする予定のあるスペースを確保するのに便利です。

ヒットサークルの追加
--------------------

これは単純で直感的なプロセスである必要があります。以下にノーマルタイプのヒットオブジェクトの基礎的なヒントがあります:

-   Grid levelはView -&gt; Grid levelから細かさ/粗さを変更できます。Noteは自動的にgridに吸い付きます。
    -   Grid snapとTime snapをShiftを押している間に移動/配置すると無効化することができます。
-   noteの上で、もしくは選択されたグループの上で右クリックをすることでそれらを削除できます。別の場所で右クリックをすればNewComboとの切り替えになります。
-   基本的なWindowsのショートカットキーもosu!のEditorで使えます(例: Ctrl+A 全てのオブジェクトを選択。Ctrl+C/V コピー&貼り付け。Ctrl+Z 取り消し)
-   Noteは視認できるスライダーに吸い付きます。なのでもしスライダーエンドにサークルを重ねておきたい場合は、必要に応じてスライダーがよく見えるところまでタイムラインを移動し、そのあとでオブジェクトのタイミングを移動させると良いでしょう。

スライダーの追加
----------------

スライダーの説明に入る前に、2つの事を行ってください。

-   Slider Velocity(スライダー速度)をタイミングタブの下部にてあなたの好きな値に変えてください。これは譜面全体に適用されるので慎重に選んでください。配置が終わった後にSlider Velocityを変更するとリズムが乱れたり形が崩れたりします。 不測の事態を避けるためにも変更は避けましょう。
-   望むタイプのスライダーをセットしてください。曲線には2つのタイプ、ベジェ(緩やかな曲線)とリニア(直線的曲線)タイプがあります。
    -   緩やかなカーブを入れたい場合はベジェタイプが役立ちます。
    -   スライダーに鋭い角(90度など)を入れたい場合、リニアタイプが役立つでしょう。

これでスライダーを置き始めることができます。左クリックでスライダーを起き始め、更に左クリックをするとwaypont(節)を追加でき、右クリックをすることでベジェスライダーを終了させます。もしあなたがリニアスライダーを作りたい場合、ベジェスライダーを作成してから、作成されている節を左クリックすることで赤い節に切り替わり、鋭角のスライダーを作成できる節へと変化します。形を調節する前にスライダーのタイミングが正しいことを確認することを推奨します。

他のスライダーに関するいくつかのヒント:

-   スライダーにリピート、言い方を変えるとリバースを追加するには、タイムライン上のスライダーの終端をドラッグし、終了後の場所まで引っ張ることでできます。
-   waypointをドラッグすることでその位置を移動させることができます。 右クリックすることでそのポイントを削除し、Ctrlを押しながらクリックするとポイントが追加されます。
-   ヒットサークルと同じように、Shiftを押している間はスナップを無効にすることができます。これはスライダーを整えるのに有用です。

スライダーがよく見えるように試して努力をしてください!偏り/オーバーラップ/醜いスライダーはあなたの譜面を台無しにします。加えてスライダーが他のスライダーと重ならないようにし、スライダーの道も常に良く見えるようにしてください。Uターンやスライダーの重なりによって頭と尾が見えない状態にすることは避けてください。

スピナーの追加
--------------

スピナーを譜面に追加するには、左クリックで起き始め、あなたが終わらせたいところまでタイムラインをスクロールし、右クリックで終了させます。スピナーの長さは適度な長さにし、長いスピナーは避けてください。長いスピナーは疲れる上に退屈です。一方短すぎるスピナーも良くはありません。"スピナーもスパム"は許されません。

"スピナースパム"とは: [Trans-Siberian Orchestra - Wizards In Winter (Impossible difficulty)](http://osu.ppy.sh/b/296)が持つ5秒以内に48~51個のスピナーを置いているもので、短すぎるスピナーはプレイに影響を与えます。その譜面はNinja Spinnerを除けばRankableです。

コンボって何?
-------------

コンボはosuにおいてスコアに関して重要な要素を持つオブジェクトのグループです。異なるコンボは異なるコンボカラーを持ち、より譜面を読み取り易くするために必要不可欠です。通常コンボは音楽上にある何かの音(ドラム、ギター、ボーカル等)に合わせて置かれ、もしあなたが誘導を行いたい場合はタイミングパネルに表示される区切りなどに注意してください。大体のコンボの長さの目安は5-15ですが、これはStream(10-30)を含みません。 注意: 終わりのコンボ(激と場合によっては喝)は他の300と違い多くHPを回復します。長いコンボは回復量が少ないので、短いコンボが推奨されます。HPの回復量が少ないことで長いコンボは不自然に難しくなるかもしれません。

Breakを自分の譜面にどうやって入れるの?
--------------------------------------

長い譜面ではプレイヤーに休憩を与える為にBreakを含むべきです。入れ方は単純で、あなたが入れたい場所を空白にし、"Insert Break Time"をEditorでクリックすれば入れられます。注意として2つのオブジェクトの間にBreakは入れる必要があるので、それを入れる前にBreakを入れる予定の場所の始まりと終わりにオブジェクトを"目印"として入れる必要があります。

A couple of rules of thumb are:-

-   2分の曲なら少なくとも中央辺りで1つのbreakを入れるべきで、3分なら2箇所に均等に置かれるべきです。これは使われる曲によって左右されます。
-   休憩の長さは理にかなったものにしてください。短いBreakは無意味で、30秒ものBreakは実用的ではありません。5-15秒を目安に入れてみてください。

ブックマークを使用すればBreakを入れる場所を考える上で役立ちます:

-   譜面を作る前に曲を聞き、どこでBreakを入れるかを決めてください - 可能なら均等に入れてください。
-   タイムライン上の各Breakの開始と終了をチェックするために、ブックマークを使用するとよいでしょう。
-   各ブックマークに一時的にマーカーとしてオブジェクト(普通はサークル)を入れ、休憩を追加したい間に移動後"Insert Break Time"をクリックしてください。
-   Breakが曲全体に万遍なく入れられているか、短すぎたり長すぎたりしないかに注意し、プレイヤーに眠くならない程度に手を休める期間を与えてください。BreakはEditorの下のタイムラインで確認できます。
-   最初のオブジェクトを置く前にBreakを置きたい場所にブックマークを入れるとよいでしょう。ブックマークは有用で、それを使うことであなたにとってアドバンテージとなるでしょう。

Beat Spacingってなんですか?
---------------------------

<img src="Beatspacing.jpg" title="fig:A quick illustration" alt="A quick illustration" width="200" /> 直感的なプレイのために譜面はよい"ビートスペーシング"を持つべきです。一般的にタイムライン上で互いに近いBeatは、配置上でも近くなるべきで、逆も同様です。これは調和した譜面によって曲の流れを保証し、譜面をより楽しくさせることに繋がります。

この感覚を維持させる簡単な方法は[Distance SnapをEditorで使用することです](JP:Distance_Snap "wikilink")。オブジェクト間の距離はマウスホイールを使用することで調整することができ、それを使っている限りは間隔が常に同じになります。

曲に難易度を追加するには?
-------------------------

新しい難易度を作るには、単純に既存の難易度を開き、"File" --&gt; "Save As New Difficulty..."を選び、難易度の欄を変更するだけでできます。

様々なバリエーションを異なる難易度との間で加えてください。追加、置き直し、削除をすることで新しいパターンを作ることができます。既存のオブジェクトを反転させたり開店させることもできます。譜面の難易度は難易度レベルに応じた差(注1)がありつつも、ある程度は似た部分(BPMの速さ、BPMの変化点や、特定のビートマップの設計など)を持つべきです。

**注意書き:** 難易度の設定(例:HPドレイン)を変えただけの譜面は新しい譜面の難易度とは認められません。それは怠惰な譜面で、新しい譜面をまともに作るように要求されるでしょう。

譜面の視覚情報
==============

BGの色をどうやって変えるの?
---------------------------

"Design"タブをクリックしてください。そこで"Set BG Colour"というボタンを押し、あなたが決めたカラーに変更をすることができます。ストーリーボードを使用するわけでなければ、背景画像や動画によって置き換えられます。

背景画像や動画をどうやって入れるの?
-----------------------------------

"Design"タブをクリックしてください。そこで"Insert Backgroundr"というボタンを押すと、ダイアログボックスが表示され、そこであなたが追加したい画像や動画を見ることができ、譜面に追加することができます。

注意点:-

-   画像は.JPGか.PNGを使うことができます。画像の大きさは800\*600以下にキープするのがベストですが、現在のルール上は最大1024\*768または1366\*768(ワイド用)まで入れることができます。
    -   可能な場合は画像の容量を圧縮して小さくしてください。ネット上にはそういったことができるソフトがあります。
-   動画のDivX、XviD、またはそれに近いコーデックを使用してエンコードするべきです。 H.264のようなコーデックの使用は推奨されません。
    -   動画のファイルサイズを小さくするために動画の音声データは削除する必要があります。
-   画像や動画はフォルダからそれらを削除することで、消滅させることができます。

カスタムイメージやサウンドをどうやって私の譜面に入れるのですか?
---------------------------------------------------------------

-   入れたい画像と音声ファイルを作成してください。
-   適切な名前に変更をしてください。
    -   ランダムな名前: ストーリーボード用。 ストーリーボードができていない時、それは無意味なものとなります。
        -   例: A, Lyric1, 007, etc
    -   スキンの名前: 譜面は自動的にそのファイルを使用し、プレイヤーのスキンと置き換えて使用されます。あなたは成功している場合それに気付くことができます。
        -   例: normal-hitnormal (このサウンドはプレイ中にプレイヤーのスキンの代わりに置き換えられます。)
-   あなたの曲のフォルダにデータを置きます。

[適切な各カスタムサウンドのファイル名はここで見つけることができます。](http://osu.ppy.sh/forum/t/729/start=0)

どうやって譜面にストーリーボードを入れるの?
-------------------------------------------

"Design"タブをクリックしてSBE ([Storyboard Editor](JP:Storyboard_Editor "wikilink"))に移動してください。

キーボードのショートカットキー
==============================

ショートカットキーってあるの?
-----------------------------

あります。必要ならばすぐに見れるようにプリントアウトするとよいでしょう。

|           一般的なショートカット          |
|:-----------------------------------------:|
|                   **H**                   |
|                   **Z**                   |
|                   **X**                   |
|              **C / Spacebar**             |
|              **Left / Right**             |
|          **Shift + Left / Right**         |
|                **Ctrl + B**               |
|                **Ctrl + G**               |
|           **Ctrl + Left Arrow**           |
|           **Ctrl + Right Arrow**          |
|                **Ctrl + L**               |
|                **Ctrl + S**               |
|                **Ctrl + N**               |
|                   **F1**                  |
|                   **F2**                  |
|                   **F3**                  |
|                   **F4**                  |
|                   **F5**                  |
|                   **F6**                  |
|                Compose Mode               |
|        **Number Keys (1, 2, 3, 4)**       |
|           **Q, W, E, R,T,Y, L**           |
| **Shift + (Q, W, E, R) (ヒットサウンド)** |
|  **Ctrl + (Q, W, E, R) (ヒットサウンド)** |
|                 **Delete**                |
|                **Ctrl + Z**               |
|                **Ctrl + Y**               |
|                **Ctrl + A**               |
|                **Ctrl + X**               |
|                **Ctrl + C**               |
|                **Ctrl + V**               |
|                **Ctrl + D**               |
|                **Ctrl + G**               |
|           **Alt (置いている間)**          |
|          **Shift (置いている間)**         |
|             '''Shift (変更中)             |
|                   **J**                   |
|                   *' K*'                  |
|                   **G**                   |
|               **Ctrl + 1-4**              |
|              **Ctrl + &lt;**              |
|              **Ctrl + &gt;**              |
|               *' Ctrl + H*'               |
|               *' Ctrl + J*'               |
|                Timing Mode                |
|                   **T**                   |
|   **Shift (while adjusting BPM/Offset)**  |
|                **Ctrl + B**               |
|                **Ctrl + P**               |

マウスでどんな操作ができるの?
-----------------------------

ここにそのリストがあります:

|        Mouse Controls        |
|:----------------------------:|
|        **Left Click**        |
|     **Ctrl + Left Click**    |
|        **Right Click**       |
|        **Mouse Wheel**       |
| **Ctrl + Alt + Mouse Wheel** |
|    **Ctrl + Mouse Wheel**    |
|     **Alt + Mouse Wheel**    |

<Category:Beatmapping/JP>