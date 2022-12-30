<template>
    <Layout>
        <Head title="Dashboard" />
        <h1>Dashboard</h1>
        <p>{{ title }}</p>
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
