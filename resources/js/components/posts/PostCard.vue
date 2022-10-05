<template>
    <div class="card text-center">
        <div class="card-header">
            {{post.slug}}
        </div>
        <div class="card-body">
            <h5 class="card-title">{{ post.title }}</h5>
            <p class="card-text">{{post.content}}</p>
        </div>
        <div class="card-footer text-muted">
            <p>{{post.category.label}}</p>
            <p>{{post.author.name}}</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "PostCard",
    props: {
        post: Object,
    }
}
</script>

<style>

</style>