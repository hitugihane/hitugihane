

## 羊羽（ひつじ）です！！
> 

> 開発経験をウェブアプリ、スマートフォンアプリそれぞれ以下に記載しています。

<details><summary>WEBアプリケーション -チーム開発</summary><div>

## YubiPass
> 概要：　YubiPassは指紋センサーを用いてユーザーごとに固有のウェブサイト登録用パスワードを生成するｗebアプリです．

> 開発の背景：ハッカソンに参加するためにWEBアプリケーションとアルディーノを用いて友人と拠点は関東と関西で離れていましたが６人で開発を進めました。私は主にリーダーを務めパスワードを生成するためのアルゴリズムの作成などを行いました。
　このプロダクトは、春休みYahooJapanのHACK Uで提出するために参加するために二週間で作成したアプリです。自身がスマホをなくした際、認証システムだと端末がなくなってしまい多くのアカウントにログインできなくなってしまいました。同じ指紋でのログインでも事前に登録しなきゃいけない認証システムでなくパスワード生成を行うことで端末に依存しないログインシステムを作成することを目指しました。
拠点の離れた場所でのハードウェアを用いた開発は大変でしたがオンラインで密にコミュニケーションをとることで当日動かすことができ全国から総勢２５チームの参加でしたが優秀賞をいただくことができました。
 
> 開発期間：開発期間は2週間
> 
> 開発人数：６人
> 
> 開発言語：Python（Django）C言語
> 
> 役割：リーダー
> 
> GitHub：https://github.com/Hack-U-2024-OSAKA-hogehoge/YUBIPASS
>
> こだわったこと：同じ指紋情報なら同じ結果のパスワードが生成されるよう画像処理で様々なアプローチで行った。結果として同じ指で５度生成したら同じパスワードの組み合わせになるまで精度を上げることができた。
> 
> 開発秘話：本当はアルディーノ上で指紋情報を取得しパスワード生成するようにしたかったがメモリが足りず、妥協でサーバ上で処理を行った
> 

## ＭＯＧＲＡ
> 概要：　モチベーショングラフを簡単に作成できる「MOGRA」というウェブアプリケーションを作りました。

> 開発の背景：ハッカソンに参加するためにDjangoとJavaScriptを用いて友人と４人で開発を進めました。私は主にリーダーを務め、フロントとバック、インフラの役割も果たしました。
　このプロダクトは、春休みYahooJapanのHACK Uで提出するために参加するために作成したアプリです。自分がモチベーショングラフを作成する際に、もっと楽に綺麗に見やすく作成できるようになるツールがあればいいと考えたことがこのアイデアを採用した背景にあります。GitHubをはじめ様々なツールを用いて開発に臨んだため、基本オンラインで開発したにもかかわらずテンポよく開発が進みました。
　私以外のメンバーは開発初心者でしたが、毎日のコアタイムを設置し進捗を細かく共有することで、一人で行き詰まってしまうことなく、全員で課題を対処することができ当初予定していた開発目標を1週間という短い期間で作成することが出来ました。
　今回の経験を通して、1人ではできないことも、チームでやるからこそ大きいことや難しいことに取り組めると改めて実感しましたし、チームで開発する”面白さ”そのものを感じれたように思います。今後のチーム開発にもここでの学びを活かしていこうと思います。
 
> 開発期間：開発期間は2週間
> 
> 開発人数：4人
> 
> 開発言語：Python（Django）JS(Chart.JS)
> 
> 役割：リーダー、インフラ、バックエンド、フロントエンド
> 
> GitHub：https://github.com/Hackathon-kait/mogra
>
> こだわったこと：デザインにかなり時間と労力をかけた。Figmaを用いてトンマな設定から検討し、UXを意識しカーソルで掴んでモチベーション度を入力できるよう実装したりだとか細かいところまでかなり意味を持ったデザインの実装を行なった。また、アカウント情報の編集から、パスワードを忘れた際のパスワード修正機能など細かい機能まで実装を短い開発期間ながら実装し、気の利いたUI/UXを実装できたと思う。
> 
> 開発秘話：メンバーが私以外開発経験がなかったが、１週間で一人でプログラムを考えて作成するまで成長してくれた


## Createst

> 概要：ChatGPTが作成したテストを回答や採点をしてくれるWEBアプリケーション

> 開発の背景：ハッカソンに参加する際に作成したアプリ。コロナ渦で学生同士の交流が出来ず、先輩から過去問を得ることが出来ないという課題から、入力したテーマをもとに選択式の問題をChatGPTに作成させ管理（生成、回答、採点）するアプリケーション。

> 開発期間：開発期間は2ヶ月
>
> 開発人数：3人
>
> 開発言語：Python（Django）
>
> 役割：サブリーダー、バックエンド、フロントエンド、デザイン
>
> GitHub：https://github.com/Hackathon-Spring-Bteam/Createst
>
> こだわったとこ：当時出たてほやほやのChatGPTのAPIを用いた開発を行なった。トークンによってかかる料金が変わってしまうため、プロントには英語を用いた。
>
> 開発を終えて思うこと：初めてのことづくしで、携わるメンバーも少なかったため、かなりやり残した点があった。まず正誤判定の際に使うための正解データがDBを確認すると選択肢にないものであったり、複数台同時にアクセスしてテスト作成すると、ChatGPTのAPIのレスポンスが帰ってくるまでの処理を独占してしまい後からリクエストを出した方の端末でエラー画面が出てしまうなど課題をかなり残した状態で開発が終わってしまった。
> 
> 開発秘話：ＭＯＧＲＡを作成したハッカソンと別のハッカソン時期がかぶってしまったため、めちゃくちゃタスクが多かった。

## LIFE

> 概要：バーコードを用いて本の管理を行うウェブアプリケーション。

> 開発の背景：ハッカソンに参加する際に作成したアプリ。何巻も続く漫画などの本をコレクションする際、どの巻を持っているのか忘れてしまうなどの課題から、本のバーコードを読み取らせるだけでGoogleBooksAPIをもちいて情報を引っ張てきて記録管理ができるアプリケーションを作成した。

> 開発期間：開発期間は2ヶ月
>
> 開発人数：5人
>
> 開発言語：Python（Django）
>
> 役割：フロントエンド、バックエンド
>
> GitHub：https://github.com/Hackathon-b-team/b-team
>
> こだわったところ：デザイン（理由は↓）
>
> 開発を終えて思うところ：デザインについてかなりこだわった。こだわりすぎた。開発期間２ヶ月のうちデザイン案最終verが出たタイミングが最終週で、機能自体はある程度の実装が終わっていたが最後にみんなでCSSを当てる作業をしていたが、そこをデプロイの時間に充てていれば当日急に動かなくなるなんて怒らなかったと思った。
> 
> 開発秘話：Googleでログインの機能を実装しようとしたが、審査が厳しすぎて余裕で間に合わなかった。

## MOSS chat

> 概要：エンジニアを意識したチャット系ウェブアプリケーション

> 開発の背景：ハッカソンに参加する際に作成したアプリ。掲示板ではフランクすぎるが、他サービスではエラー解決が主な内容となっており、ITエンジニア同士のオンラインでの気軽な情報交換などの交流がない。掲示板のように気軽に話題を提供し合える場所があることで、交流するまでのハードルを下げてかつITエンジニア同士のマッチングを図る。

> 開発期間：開発期間は2ヶ月
>
> 開発人数：6人
>
> 開発言語：Python（Flask）
>
> 役割：バックエンド
>
> GitHub：https://github.com/HackathonGteam/gteam
>
> 開発秘話：ハッカソン中にPCがぶっ壊れて、2週間私がタスクをこなせなかった。


</div></details>
<details><summary>スマートフォンアプリ -チーム開発</summary>

## cotabi
> 概要：　旅の行き先を現在地、予算、時間を基に提案してくれるスマホアプリ

> 開発の背景：ハッカソンに参加する際に作成したアプリ。従来小旅行をしようにも行先を決め事前にリサーチを行い計画を立てたりするなど、旅行の規模の大小にかかわらず手間がかかっていた。その課題を解決しようと、GoogleMapsAPI、YOLP、ChatGPTのAPIを用いて、ユーザに指定された条件（旅のテーマ、予算、使える時間）をもとに行先を提案してくるスマホアプリを作成した。

> 開発期間：開発期間は3週間
>
> 開発人数：6人
>
> 開発言語：JAVA(Spring Boot),JavaScript（React native）
>
> 役割：リーダー、バックエンド、フロントエンド
>
> GitHub：https://github.com/Hack-U-Nagoya-KAIT/cotabi
>
> 開発秘話：オフラインの発表会で、新幹線代を預けたメンバーが寝坊してしまった。

## SOMETAROKA（開発中）

> 概要：地方の垣根を越えて方言を体験できる次世代翻訳SNSアプリ

> 開発の背景：自分が大学リーダー兼PMOを務める4大学（法政大学、はこだて未来大学、京都橘大学、神奈川工科大学）が合同で3つのスマートフォンのアプリの作成を行うミライケータイプロジェクト2023で作成しているアプリケーション。翻訳とSNSのチャット機能を組み合わせて誰でもどこでも方言による会話を可能にする。
方言話者と非方言話者を方言で繋ぐSNSアプリ

> 開発期間：開発期間は1年（完成予定2024/03）
> 
> 開発人数：１０（プロジェクト全体で４０人前後）
>
> 開発言語：Python（Django）、JavaScript（React native）
>
> 役割：バックエンド,PMO,テックリード、インフラ
>
> GitHub：https://github.com/sometaroka
>
> 開発秘話：プロジェクト全体のリーダーがオフライン合宿の直前にとんだ。

</div></details>
<details><summary>その他の経験</summary>

#### 勉強会
> 大学内でKAITpiaという2023年度現在180人が所属している学生支援のボランティア団体のマネージャーをしており、その活動の一環で情報学部の相談者の対応を行っている。

#### 勉強会
> ソフトウェア工房という４０人弱が所属している工房の工房長をしており、今年度の前期は所属している1年生を対象に毎週ワークショップを主催した。

#### ハッカソン
> - RareTECHが主催するスクール内ハッカソンに3度参加
> - YahooJapan！が主催するHackUに２度のオフライン参加
> - MITが主催するMIT「MIT App Inventor」を用いるハッカソンに計3チームの参加

#### サークル運営
> 2023年度の前期の間、AniRingという「学生生活を彩るとともに、出会った人たちとの縁を大切にする」をモットーに活動を行う大学非公認のイベント団体を運営していた。（活動内容はボードゲーム会や飲み会、BBQなどの主催）

#### リーダー
> 公立はこだて未来大学、神奈川工科大学、法政大学、京都橘大学の4大学が連携し、未来の通説を創り出す「ミライ性」のあるサービスの企画・開発を行う「ミライケータイプロジェクト（PBL）」で大学リーダー兼PMO

</div></details>


<!--
**hitugihane/hitugihane** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
