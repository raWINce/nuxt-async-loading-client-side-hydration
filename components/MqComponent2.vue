<template>
    <div>
        <wrapper :enabled="$mq === 'sm'">
            <span>Text for <b>{{ $mq }}</b></span>
        </wrapper>
    </div>
</template>

<script>
    import Wrapper from './Wrapper'

    export default {
        components: { Wrapper },
    }
</script>
