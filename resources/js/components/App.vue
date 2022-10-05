<template>
    <div class="content">
        <MainHeader></MainHeader>
        <HomePage />
    </div>
</template>

<script>
import MainHeader from "./MainHeader.vue";
import HomePage from "./pages/HomePage.vue";

export default {
    name: "App",
    components: { MainHeader, HomePage }
}
</script>

