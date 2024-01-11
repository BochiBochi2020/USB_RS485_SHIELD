# USB_RS485_SHIELD
JMRIのCMRI NodeへRS485を通して接続するためのArduino shieldです。 RS485の通信は、独自仕様のRJ45のコネクタを使用しています。 
現在、全面的に見直しを行っています。
主な変更点は以下となります。
* USBの接続は、micro USBに変更。
* DC-Jackから、12Vの電源を取得
* 12Vは、arduino shieldのVinへ供給

USB Hubは市販のものが使えますが、好みに応じて別途USB Hub shieldも
設計しています。
また、CMRIのノードとして、keypad、在線センサ/列車センサー、ポイント制御及び
信号機を鋭意作成中です。

/以上/
