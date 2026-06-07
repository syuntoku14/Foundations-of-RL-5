---
maxDepth: 1
layout: default
---

<Toc />

---
hideInToc: true
---

## 中心極限定理

<br>

<div style="border: 2px solid #000; padding-top: 1px; padding-left: 10px; margin-top: 5px;">

MDPの情報が全部わかっている場合に$\pi^\star$を求める問題を**プランニング問題**と呼ぶ．\
つまり，$(\mathcal{S}, \mathcal{A}, P, r, \mu)$がわかっている場合に$\pi^\star$を**計算する**問題．

これまでの講義で，プランニング問題を解く様々なアルゴリズムを学んできた．\
価値反復法，方策反復法，方策勾配法，線型計画法…

</div>

<v-click>

<div style="border: 2px solid #000; padding-top: 1px; padding-left: 10px; margin-top: 5px; background-color: #ffffe0;">

しかし，現実の意思決定問題では$P$や$r$がわからないことが多い．

例：歪んだサイコロを振ってみよう．目が出る確率は最初わからない．何度も振ってみて，どの目が出やすいかを推定する必要がある．

**$P, r$がわからない場合** に$\pi^\star$を求める問題を**強化学習問題**と呼ぶ．

</div>

</v-click>

<span style="border: 2px solid #000; border-radius: 10px; padding: 5px 10px; background-color: #ffffe0; display: inline-block; position: absolute; top: 85%; left: 10%;">
プランニング問題
</span>

<Arrow x1="260" y1="490" x2="400" y2="490" />
<div style="position: absolute; top: 85%; left: 28%; text-align: center; font-size: 0.7em;">
サンプル近似（探索）
</div>

<span style="border: 2px solid #000; border-radius: 10px; padding: 5px 10px; background-color: #ffffe0; display: inline-block; position: absolute; top: 85%; left: 42%;">
強化学習
</span>

<Arrow x1="520" y1="490" x2="670" y2="490" />
<div style="position: absolute; top: 85%; left: 56%; text-align: center; font-size: 0.7em;">
関数近似 （深層）
</div>

<span style="border: 2px solid #000; border-radius: 10px; padding: 5px 10px; background-color: #ffffe0; display: inline-block; position: absolute; top: 85%; left: 70%;">
深層強化学習
</span>
