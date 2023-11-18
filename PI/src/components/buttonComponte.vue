<template>
    <DxButton
        text="Click me"
        @click="sayHelloWorld"
        
    />
</template>
 
<script>
import DxButton from 'devextreme-vue/button';
 
export default {
    components: {
        DxButton
    },
    methods: {
        sayHelloWorld() {
            alert('Hello world!')
        }
    }
}
</script>