<template>
    <div :style="customSquare"></div>
</template>

<script>
    export default {
        name:"RedSquare3",
        computed:{
            customSquare() {
                return {
                    margin: 'auto',
                    width: '40px',
                    height: '40px',
                    background: 'red',
                }
            }
        }
    }
</script>
