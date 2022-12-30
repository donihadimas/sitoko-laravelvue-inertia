<template>
    <main>
        <header>
            <Link href="/dashboard">Dashboard</Link> |
            <Link href="/sales-transaction">Transaksi Penjualan</Link> |
            <Link href="/sales-list">Data Transaksi</Link>
        </header>
        <article>
            <slot />
        </article>
    </main>
</template>

<script>
import { Link } from "@inertiajs/inertia-vue3";

export default {
    components: {
        Link,
    },
};
</script>
