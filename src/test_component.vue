<template>
    <div>TEST</div>
</template>
<script lang="ts">
import Vue from 'vue'

interface IProps {
    type: string,
    test: string
}
export default Vue.extend<{}, {}, {}, IProps>({
    name: 'TestComponent',
    props: {
        type: String,
        test: String
    }
    
})
</script>