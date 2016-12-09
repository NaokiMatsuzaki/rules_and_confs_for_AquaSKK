# rules_and_confs_for_AquaSKK
Mac OS用のかな漢字変換プログラム[AquaSKK](https://github.com/codefirst/aquaskk)の補助ルールです。

##インストール
[AquaSKK プロジェクト::かな変換のカスタマイズ](http://aquaskk.osdn.jp/kana_rule.html "AquaSKK プロジェクト::かな変換のカスタマイズ")を参照の上、使用したいファイルを個人フォルダ (~/Library/Application Support/AquaSKK/) にコピーしてください。

##漢字直接入力用補助ルール
漢字直接入力[T-Code](http://openlab.jp/tcode/intro.html), [TUT-Code](http://www.geocities.jp/ken1noguchi/TUT-CODE/), [G-Code](http://homeposition.net/~m(as)m/index.php/G-Code)用の補助ルールです。設定の内容によって以下の三つのフォルダに分けています。

####entryinput-disabled
シフト+文字キーで見出し語入力に移らない設定です。

####entryinput-enabled
シフト+文字キーで見出し語入力に移る設定です(Qwerty, Colemakの0を除く)。

####prefix
他のかな入力やローマ字入力と併用するための設定で、キーボードカスタマイズツールの使用を前提としています([設定例](https://github.com/NaokiMatsuzaki/config_for_keyhac "config_for_keyhac"))。ローマ字定義のスペース以外の文字に#を前置しています。見出し語入力に移る文字は未設定です。必要に応じてキー割り当てを変更してください。

各設定につき、Qwerty配列版・Dvorak配列版・Colemak配列版の三つのファイルがあります。

###キー割り当て
####Qwerty, Colemak
トグルカナ変換    -    
ASCII モード遷移    ^    
全角英数モード遷移    |    
Abbrev モード遷移    ¥    
見出し語入力遷移    @

####Dvorak
トグルカナ変換    _    
ASCII モード遷移    +    
全角英数モード遷移    |    
Abbrev モード遷移    \     
見出し語入力遷移    =

JISキーボード用として作成しており、USキーボードでは未検証です。

##ローマ字入力用補助ルール
####Hepburn_system
ヘボン式ローマ字の撥音規則(mb/mm/mp)・促音規則(tch)を使って入力するための設定です。mmで「っ」が入力できなくなります。
