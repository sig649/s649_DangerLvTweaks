理論上はたぶん動くよバージョン  
動作保証は全くできません  
分かる方だけお試しを

効能：危険度(Zone.DangerLv)に対して以下の処理をする（はず）  
最深到達層(EClass.player.stats.deepest)を参照して、それがベース危険度(Zone._dangerLv)＋lv加算(base.lv)より低ければlvの加算を行わない（はず）


TODO : ベース危険度は低いがlv加算が高い場合に危険度が低くなってしまう可能性に対応  
      ：デバッグログを出力しようとするとスパムになってしまう問題  
      ：*解決*//なぜかharmonyのzone.activateからログ出力しようとするとうまくいかない問題(
      別MOD
      )  
：DangerLvFixの調査
