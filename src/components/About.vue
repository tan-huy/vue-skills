<template>
    <div class="about">
        <h1>Hello {{user_name}}, this is an about page</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi incidunt autem quod, beatae itaque minima fuga tempore temporibus atque! Vitae?</p>
    </div>
</template>

<script>
export default {
  name: 'Skills',
    data() {
        return {
            user_name: this.$route.params.name
        }
    }
}
</script>