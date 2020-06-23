<template>
    <div class="hello">Hello {{who}}</div>
</template>

<script>
module.exports = {
    data: function() {
        return {
            who: 'world'
        }
    }
}
</script>

<style lang="scss">
$primary-color: #333;
$color: #ffffff;

.hello {
    background-color: $primary-color;
    color: $color;
}
</style>