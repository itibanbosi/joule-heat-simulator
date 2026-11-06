# 電子くんとジュール熱

[シミュレーションを開く](https://itibanbosi.github.io/joule-heat-simulator/)

抵抗と電流・電圧による発熱の違いを、○の流れと赤い光で比べるHTML教材です。

## 使い方

「比較する条件」で定電流／定電圧を切り替えます。起動時は定電流です。上側の抵抗は1 Ω、下側は1～8 Ωで変更できます。

- **定電流**：上下に同じ電流を流します。同じ数の○が同じ速さで移動し、抵抗が大きいほど発熱の電力 P = I²R が大きくなります。
- **定電圧**：上下に同じ電圧をかけます。I = V/R に従い、下側の抵抗を増やすと流れが遅くなります。発熱の電力 P = V²/R も小さくなります。
- スライダーで電流（1～5 A）または電圧（1～5 V）を設定します。
- 「一時停止／再生」で止めたり動かしたりできます。「最初から」は条件を保って流れを初期化します。

## 数値と模型の見方

初期値は定電流2 A・下側5 Ωです。上側4 W、下側20 Wです。同じ条件で定電圧2 Vにすると、上側2 A・4 W、下側0.4 A・0.8 Wとなります。

○は同じ密度で並び、その通過頻度を電流に対応させています。赤い光は物質へのエネルギーの伝達を表す定性的な表現です。電子の実際の速度・衝突回数・温度を再現するものではありません。Wは電力（1秒あたりの熱量）であり、一定時間t秒の熱量は Q = I²Rt（J）です。

## 起動方法

公開URLをブラウザーで開くだけで利用できます。ダウンロードしたindex.htmlを直接開くこともできます。外部ライブラリは不要です。

## License

MIT License — Copyright (c) 2026 itibanbosi.
改変・再配布・商用利用ができます。配布時は著作権表示とLICENSE全文を含めてください。

## 日本語・English

右上の「表示言語 / Language」で日本語と英語を切り替えます。初期表示は日本語です。切り替えても比較条件や再生状態は変わりません。詳しい説明は画面下の「図の見方・説明」から開けます。PCでは画面の高さに合わせて図を調整し、狭い画面では読みやすさを保ってスクロールできます。

Use the language selector at the top right to switch between Japanese and English. All controls, diagram labels and explanations are translated. Current settings and playback state are preserved. Choose constant current or constant voltage, then adjust the lower resistance and current/voltage sliders. Heating power is P = I²R; under constant voltage, P = V²/R. Open “How to read this model” for details. MIT licensed.

## 実際のジュール熱との違い

実際のジュール熱の仕組みは、このアニメーションとは異なります。金属では、電場によって電子がエネルギーを受け取り、格子の振動などとの相互作用を通して、そのエネルギーが物質に伝わって熱になります。電子が図の障害物にぶつかり、摩擦で熱を出すという仕組みではありません。障害物・○の動き・赤い光は、抵抗・電流・発熱の関係を理解するための模式表現です。実際の電子の速さ・衝突回数・温度を再現していません。

Actual Joule heating works differently from this animation. In a metal, electrons gain energy from the electric field and transfer it to the material through interactions with lattice vibrations and other scattering processes. Heat is not produced by electrons rubbing against the pictured obstacles. The obstacles, moving circles and red flashes are schematic representations of resistance, current and heating power. They do not reproduce actual electron speeds, collision counts or temperatures.
