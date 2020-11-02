# LinkTestSwift
LinkKitをSwiftで使うテスト

## TL;DR

正直、Obj-Cで書いてったほうが早いしサンプルも参考になるので、こっちは無理してやる必要があるのか微妙なところなんだけど興味があるので少しずつやってみる。現状ではBridging Headerを使ったLinkKitの読み込みが出来ただけ、の状態。Bridging Headerを作成するにはCocoa Touch Classじゃないと作成できないのでそこが注意（こちらが参考になった＞https://akabeko.me/blog/2020/02/google-analytics-with-xcode-11-swift/ ）。またただimport <ABLLink.h>をするだけだと、unknown type name 'bool'というエラーになるので、<stdbool.h＞もimportする。

