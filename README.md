# Agora_Web_SDK
Agora_Web_SDK
-----
【配信(入室)】
１．(host/audience)index.htmlを開く

２．(host/audience)APPIDを入力
３．(host/audience)Channelを入力（デフォルトdemo）
４．(host/audience)Roleを選択（主催者の場合host、受講者の場合audience）
５．(host/audience)Joinをクリック（入室）
hostのストリームをpublish
（audienceはしない）
-----
【受講者発言(リクエスト→許可)】
６．(audience)Requestをクリック
７．(host)Requestダイアログ取得（Are you sure…?）
８．(host)OKをクリック
audienceのストリームをinit&publish
-----
【(hostより)受講者発言をOFF】
９．(host)MUTEをクリック
audienceのストリームをunPublish
-----
【(hostより)受講者発言をON】
１０．(host)UNMUTEをクリック
audienceのストリームをpublish

