# My-Karabiner-Elements-config

[Karabiner-Elements](https://karabiner-elements.pqrs.org/)で、
好みのキーバインドを実現するためのjsonファイルです!　　

Karabiner-Json file to realize your favorite key binding with Elements!

# 設定準備(Setting preparation)
Karabiner-Elementsの「simple modification」で以下のように予めキーバインドを設定しておきます。

* left-ctrl →　commandキーとなるようにする
* Windows　→　optionキーとなるようにする


Set the key binding in advance as follows in "simple modification" of Karabiner-Elements.

* left-ctrl → Make it a command key
* Windows → Make it an option key

| From key | To key |
| --- | --- |
| left_command | left_option |
| left_control | left_command |

# 機能紹介(Function introduction)

## capskey-toggle-to-en-and-ja.json

capskeyで英語と日本語を切り替えるための設定ファイルです。  
Windowsのキーボードや、MacのUSキーボードで実現できるが、   
MacのJISキーボードでは実現できない不便さを解消します。  

This is a configuration file for switching between English and Japanese with capskey.  
It can be achieved with a Windows keyboard or a Mac US keyboard,  
It eliminates the inconvenience that cannot be realized with the JIS keyboard of Mac.  

## delete-files-with-deletekey.json

DeletekキーでFinder上のファイルを削除することができるようにするための設定ファイルです。  
Windowsのキーボードで実現できるが、Macのキーボードでは実現できない不便さを解消します。  
なお、この機能はFinderでのみ機能します。  

This is a configuration file that allows you to delete files in the Finder with the Deletek key.  
It eliminates the inconvenience that can be achieved with a Windows keyboard but not with a Mac keyboard.  
Please note that this feature only works in the Finder.  
　
## Screenlock-like-windows.json

OptionキーとLキーで画面ロックをかけることができます。  
作成者はキーボードのWindowsキーにOptionキーが割あたっていたのでそのようにし、  
Windowsと同じキーで画面ロックをかけることができるようにしました。
必要に応じてどのキーを押すかはカスタマイズしてください。  

You can lock the screen with the Option key and L key.  
The author assigned the Option key to the Windows key on the keyboard, so do so,  
The screen can be locked with the same key as Windows.  
Customize which key you press as needed.  


## use-chromeDevtool-like-windows.json

Chromeのデベロッパーツールをwindowsと同じCrtl+Shit+iで使うことができます。  

You can use Chrome's developer tools with the same Crtl + Shit + i as windows.

# 使い方(How to Use)

`~/.config/karabiner/assets/complex_modifications` にファイルを置いて`Complex Modifications`から有効化


Place the file in `~/.config/karabiner/assets/complex_modifications` and enable it from` Complex Modifications`

# Reference
[Karabiner-Elementsで英数/かなの切り替えをトグルにしてみた。](https://yamaimo.hatenablog.jp/entry/2018/01/14/200000)  
[快適キーボード操作のためのキーカスタマイズ ～Mac編～](https://knowledge.sakura.ad.jp/23355/)
