# UDP Flood攻撃パケットの特徴

多量のUDPパケットを送られていることが確認できます．  
さらに，Timeの部分に注目すると，短時間で大量に送信されており，悪意のあるパケットを受信していることがわかります．

![](../img/pcap/udp/01.png)

以上のことから，UDPパケットを大量に送信し，サービスを妨害するUDP Flood攻撃を受けていることが特定できます．