<template>
    <div>
        <p v-if="$mq === 'sm'">sm paragraph</p>
        <h1 v-if="$mq === 'md'">md h1</h1>
        <div v-if="$mq === 'lg'">lg more content</div>
    </div>
</template>

<script>
    export default {}
</script>
