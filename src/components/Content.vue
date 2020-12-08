<template>
    <div>
        <Feed
            v-bind:papers="papers"
        />
              
    </div>
</template>
<script>
import Feed from '@/components/Feed.vue'
export default {
    props: [
        'papers'
    ],
    components: {
        Feed
    }
}
</script>
<style scoped>
    div {
        padding: 0 20px;
    }
</style>