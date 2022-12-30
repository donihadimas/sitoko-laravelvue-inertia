<template>
    <Layout>
        <Head title="Transaksi Penjualan" />
        <h1>Transaksi Penjualan</h1>
    </Layout>
</template>
<script>
import Layout from "./Layout.vue";
import { Link, Head } from "@inertiajs/inertia-vue3";

export default {
    components: {
        Head,
        Link,
        Layout,
    },
    props: ["title"],
};
</script>
