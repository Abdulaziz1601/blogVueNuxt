<template>
    <section class="post-list">
        <PostPreview
            id="1"
            thumbnail="https://res-3.cloudinary.com/fieldfisher/image/upload/c_lfill,g_auto/f_auto,q_auto/v1/sectors/technology/tech_neoncircuitboard_857021704_medium_lc5h05"
            title="Hello There!"
            previewText="This is my first post!"
        />
        <PostPreview
            id="2"
            thumbnail="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/tech-gifts-2020-1605302505.jpg"
            title="Hello There - second time"
            previewText="This is my second post!"
        />

        <PostPreview
            id="3"
            thumbnail="https://d26519lbsgqyxd.cloudfront.net/dashboard/wp-content/uploads/2021/02/11155557/lightbulb-illuminating-floor-background.jpg"
            title="Hello There - third time"
            previewText="This is my third post!"
        />

    </section>
</template>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}


</style>