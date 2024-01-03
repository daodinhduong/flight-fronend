<script setup>
const route = useRouter();

const push = function () {
    route.push({ path: "/login" });
}
</script>
<template>
    <div>
        <button @click="push">click</button>
    </div>
</template>