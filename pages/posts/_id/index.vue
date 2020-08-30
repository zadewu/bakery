<template>
    <div class="single-post-page container">
        <section class="post">
            <h1>Title of Post</h1>
            <div class="post-details">
                <div class="post-detail">Last updated on xxx</div>
                <div class="post-detail">Written by NAME</div>
            </div>
            <p>Content of the post</p>
        </section>
        <section class="post-feedback">
            <p>Let me know what you think about this post</p>
        </section>
    </div>
</template>

<style lang="scss">
    .single-post-page {
        section {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        } 

    }
</style>