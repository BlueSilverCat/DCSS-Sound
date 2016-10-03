# DCSS-Sound
Dungeon Crawl Stone Soupe用のサウンド設定ファイル  
ログを見なくても状況が判別できるようにしたくて作成始めました  
まだまだ完璧には程遠いです  

# 使い方
1. sound.zipを解凍してください
2. 解凍して出来たsoundディレクトリとsound.txtを、crawl.exeと同じ場所においてください  

# カスタマイズ
force_more_messageを使用していますので、オリジナルよりも--More--メッセージが表示されます。  
(--More--が表示されるとEnterかSpaceを押さないとゲームが進みません)  
要らないようでしたら削除してください  
ただし、それによって聞こえなくなるサウンドが出てきてしまいます  

sound.txtの最初の方にある
```
FMM0 := force_more_message
FMM1 := force_more_message
#FMM2 := force_more_message
#FMM3 := force_more_message
#FMM4 := force_more_message
#FMMT := force_more_message
```
を以下のようにコメント全てコメントアウトすればforce_more_messageは解除されます  
```
#FMM0 := force_more_message
#FMM1 := force_more_message
#FMM2 := force_more_message
#FMM3 := force_more_message
#FMM4 := force_more_message
#FMMT := force_more_message
```
