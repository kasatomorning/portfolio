<template>
    <div class="lg:pl-[19.5rem]">
        <div class="max-w-3xl mx-auto pt-10 xl:max-w-none xl:ml-0 xl:pr-16">
            <div class="mx-auto max-w-sm my-[1rem] text-center">
                <h1
                    class="inline-block text-5xl sm:text-5xl font-extrabold text-slate-900 tracking-tight dark:text-slate-200">
                    Home</h1>
            </div>
            <h2 class="inline-block text-4xl sm:text-4xl relative border-none lg:-ml-2 lg:pl-2 m-2">自己紹介</h2>
            <p class="my-[0.3em]">理工情報生命学術院システム情報工学研究群（博士前期課程）情報理工学位プログラム1年次の笠島です。</p>
            <p class="my-[0.3em]">ネットワーク系の研究室に所属しています。</p>
            <h2 class="inline-block text-4xl sm:text-4xl relative border-none lg:-ml-2 lg:pl-2 m-2">資格</h2>
            <div class="p-4 mb-2 max-w-lg bg-white rounded-md shadow-lg">
                <p>2021年3月</p>
                <p class="text-gray-600">基本情報技術者試験 合格</p>
            </div>
            <div class="p-4 mb-2 max-w-lg bg-white rounded-md shadow-lg">
                <p>2022年12月</p>
                <p class="text-gray-600">応用情報技術者試験 合格</p>
            </div>
            <div class="p-4 mb-2 max-w-lg bg-white rounded-md shadow-lg">
                <p>2022年10月</p>
                <p class="text-gray-600">TOEIC 730点</p>
            </div>
            <h2 class="inline-block text-4xl sm:text-4xl relative border-none lg:-ml-2 lg:pl-2 m-2">経歴</h2>
            <div class="p-4 mb-2 max-w-lg bg-white rounded-md shadow-lg">
                <p>2017年4月~2020年3月</p>
                <p class="text-gray-600">渋谷教育学園渋谷高校</p>
            </div>
            <div class="p-4 mb-2 max-w-lg bg-white rounded-md shadow-lg">
                <p>2020年4月~</p>
                <p class="text-gray-600">筑波大学情報学群情報科学類</p>
            </div>
            <div class="p-4 mb-2 max-w-lg bg-white rounded-md shadow-lg">
                <p>2022年8月</p>
                <p class="text-gray-600">いい生活 短期インターン</p>
                <p class="text-gray-600 text-sm">TypeScript+Vue3を用いたWebアプリケーション作成</p>
            </div>
            <div class="p-4 mb-2 max-w-lg bg-white rounded-md shadow-lg">
                <p>2023年5月~8月</p>
                <p class="text-gray-600">いい生活 長期インターン</p>
                <p class="text-gray-600 text-sm">C#を用いたWPFアプリケーションの改良</p>
            </div>
            <div class="p-4 mb-2 max-w-lg bg-white rounded-md shadow-lg">
                <p>2023年12月~</p>
                <p class="text-gray-600">ドワンゴ 長期インターン</p>
                <p class="text-gray-600 text-sm">社内システムのバックエンドの運用・監視</p>
            </div>
            <h2 class="inline-block text-4xl sm:text-4xl relative border-none lg:-ml-2 lg:pl-2 m-2">趣味</h2>
            <ul role="list" class="list-inside list-disc">
                <li>
                    ゲーム
                    <ul class="list-disc list-inside space-y-0.3 pl-5">
                        <li>
                            VALORANT
                        </li>
                        <li>
                            Overwatch2
                        </li>
                    </ul>
                </li>
                <li>配信視聴</li>
            </ul>
        </div>
    </div>
</template>
<script setup lang="ts">
useHead({
    title:'Home'
})
</script>