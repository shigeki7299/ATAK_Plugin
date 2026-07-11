プロトタイプで作ったのもののため機種や機能試験を別途実施するのが望ましいです。

###<b>WindsAloft-0.1</b><br>
 Open-Meteroから<b>気象情報を取得</b>できるアプリを開発しました。<br>
<img width="1824" height="864" alt="screen" src="https://github.com/user-attachments/assets/0dc9b172-c3f7-4612-956c-bfd569840e77" />

###<b>RF Design studio</b><br>
 電波解析を行うプラグインです。計算照合（機能テスト）がまだです。<br>
 <img width="912" height="432" alt="screen全系" src="https://github.com/user-attachments/assets/13c5e9eb-aca9-458d-9a4f-5412f8559fb3" />
<img width="912" height="432" alt="screen対向" src="https://github.com/user-attachments/assets/33b4e214-f9a1-4605-9f2a-966d9e34d06b" />
<img width="912" height="432" alt="screen電界図" src="https://github.com/user-attachments/assets/b378b7e5-1cb6-4296-a5b9-ae7f360ea714" />

###<b>Tactical suite（開発中）</b><br>
 ネットワークの監視、捜索、接続を行う。<br>
 ネットワークをMANETによる自動中継を行い、WIFI Direct等で利用が可能<br>
<br>
 PDR測位、スマホセンサーから屋内の位置情報をAIで推定<br>
<br>
 音声認識によるメニュー、メッセージ入力機能（音声認識AI）<br>
 チャット受信時に自動読み上げ<br>
<br>
 生体情報の把握、警告機能及び送信<br>
 生体情報はCallsignの横に表示を行いますので、隊員間で状態把握が可能です。<br>
 胸部にEUDを装着した状態から姿勢を検出して状態を把握します。（IMU,気圧センサ等を使います）<br>

###<b>gcs（開発中）</b><br>
 無人機の操縦、飛行計画の転送、３D確認<br>
 無人機位置の共有<br>


###<b>TAK Gateway（未試験）</b><br>
　ネットワークの監視を行います。AIにより通信状況を監視し、最適通信手段を選択して接続します。

###<b>Compass2</b><br>
　ランドナビゲーション用のコンパス
  位置情報と時刻に応じ変化する<b>真北（TN）</b>と磁北（MN）に対応
  表示のタップで、°→mil→radへ変更、AGL,MGL切り替え表示
  基準標高を手動で設定した場合は、気圧計で対地高度をシアンで表示します。
 <img width="912" height="432" alt="screen" src="https://github.com/user-attachments/assets/6c33b012-edb7-4d05-9b32-5d09add607e6" />

###<b>PushToTalk2-3.1.9</b><br>
 <b>最大１０つの系を登録して、同時に２系を取り扱いします（多所多系）</b><br>
 従来のPushToTalkと異なるアルゴリズムで構築してます。<br>
 音声圧縮を従来の1/6以下にしています。<br>
 音声デバイス制御を再構築し、骨伝導のボタンでPTT制御できます。<br>
 AndroidNSDの制御を全て削除して、相手の認証せずに音声を発信します。<br>
 Mumbleサーバーへの接続は画面のみで処理はしないため、外部サーバーへの接続はしません。<br>
<img width="912" height="432" alt="screen" src="https://github.com/user-attachments/assets/830c98b2-c0ea-4f81-9463-e3b91910480c" />
<img width="30%" height="30%" alt="screen設定" src="https://github.com/user-attachments/assets/aa5a9d18-acfb-4144-9678-2b06e57f151f"  />

 
###<b>ATAK-5.5.1　試験用</b><br>
　https://drive.google.com/file/d/1zqcIPbAIZJPkL2ov9_DKfRBCv0tna-pJ/view?usp=sharing<br>
