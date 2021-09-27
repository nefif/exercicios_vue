<template>
    <buton class="button">
        0
    </buton>
</template>

<script>
export default {
    props: {
        label: {},
        operation: {type: Boolean},
        double: {type: Boolean},
    }
}
</script>

<style>
.button{
    background: #fff;
    color: black;

}
</style>