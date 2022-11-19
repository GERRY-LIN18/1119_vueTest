<template>
    <img :src="require(`@/assets/images/${imgurl}.png`)">
</template>

<script>
export default {
    name: 'BigPicture',
    props: {
        imgurl: String,
    }
}
</script>