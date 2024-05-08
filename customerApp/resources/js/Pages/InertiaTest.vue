<script setup>
import { Link } from "@inertiajs/inertia-vue3";
</script>

<template>
<p>てすと</p>
<a href="/">テスト</a><br>
<Link href="/">リンク</Link><br>
<Link :href="route('inertia.index')">名前付きルート</Link>
</template>