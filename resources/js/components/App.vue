<template>
    <div class="content">
        <MainHeader></MainHeader>
        <PostsList></PostsList>
    </div>
</template>

<script>
import MainHeader from "./MainHeader.vue";
import PostsList from "./posts/PostsList.vue";

export default {
    name: "App",
    components: { MainHeader, PostsList }
}
</script>

