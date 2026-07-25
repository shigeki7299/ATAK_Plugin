プロトタイプで作ったのもののため機種や機能試験を別途実施するのが望ましいです。<br>
ATAKの認証でうまく動作しない場合は、本説明の最後に対応するATAK 5.5.1があるので利用ください。<br>
内容により公開していないプラグインがあります。必要な方は作者に連絡してください。<br>
### <b>FO Tool</b><br>
 - 米軍教範、NATO標準化文書（公開文書）に基づく、目標設定、CAS要求、火力要求、任務設定、火砲計算（計算式調査中）、兵器リスト<br>
 - 目標解析において兵器諸元により、誤差、危険地域などを解析して表示できます。<br>
 - 目標管理や処置を行い、チームで共有が可能です<br>
<img width="2280" height="1080" alt="Screenshot_20260726_010433" src="https://github.com/user-attachments/assets/4bfe29de-527b-42ff-911c-873fe7ca6cee" />
<img width="2280" height="1080" alt="Screenshot_20260726_010404" src="https://github.com/user-attachments/assets/5258e98a-2dc7-4f67-8a49-34e9871a96d4" />
<img width="2280" height="1080" alt="Screenshot_20260726_010321" src="https://github.com/user-attachments/assets/76291eb5-0c12-453a-9375-9d179903dd82" />
<img width="2280" height="1080" alt="Screenshot_20260726_010233" src="https://github.com/user-attachments/assets/25cf9d6a-483d-4f46-887d-a90b56f00824" />


<br><br>

### <b>WindsAloft</b><br>
 - Open-Meteroから<b>気象情報を取得</b>できるプラグインを開発しました。<br>
 - Importを選択し、特定のアイコンを選択すると座標から適切なデータを取得します<br>
 - 気象情報は、WindsAloftなどで公開されている情報の元データから取得します。予測情報を表示することが可能です。<br>
 - 対地高度ＡＧＬと絶対標高ＭＧＬを切り替えて利用が可能です。<br>
 - 全世界の気象情報を取得できます。
<img width="1824" height="864" alt="screen" src="https://github.com/user-attachments/assets/0dc9b172-c3f7-4612-956c-bfd569840e77" />
<br><br>

### <b>MANET</b><br>
 - MANETを構成するプラグインです<br>
 - 現在対応無線 WIFI Awareに対応しており、AP不要<br>
 - すれ違い通信や、100m県内の小規模ネットワーク構成に適します<br>
 - 周囲のネットワークアダプタを検索してプラグイン相互で設定を行い接続を行います。<br>
 - グループ設定によりネットワークを分離することが可能です。<br>
 - 将来的にHALWなどの無線機にも対応できる設計のため必要に応じネットワークアダプターを追加できます。<br>
 - パスワードなどを用いて接続を制約することが可能です。<br>
 - セキュリティは、軍用暗号などを用いることが可能です詳細は問い合わせください。<br>
 - 画面はテスト用の画面ですので、修正する可能性があります。<br>
<img width="300" height="260" alt="ScreenShot2" src="https://github.com/user-attachments/assets/c1c7d20b-6fa3-4ae0-abf0-7d7a4e048e6e" />

   <br><br>

### <b>RF Design studio</b><br> 
 - 電波解析を行うプラグインです。<br>
 - 電界図、全系通信解析、対向通信、評定図が可能です。<br>
 
 <img width="912" height="432" alt="screen全系" src="https://github.com/user-attachments/assets/13c5e9eb-aca9-458d-9a4f-5412f8559fb3" />
<img width="912" height="432" alt="screen対向" src="https://github.com/user-attachments/assets/33b4e214-f9a1-4605-9f2a-966d9e34d06b" />
<img width="912" height="432" alt="screen電界図" src="https://github.com/user-attachments/assets/b378b7e5-1cb6-4296-a5b9-ae7f360ea714" />
<br><br>

### <b>Tactical suite（開発中）</b><br>
 - PDR測位、スマホセンサーから屋内の位置情報をAIで推定<br>
<br>
 音声認識によるメニュー、メッセージ入力機能（音声認識AI）<br>
 チャット受信時に自動読み上げ<br>
<br>
 - 生体情報の把握、警告機能及び送信<br>
 - 生体情報はCallsignの横に表示を行いますので、隊員間で状態把握が可能です。<br>
 - 胸部にEUDを装着した状態から姿勢を検出して状態を把握します。（IMU,気圧センサ等を使います）<br>
<br>




### <b>TAK Gateway（未試験）</b><br>
　- ネットワークの監視を行います。AIにより通信状況を監視し、最適通信手段を選択して接続します。
<br>
### <b>Compass2</b><br>
　- ランドナビゲーション用のコンパス
  - 位置情報と時刻に応じ変化する<b>真北（TN）</b>と磁北（MN）に対応
  - 表示のタップで、°→mil→radへ変更、AGL,MGL切り替え表示
  - 基準標高を手動で設定した場合は、気圧計で対地高度をシアンで表示します。
 <img width="912" height="432" alt="screen" src="https://github.com/user-attachments/assets/6c33b012-edb7-4d05-9b32-5d09add607e6" />
<br><br>
<HR>

======独立アプリケーション=====<br>
### <b>MANET Gateway</b><br>
 - localhostのデータを外部ネットワークへ中継を行う<br>
 - ATAK関連及びPushToTalkの情報共有へ対応<br>
 <img width="345" height="729" alt="Screenshot_20260720_024952" src="https://github.com/user-attachments/assets/e31e1554-895a-4124-9499-cb0ed43dd5d0" />

 <br>
### <b>QGroundContllre</b><br>
 - 無人機の操縦、飛行計画の転送、３D確認<br>
 - 無人機位置の共有<br>
 - ATAK連携が可能なGCS<br> 
 <br>

### <b>TAK_BEACON</b><br>
 - 位置情報送信するのみアプリです。<br>
 - 安価な端末にインストールし運用しすることで、物品改修や装置の位置を収集できるためIoTデバイスとして利用に適します。<br>
<img  width="345" height="729" alt="Screenshot_20260720_025358" src="https://github.com/user-attachments/assets/79cabaf5-62f3-46bf-b2fc-b7cff710c4af" />

 <br>
 
### <b>PushToTalk2</b><br>
 - 従来のPushToTalkと異なるアルゴリズムで構築してます。<br>
 - <b>最大１０つの系を登録して、同時に２系を取り扱いが可能です。（多所多系）</b><br>
 - 音声圧縮を従来の1/6以下にしていますので長距離通信にも対応します。<br>
 - 音声デバイス制御を再構築し、骨伝導のボタンでPTT制御できます。<br>
 - AndroidNSDの制御を全て削除して、相手の認証せずに音声を発信します。<br>
 - Mumbleサーバーへの接続は画面のみで処理はしないため、外部サーバーへの接続はしません。<br>
<img width="912" height="432" alt="screen" src="https://github.com/user-attachments/assets/830c98b2-c0ea-4f81-9463-e3b91910480c" />
<img width="30%" height="30%" alt="screen設定" src="https://github.com/user-attachments/assets/aa5a9d18-acfb-4144-9678-2b06e57f151f"  />

<br> 

### <b>ATAK-5.5.1　試験用</b><br>
　https://drive.google.com/file/d/1zqcIPbAIZJPkL2ov9_DKfRBCv0tna-pJ/view?usp=sharing<br>
