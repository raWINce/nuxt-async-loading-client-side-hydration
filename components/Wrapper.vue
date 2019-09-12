<template>
    <div>
        <div v-if="enabled">
            <p>
                <slot />
            </p>
        </div>
        <div v-else>
            <slot />
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            enabled: {
                type: Boolean,
                required: true,
            }
        }
    }
</script>
