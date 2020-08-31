<template>
    <section class="nav">
        <div class="nav-logo">
             <img height="160px" src="https://www.freelogodesign.org/Content/img/logo-ex-2.png" alt="logo">
        </div>
        <div class="nav-menu">
            <ul class="nav-menu-list">
                <li class="nav-list-item">About</li>
                <li class="nav-list-item">Skills</li>
                <li class="nav-list-item">Education & Experience</li>
                <li class="nav-list-item">Projects</li>
                <li class="nav-list-item">Contact</li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="sass" scoped>
.nav
    position: fixed
    left: 0
    top: 0
    bottom: 0
    background: #333
    display: flex
    flex-direction: column
    align-items: center
    width: 20vw
    .nav-logo
        margin: 50px auto
    .nav-menu
        color: white
.nav-menu-list
    list-style: none
    padding: 0
    .nav-list-item
        background: #222
        padding: 10px 20px
        text-align: center
        margin: 10px auto
        cursor: pointer
        &:hover
            width: 100%
</style>