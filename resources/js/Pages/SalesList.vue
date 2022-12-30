<template>
    <Layout>
        <Head title="Data Penjualan" />
        <h1>Data Penjualan</h1>
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
