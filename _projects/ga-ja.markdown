---
layout: project
title: "成長しすぎたプロダクトのインタラクション再設計"
company: Vyond
featured: true
order: 1
date: 1999-05-02 00:00:00
project-date: "2014 – 2018"
description: "Vyondのアニメーションツールは急速に成長した。成長しすぎた。ベータテストで露わになったのは、機能ごとには動くが、実際の使用では破綻する製品だった。ひとつのインタラクションパターンがそれを変えた。"
teaser-image: /assets/img/ga/teaser.png
screens: /assets/img/ga/screens.png
tags: [情報アーキテクチャ, インタラクションデザイン, ユーザーリサーチ]
lang: ja
---

<!-- Hero Section -->
<div class="full-width-section" style="background-color: #EDEFF2;">
  <div class="container">
    <div class="d-flex justify-content-between align-items-baseline project-lang-row">
      <h1>{{ page.title }}</h1>
      <a href="/projects/ga.html" class="lang-switch-link">English</a>
    </div>
    <p class="lead" style="max-width: 640px;">{{ page.description }}</p>
    <div class="py-4">
      <div style="background-color: #9BDEA8; border-radius: 8px; padding: 2rem;">
        <!-- Device frame -->
        <div style="background: #1c1c1e; border-radius: 10px; padding: 14px 14px 28px 14px; position: relative; box-shadow: 0 2px 12px rgba(0,0,0,0.3);">
          <div style="width: 6px; height: 6px; background: #3a3a3a; border-radius: 50%; margin: 0 auto 10px;"></div>
          <video class="img-fluid" autoplay muted loop playsinline style="border-radius: 4px; display: block;">
            <source src="/assets/img/ga/color-demo.mp4" type="video/mp4">
          </video>
        </div>
      </div>
    </div>
    <hr class="project-meta-rule">
    <div class="project-meta-grid">
      <div>
        <div class="meta-label">役割</div>
        <p class="meta-value">シニアUXデザイナー</p>
      </div>
      <div>
        <div class="meta-label">チーム</div>
        <p class="meta-value">デザイン、エンジニアリング、プロダクト</p>
      </div>
    </div>
  </div>
</div>

<!-- Context -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">背景</h3>
    <p>Vyondに入社したのは2014年。デザイナー3名、社員約30名、香港・台湾・サンフランシスコをまたぐチームだった。4年間で毎年ほぼ倍増する組織の成長とともに、スケールに耐えるデザインプロセスとパターンの構築を担った。</p>
    <p>アプリは移行ではなく、ゼロから作り直されていた。スピードを優先したため、デザインチームは機能ごとの小チームに分かれた。それぞれが合理的な判断をしていた。ただし、横断的な視点を持つ人がいなかった。プライベートベータを新規ユーザーとパワーユーザーで実施したとき、それは明らかになった。</p>
    <p>製品はブラウザベースのアニメーション動画ツールで、非デザイナーがプロ品質の動画を作れる。多くのFortune 500企業に使われていた。その規模感はこんな感じだ：</p>
    <div class="mt-4" style="border: 1px solid #e0e0e0; border-radius: 8px; padding: 1rem 1.25rem;">
      <div class="row mb-2">
        <div class="col-6 col-md-3 mb-3">
          <p class="card-tags mb-1">シーン</p>
          <p style="font-size: var(--text-sm); opacity: 0.7; line-height: 1.6;">背景・カメラ・長さ・トランジション</p>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <p class="card-tags mb-1">キャラクター</p>
          <p style="font-size: var(--text-sm); opacity: 0.7; line-height: 1.6;">アクション・表情・口パク・音声</p>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <p class="card-tags mb-1">エフェクト</p>
          <p style="font-size: var(--text-sm); opacity: 0.7; line-height: 1.6;">グループ・モーション・マスキング・フィルター</p>
        </div>
        <div class="col-6 col-md-3 mb-3">
          <p class="card-tags mb-1">アセット＆出力</p>
          <p style="font-size: var(--text-sm); opacity: 0.7; line-height: 1.6;">小道具・テキスト・音楽・テンプレート・テーマ</p>
        </div>
      </div>
      <details style="border-top: 1px solid #e0e0e0; padding-top: 1rem;">
        <summary style="cursor: pointer; font-size: var(--text-sm); color: var(--text-muted, #666); user-select: none;">全体マップを見る →</summary>
        <img src="/assets/img/ga/structure.png" class="rounded mt-3" style="max-width: 60%; display: block; margin: 0 auto;" alt="Vyond動画の全体構造">
        <p class="figure-caption text-center mt-2">ひとつひとつが機能、そして機能ごとに独自のインタラクションパターンがあった</p>
      </details>
    </div>
  </div>
</div>

<!-- People -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">ユーザー</h3>
    <p>再設計したアプリのベータリリースが近づくにつれ、テストでふたつの異なる失敗パターンが浮かび上がってきた。新規ユーザーと、経験豊富なユーザー、それぞれに。</p>
    <div class="row mt-4 mb-2">
      <div class="col-sm-6 mb-4">
        <div class="persona-card persona-card--newbie">
          <div class="d-flex align-items-start gap-3 mb-3">
            <img src="/assets/img/ga/persona-newbie.png" class="persona-avatar" alt="新規ユーザー">
            <div class="speech-bubble flex-grow-1">「少し混乱してしまいました…またいつか試してみます」</div>
          </div>
          <p class="persona-type">新規ユーザー</p>
          <p class="persona-body">トライアルで登録したばかり。とにかく一本だけ動画を作りたい。選択肢が多すぎて、どこから始めればいいかわからない。やる気があっても、始める前に挫折しやすい。</p>
        </div>
      </div>
      <div class="col-sm-6 mb-4">
        <div class="persona-card persona-card--poweruser">
          <div class="d-flex align-items-start gap-3 mb-3">
            <img src="/assets/img/ga/persona-champion.png" class="persona-avatar" alt="パワーユーザー">
            <div class="speech-bubble flex-grow-1">「レガシーとはかなり違う画面ですね…キャラクターに話させようとしてるんですが、どこをクリックすればいいのかわからなくて」</div>
          </div>
          <p class="persona-type">パワーユーザー</p>
          <p class="persona-body">チーム全体の動画を大量に制作している。やりたいことは明確で、ツールには邪魔してほしくない。パネルごとにパターンが違うせいで、毎回操作を覚え直す羽目になる。</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Problem -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">課題</h3>
    <p>テストを通じて、製品全体に一貫した混乱のパターンが見えてきた。その一部：</p>
    <img src="/assets/img/ga/panel-before-jp.png" class="img-fluid rounded mt-3" alt="再設計前のアセットパネル">
  </div>
</div>

<!-- Goals -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">ゴール</h3>
    <p>再設計は、まったく異なるふたりのユーザーに同時に応える必要があった。初めてアプリを開く人と、何年も使い込んできた人。どちらかを犠牲にしない解決策が求められた。</p>
    <ol>
      <li><strong>新規ユーザーの発見性</strong>、迷わず探索でき、自信を持って短い動画を完成できる</li>
      <li><strong>パワーユーザーのスピード</strong>、使い慣れたユーザーはやりたいことがわかっている。ツールは邪魔しない</li>
    </ol>
  </div>
</div>

<!-- Approach -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">アプローチ</h3>
    <p>製品内のすべてのアセットタイプに共通する流れがあった。<em>ブラウズ → 選択 → 適用 → カスタマイズ</em>。解決策は、この流れをベースにしたプログレッシブディスクロージャーパターン、「ツールボックス」と呼んだものを、すべてのパネルに一貫して適用することだった：</p>
    <ul>
      <li><strong>クイックアクセス</strong>、ブックマークしたアイテムをすぐに表示</li>
      <li><strong>最近使用したもの</strong>、繰り返し作業のショートカット</li>
      <li><strong>カテゴリ</strong>、発見のための整理されたブラウジング</li>
      <li><strong>カスタム</strong>、ブランドアセットやアップロードしたコンテンツ</li>
    </ul>
    <p>新規ユーザーはカテゴリで探索する。パワーユーザーは最近使用したものを使い続ける。エンタープライズチームはカスタムでブランドの一貫性を保つ。ひとつのパターン、三つのメンタルモデル。</p>
  </div>
</div>

<!-- Final design -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">デザイン</h3>
    <img src="/assets/img/ga/solution.png" class="img-fluid rounded mb-4" alt="最終的なアセットパネルデザイン">
    <p class="figure-caption text-center mb-4">キャラクター、カテゴリ、テキスト、オーディオパネルに適用されたツールボックスパターン</p>
    <p>変わったのはUIだけではない。期待値が変わった。ツールの新しい部分に出会ったとき、ユーザーはすでにそのパターンを別の場所で学んでいる。</p>
  </div>
</div>

<!-- Outcome -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">成果</h3>
    <div class="row mb-4">
      <div class="col-md-4 mb-4">
        <p class="persona-type">新規ユーザー</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">チュートリアルなしで、どのパネルも操作できるようになった。パターンが転用できた。</p>
      </div>
      <div class="col-md-4 mb-4">
        <p class="persona-type">パワーユーザー</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">一貫したパターンにより、毎回の覚え直しがなくなった。クイックアクセスと最近使用したものが、求めていたスピードを実現した。</p>
      </div>
      <div class="col-md-4 mb-4">
        <p class="persona-type">チーム</p>
        <p style="font-size: var(--text-sm); line-height: 1.7;">新機能を共通パターンに沿って構築できるようになり、リリースごとのデザインとエンジニアリングの負荷が減った。ツールボックスは私が退職した後も、何年も使われ続けている。</p>
      </div>
    </div>
    <p style="font-size: var(--text-sm); line-height: 1.7; opacity: 0.65;">問題は悪いデザインではなかった。共通のデザインがなかったことだ。チームが並行して素早く動くとき、個々の判断はそれぞれ合理的に見える。そのコストは、誰かがテストをして初めて、目に見えない形で積み上がっていたことに気づく。</p>
  </div>
</div>
