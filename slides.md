---
title: タスクをアクション動詞で書くメリット
theme: seriph
highlight: atom-one-dark
accentColor: '#2563EB'        # Tailwind blue‑600
fontFamily: 'Inter'
transition: slide-left
background: 'https://source.unsplash.com/collection/94734566/1920x1080'
class: 'text-center'
---

<!-- 全体スタイル -->
<style>
.slidev-layout {
  background-color: #f9fafb; /* やわらかいグレー */
}

/* カード風ブロック */
.card {
  background: #ffffffcc;            /* 透過白 */
  backdrop-filter: blur(6px);
  border-radius: 1rem;
  box-shadow: 0 8px 16px rgba(0,0,0,0.08);
  padding: 1.25rem;
}

/* 図形のスタイル */
.box {
  border-radius: 0.5rem;
  padding: 0.75rem;
  margin: 0.5rem 0;
}

.arrow-box {
  position: relative;
  background: #fff;
  border: 2px solid #2563EB;
  border-radius: 0.5rem;
  padding: 0.75rem;
  margin: 0.5rem 0;
}

.arrow-box:after, .arrow-box:before {
  left: 100%;
  top: 50%;
  border: solid transparent;
  content: "";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
}

.arrow-box:after {
  border-color: rgba(255, 255, 255, 0);
  border-left-color: #fff;
  border-width: 10px;
  margin-top: -10px;
}

.arrow-box:before {
  border-color: rgba(37, 99, 235, 0);
  border-left-color: #2563EB;
  border-width: 13px;
  margin-top: -13px;
}

.step-box {
  background: #fff;
  border-left: 4px solid #2563EB;
  padding: 0.75rem;
  margin: 0.5rem 0;
}
</style>

## タスクをアクション動詞で書くメリット
<div class="mt-8 flex justify-center">
  <div class="relative w-64 h-64">
    <div class="absolute inset-0 bg-blue-100 rounded-full opacity-20"></div>
    <div class="absolute inset-4 bg-blue-200 rounded-full opacity-40 flex items-center justify-center">
      <div class="absolute inset-8 bg-blue-300 rounded-full opacity-60 flex items-center justify-center">
        <div class="text-center">
          <div class="text-xl font-bold text-blue-800">タスクを制する者が</div>
          <div class="text-2xl font-bold text-blue-900">仕事を制する</div>
        </div>
      </div>
    </div>
  </div>
</div>

---
layout: two-cols
---

# 主張：アクション動詞で書く

<div class="space-y-4">
  <div class="arrow-box">
    単なる書き方ではなく<b>思考法</b>
  </div>
  <div class="arrow-box">
    抽象的な名詞より<b>具体的な動詞</b>で
  </div>
  <div class="arrow-box">
    「脳内ツッコミ」で具体化すれば生産性が高まる
  </div>
</div>

::right::

<div class="flex h-full items-center justify-center">
  <div class="relative">
    <div class="w-48 h-48 bg-red-100 rounded-lg opacity-30 absolute -left-4 -top-4"></div>
    <div class="w-48 h-48 bg-blue-100 rounded-lg opacity-30 absolute -right-4 -bottom-4"></div>
    <div class="w-48 h-48 border-2 border-blue-500 rounded-lg bg-white p-4 relative">
      <div class="mb-2 font-bold text-red-500 line-through">会議の準備</div>
      <div class="font-bold text-blue-500">
        → 資料を3ページ作成し<br>
        → 参加者に事前送付し<br>
        → 会議室を予約する
      </div>
    </div>
  </div>
</div>

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# 1. アクション動詞の力

<div class="space-y-6">
  <div class="flex items-center">
    <div class="bg-red-100 border border-red-500 text-red-700 px-4 py-2 rounded w-32 text-center">
      検討する
    </div>
    <div class="mx-4 text-2xl">→</div>
    <div class="bg-green-100 border border-green-500 text-green-700 px-4 py-2 rounded w-48 text-center">
      3案を比較し選択する
    </div>
  </div>

  <div class="flex items-center">
    <div class="bg-red-100 border border-red-500 text-red-700 px-4 py-2 rounded w-32 text-center">
      確認する
    </div>
    <div class="mx-4 text-2xl">→</div>
    <div class="bg-green-100 border border-green-500 text-green-700 px-4 py-2 rounded w-48 text-center">
      テストして結果を記録する
    </div>
  </div>

  <div class="flex items-center">
    <div class="bg-red-100 border border-red-500 text-red-700 px-4 py-2 rounded w-32 text-center">
      Led
    </div>
    <div class="mx-4 text-2xl">→</div>
    <div class="bg-green-100 border border-green-500 text-green-700 px-4 py-2 rounded w-48 text-center">
      Orchestrated / Redesigned
    </div>
  </div>
</div>

---
layout: center
class: text-center
---

# 2. 脳内ツッコミのプロセス

```mermaid
graph LR
    A[A社へ連絡] --> B[下書き作成]
    B --> C[上司確認]
    C --> D[承認後送信]
    style A fill:#f9d6d6,stroke:#e74c3c,color:#e74c3c,font-weight:bold
    style B fill:#d6e9f9,stroke:#3498db,color:#3498db,font-weight:bold
    style C fill:#d6e9f9,stroke:#3498db,color:#3498db,font-weight:bold
    style D fill:#d6e9f9,stroke:#3498db,color:#3498db,font-weight:bold
```

<div class="flex justify-center items-center space-x-2 mb-8">
  <div class="bg-gray-100 p-4 rounded-lg text-center w-64 border border-gray-300 shadow-sm">
    <div class="text-xl font-bold text-gray-800">A社へ連絡</div>
    <div class="text-sm text-gray-600">抽象的・曖昧</div>
  </div>
  <div class="text-4xl text-blue-500">→</div>
  <div class="p-2 bg-blue-50 rounded-lg">
    <div class="text-center">
      <div class="text-xl font-bold text-blue-600">脳内ツッコミ</div>
      <div class="text-sm italic text-blue-700">"具体的には何をするの？"</div>
    </div>
  </div>
  <div class="text-4xl text-blue-500">→</div>
  <div class="bg-green-100 p-4 rounded-lg text-center w-64 border border-green-300 shadow-sm">
    <div class="text-xl font-bold text-green-800">具体的なステップ</div>
    <div class="text-sm text-green-700">明確なアクション</div>
  </div>
</div>

<div class="grid grid-cols-3 gap-6">
  <div class="step-box">
    <div class="font-bold text-blue-700">1. 下書き作成</div>
    <div class="text-sm">A社X様向けに提案内容を整理</div>
  </div>
  <div class="step-box">
    <div class="font-bold text-blue-700">2. 上司確認</div>
    <div class="text-sm">内容と表現の適切さを確認</div>
  </div>
  <div class="step-box">
    <div class="font-bold text-blue-700">3. 承認後送信</div>
    <div class="text-sm">修正を反映させ期限内に送信</div>
  </div>
</div>

---
layout: center
---

# 3. 生産性向上の3つの理由

<div class="grid grid-cols-3 gap-12">
  <div class="flex flex-col items-center">
    <div class="w-24 h-24 rounded-full bg-blue-100 flex items-center justify-center mb-4">
      <div class="text-4xl text-blue-700">💪</div>
    </div>
    <div class="font-bold text-xl text-center text-blue-800">意志力の節約</div>
    <div class="text-center text-sm mt-2">
      <div class="flex items-center">
        <div class="w-3 h-3 rounded-full bg-green-500 mr-2"></div>
        判断に悩む時間を削減
      </div>
      <div class="flex items-center mt-1">
        <div class="w-3 h-3 rounded-full bg-green-500 mr-2"></div>
        実行のハードルが下がる
      </div>
    </div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-24 h-24 rounded-full bg-green-100 flex items-center justify-center mb-4">
      <div class="text-4xl text-green-700">⏱️</div>
    </div>
    <div class="font-bold text-xl text-center text-green-800">正確な見積り</div>
    <div class="text-center text-sm mt-2">
      <div class="flex items-center">
        <div class="w-3 h-3 rounded-full bg-green-500 mr-2"></div>
        隠れた工数が明確化
      </div>
      <div class="flex items-center mt-1">
        <div class="w-3 h-3 rounded-full bg-green-500 mr-2"></div>
        待ち時間の把握が容易
      </div>
    </div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-24 h-24 rounded-full bg-purple-100 flex items-center justify-center mb-4">
      <div class="text-4xl text-purple-700">🔄</div>
    </div>
    <div class="font-bold text-xl text-center text-purple-800">明確な共有</div>
    <div class="text-center text-sm mt-2">
      <div class="flex items-center">
        <div class="w-3 h-3 rounded-full bg-green-500 mr-2"></div>
        役割の明確化
      </div>
      <div class="flex items-center mt-1">
        <div class="w-3 h-3 rounded-full bg-green-500 mr-2"></div>
        関係者の準備が容易に
      </div>
    </div>
  </div>
</div>

---
layout: image-right
image: https://source.unsplash.com/xkArbdUcUeE/1920x1080
---

# 4. チームでの効果

<div class="mb-6">
  <div class="flex items-center mb-4">
    <div class="w-12 h-12 rounded-full bg-blue-100 flex items-center justify-center mr-4">
      <div class="text-2xl">🔄</div>
    </div>
    <div>
      <div class="font-bold text-blue-800">スムーズな調整</div>
      <div class="text-sm text-blue-600">依頼の意図と行動が明確化</div>
    </div>
  </div>
  
  <div class="flex items-center mb-4">
    <div class="w-12 h-12 rounded-full bg-yellow-100 flex items-center justify-center mr-4">
      <div class="text-2xl">💡</div>
    </div>
    <div>
      <div class="font-bold text-yellow-800">効果的なフィードバック</div>
      <div class="text-sm text-yellow-600">具体的タスクへの適切な助言</div>
    </div>
  </div>
  
  <div class="flex items-center">
    <div class="w-12 h-12 rounded-full bg-green-100 flex items-center justify-center mr-4">
      <div class="text-2xl">📈</div>
    </div>
    <div>
      <div class="font-bold text-green-800">生産性の向上</div>
      <div class="text-sm text-green-600">チーム全体のスループット改善</div>
    </div>
  </div>
</div>

```mermaid
graph LR
  A[明確なタスク] --> B[効率的な実行]
  B --> C[迅速なフィードバック]
  C --> D[チーム生産性向上]
  D --> A
  style A fill:#e6f7ff,stroke:#1890ff,color:#1890ff,font-weight:bold
  style B fill:#f6ffed,stroke:#52c41a,color:#52c41a,font-weight:bold
  style C fill:#fff7e6,stroke:#fa8c16,color:#fa8c16,font-weight:bold
  style D fill:#f9f0ff,stroke:#722ed1,color:#722ed1,font-weight:bold
```

---
layout: center
---

# 5. 幅広い応用範囲

<div class="flex justify-center">
  <div class="relative w-96 h-96">
    <div class="absolute inset-0 bg-blue-50 rounded-full">
      <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-32 h-32 bg-blue-100 rounded-full flex items-center justify-center">
        <div class="text-blue-800 font-bold text-center">アクション<br>動詞</div>
      </div>
      <div class="absolute top-8 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-green-100 px-4 py-2 rounded-lg shadow-md">
        <div class="text-green-800 font-bold">個人のタスク管理</div>
      </div>
      <div class="absolute top-1/2 right-8 transform translate-y-1/2 bg-purple-100 px-4 py-2 rounded-lg shadow-md">
        <div class="text-purple-800 font-bold">チームへの依頼</div>
      </div>
      <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 translate-y-1/2 bg-yellow-100 px-4 py-2 rounded-lg shadow-md">
        <div class="text-yellow-800 font-bold">企画書・提案書</div>
      </div>
      <div class="absolute top-1/2 left-8 transform -translate-y-1/2 bg-red-100 px-4 py-2 rounded-lg shadow-md">
        <div class="text-red-800 font-bold">議事録・報告書</div>
      </div>
      <div class="absolute top-1/4 right-1/4 bg-indigo-100 px-4 py-2 rounded-lg shadow-md">
        <div class="text-indigo-800 font-bold">プロジェクト計画</div>
      </div>
      <div class="absolute bottom-1/4 left-1/4 bg-pink-100 px-4 py-2 rounded-lg shadow-md">
        <div class="text-pink-800 font-bold">業務マニュアル</div>
      </div>
    </div>
  </div>
</div>

---
layout: two-cols
---

# Before / After

<div class="space-y-8">
  <div class="bg-red-50 p-4 rounded-lg border-l-4 border-red-400">
    <div class="text-xl font-bold text-red-600">Before（曖昧）</div>
    <div class="mt-4 space-y-2">
      <div class="bg-white p-2 rounded shadow-sm border border-gray-200 text-gray-800 font-medium">〇〇について検討</div>
      <div class="bg-white p-2 rounded shadow-sm border border-gray-200 text-gray-800 font-medium">A社へ連絡</div>
      <div class="bg-white p-2 rounded shadow-sm border border-gray-200 text-gray-800 font-medium">資料作成</div>
      <div class="bg-white p-2 rounded shadow-sm border border-gray-200 text-gray-800 font-medium">会議の準備</div>
    </div>
    <div class="mt-4 text-sm text-red-600">
      ⚠️ 抽象的で実行が難しい<br>
      ⚠️ 工数見積もりが困難<br>
      ⚠️ 何をしたか不明確
    </div>
  </div>
</div>

::right::

<div class="space-y-8 pt-12">
  <div class="bg-green-50 p-4 rounded-lg border-l-4 border-green-400">
    <div class="text-xl font-bold text-green-600">After（具体的）</div>
    <div class="mt-4 space-y-2">
      <div class="bg-white p-2 rounded shadow-sm border border-green-200 text-gray-800 font-medium">〇〇を整理し<b class="text-green-700">スライド1枚にまとめる</b></div>
      <div class="bg-white p-2 rounded shadow-sm border border-green-200 text-gray-800 font-medium">A社X様へメールを<b class="text-green-700">下書き→上司確認→送信</b></div>
      <div class="bg-white p-2 rounded shadow-sm border border-green-200 text-gray-800 font-medium">データを<b class="text-green-700">グラフ化し5ページの報告書を作成</b></div>
      <div class="bg-white p-2 rounded shadow-sm border border-green-200 text-gray-800 font-medium">資料を準備し<b class="text-green-700">参加者に事前共有</b>→会議室を予約</div>
    </div>
    <div class="mt-4 text-sm text-green-600">
      ✅ すぐに実行できる<br>
      ✅ 正確な見積もりが可能<br>
      ✅ 目に見える成果が明確
    </div>
  </div>
</div>

---
layout: center
class: text-center
---

<h1 class="bg-white bg-opacity-80 px-6 py-3 rounded-lg shadow-md inline-block text-blue-800 border-b-4 border-blue-500 mb-6">まとめ</h1>

<div class="grid grid-cols-2 gap-8 mt-8">
  <div class="relative">
    <div class="absolute -inset-0.5 bg-gradient-to-r from-blue-500 to-green-500 rounded-lg blur"></div>
    <div class="relative bg-white rounded-lg p-6 shadow-lg">
      <div class="w-16 h-16 rounded-full bg-blue-100 flex items-center justify-center mx-auto mb-4">
        <div class="text-3xl">✍️</div>
      </div>
      <div class="font-bold text-lg text-center mb-2 text-blue-800">タスクの書き方の改善</div>
      <div class="text-md text-gray-700">
        <span class="font-medium">アクション動詞</span>で具体的に書き<br>
        <span class="font-medium">「脳内ツッコミ」</span>で細分化する
      </div>
    </div>
  </div>
  
  <div class="relative">
    <div class="absolute -inset-0.5 bg-gradient-to-r from-green-500 to-purple-500 rounded-lg blur"></div>
    <div class="relative bg-white rounded-lg p-6 shadow-lg">
      <div class="w-16 h-16 rounded-full bg-green-100 flex items-center justify-center mx-auto mb-4">
        <div class="text-3xl">🚀</div>
      </div>
      <div class="font-bold text-lg text-center mb-2 text-green-800">得られる効果</div>
      <div class="text-md text-gray-700">
        <span class="font-medium">意志力の節約</span><br>
        <span class="font-medium">時間見積りの精度向上</span><br>
        <span class="font-medium">チームコミュニケーション円滑化</span>
      </div>
    </div>
  </div>
</div>

<div class="mt-8 text-xl font-bold text-white bg-blue-600 px-6 py-2 rounded-lg shadow-md inline-block">
  「タスクを制する者が仕事を制する」
</div>
