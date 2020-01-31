# はじめに

RxJSの明確な例、説明、およびリソース。

_By_ [_@btroncone_](https://twitter.com/BTroncone)

## 序章

[RxJS](https://github.com/ReactiveX/rxjs) は、現在の Web 開発で最もホットなライブラリの1つです。
イベントを処理するための強力で機能的なアプローチを提供し、
より多くのフレームワーク、ライブラリ、およびユーティリティへの統合ポイントを提供することで、
Rx を学習するケースはかつてないほど魅力的になりました。
これを[ほぼすべての言語](http://reactivex.io/languages.html)で知識を活用する機能と組み合わせて、
リアクティブプログラミングをしっかりと把握し、何が提供できるかは簡単に思えます。

**しかし...**

RxJS とリアクティブプログラミングの学習は[困難](https://twitter.com/hoss/status/742643506536153088)です。
多数の概念、大きな API サーフェス、および[命令型から宣言型](https://tylermcginnis.com/imperative-vs-declarative-programming/)への考え方の根本的な変化があります。
このサイトはこれらの概念を親しみやすくすること、例が明確で簡単に探求できることに焦点を当てており、
Web 上の最高の RxJS 関連資料への参照を提供しています。
目標は、[公式ドキュメント](http://reactivex.io/rxjs/)と既存の学習教材を補完すると同時に、
ハードルを解消し、問題点に取り組むための新しい新鮮な視点を提供することです。
Rx の学習は難しいかもしれませんが、努力する価値はあります。

[![Ultimate RxJS](https://drive.google.com/uc?export=view&id=1htrban3k3Z8CxiKwEV6bdmxW5Wu8xdWX)](https://ultimatecourses.com/courses/rxjs?ref=4)

### RxJS が初めてですか？

[RxJS Primer](/concepts/rxjs-primer.md) の生産性を高めるために必要なすべての重要な概念を理解してください！

## コンテンツ

#### Operators

OOperators は observables の背後にある馬力であり、
複雑な非同期タスクにエレガントで宣言的なソリューションを提供します。
このセクションにはすべての [RxJS operators](/operators/README.md)が含まれており、
明確で実行可能な例が含まれています。
該当する場合、各オペレーターの追加リソースおよびレシピへのリンクも提供されます。

##### Operator カテゴリー

- [Combination](/operators/combination/README.md)
- [Conditional](/operators/conditional/README.md)
- [Creation](/operators/creation/README.md)
- [Error Handling](/operators/error_handling/README.md)
- [Multicasting](/operators/multicasting/README.md)
- [Filtering](/operators/filtering/README.md)
- [Transformation](/operators/transformation/README.md)
- [Utility](/operators/utility/README.md)

**もしくは...**

[Complete listing in alphabetical order](/operators/complete.md)

#### Subject を理解する

Subject は、observer 間で単一の実行パスを共有する特別なタイプの Observable です。

- [概要](/subjects/README.md)
- [AsyncSubject](/subjects/asyncsubject.md)
- [BehaviorSubject](/subjects/behaviorsubject.md)
- [ReplaySubject](/subjects/replaysubject.md)
- [Subject](/subjects/subject.md)

#### コンセプト

Observables が裏でどのように機能するかについてしっかりとした基礎知識がなければ、
RxJS の多くが「魔法」のように感じるのは簡単です。
このセクションは、リアクティブプログラミングと Observable に慣れるために必要な主要な概念を固めるのに役立ちます。

- [RxJS Primer](/concepts/rxjs-primer.md)
- [Get started transforming streams with map, pluck, and mapTo](/concepts/get-started-transforming.md)
- [Time based operators comparison](/concepts/time-based-operators-comparison.md)
- [RxJS v5 -> v6 Upgrade](/concepts/rxjs5-6.md)

#### レシピ

RxJS を使用した一般的な使用例と興味深いソリューションのレシピ。

- [Alphabet Invasion Game](/recipes/alphabet-invasion-game.md)
- [Battleship Game](/recipes/battleship-game.md)
- [Breakout Game](/recipes/breakout-game.md)
- [Car Racing Game](/recipes/car-racing-game.md)
- [Catch The Dot Game](/recipes/catch-the-dot-game.md)
- [Click Ninja Game](/recipes/click-ninja-game.md)
- [Flappy Bird Game](/recipes/flappy-bird-game.md)
- [Game Loop](/recipes/gameloop.md)
- [Horizontal Scroll Indicator](/recipes/horizontal-scroll-indicator.md)
- [HTTP Polling](/recipes/http-polling.md)
- [Lockscreen](/recipes/lockscreen.md)
- [Matrix Digital Rain](/recipes/matrix-digital-rain.md)
- [Memory Game](/recipes/memory-game.md)
- [Mine Sweeper Game](/recipes/mine-sweeper-game.md)
- [Platform Jumper Game](/recipes/platform-jumper-game.md)
- [Progress Bar](/recipes/progressbar.md)
- [Save Indicator](/recipes/save-indicator.md)
- [Smart Counter](/recipes/smartcounter.md)
- [Stop Watch](/recipes/stop-watch.md)
- [Space Invaders Game](/recipes/space-invaders-game.md)
- [Swipe To Refresh](/recipes/swipe-to-refresh.md)
- [Tank Battle Game](/recipes/tank-battle-game.md)
- [Tetris Game](/recipes/tetris-game.md)
- [Type Ahead](/recipes/type-ahead.md)
- [Uncover Image Game](/recipes/uncover-image-game.md)

## 入門資料

RxJS とリアクティブプログラミングは初めてですか？ このサイトにあるコンテンツに加えて、
これらの優れたリソースは学習体験をすぐに始めるのに役立ちます！

#### カンファレンス

- [RxJS Live](https://www.rxjs.live/) - RxJSに焦点をあてたカンファレンス

#### Reading

- [RxJS Introduction](https://rxjs-dev.firebaseapp.com/guide/overview) -
  Official Docs

- [The Introduction to Reactive Programming You've Been Missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754) -
  André Staltz

- [RxJS: Observables, Observers and Operators Introduction](https://ultimatecourses.com/blog/rxjs-observables-observers-operators) -
  Todd Motto

#### ビデオ

- [Ultimate RxJS](https://ultimatecourses.com/courses/rxjs?ref=4) 💵 - Brian
  Troncone

- [Asynchronous Programming: The End of The Loop](https://egghead.io/courses/mastering-asynchronous-programming-the-end-of-the-loop) -
  Jafar Husain

- [What is RxJS?](https://egghead.io/lessons/rxjs-what-is-rxjs) - Ben Lesh
- [Creating Observable from Scratch](https://egghead.io/lessons/rxjs-creating-observable-from-scratch) -
  Ben Lesh

- [Introduction to RxJS Marble Testing](https://egghead.io/lessons/rxjs-introduction-to-rxjs-marble-testing)
  💵 - Brian Troncone

- [Introduction to Reactive Programming](https://egghead.io/courses/introduction-to-reactive-programming)
  💵 - André Staltz

- [Reactive Programming using Observables](https://www.youtube.com/watch?v=HT7JiiqnYYc&feature=youtu.be) -
  Jeremy Lund

#### エクササイズ

- [Functional Programming in JavaScript](http://reactivex.io/learnrx/) - Jafar
  Husain

#### ツール

- [Rx Marbles - Interactive diagrams of Rx Observables](http://rxmarbles.com/) -
  André Staltz

- [Rx Visualizer - Animated playground for Rx Observables](https://rxviz.com) -
  Misha Moroshko

- [Reactive.how - Animated cards to learn Reactive Programming](http://reactive.how) -
  Cédric Soulas

- [Rx Visualization - Visualizes programming with RxJS](https://fingerpich.github.io/rx-visualization/) -
  Mojtaba Zarei

_RxJS 4 に興味がありますか？ Check out_
[_Denis Stoyanov's_](https://github.com/xgrommx) _excellent_
[_eBook_](https://xgrommx.github.io/rx-book/)_!_

## 翻訳

- [简体中文](https://rxjs-cn.github.io/learn-rxjs-operators)

### 参照に関する注意

この GitBook に含まれるすべての参考資料は、無料と有料の両方があり、
RxJS を学習する際に非常に役立ちました。
含めるべきだと思う記事やビデオに出会った場合は、
トップメニューの _このページを編集_ リンクを使用してプルリクエストを送信してください。
あなたのフィードバックは大歓迎です！