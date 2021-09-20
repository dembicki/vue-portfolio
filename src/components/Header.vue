<template>
<div class="header">
    <div>
        <img alt="Vue logo" src="../assets/logo.png" height="30" />
    </div>
    <nav class="nav">
        <ul class="nav__items">
            <li class="nav__items__item">Works</li>
            <li class="nav__items__item">Experience</li>
            <li class="nav__items__item">Contact</li>
        </ul>
    </nav>
</div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
    .header{
        display:flex;
        justify-content: space-between;
        padding: 0 20px;
        align-items: center;
        background-color: black;
    }

    .nav {
        display:flex;
        align-items: center;
        &__items{
            list-style: none;
            display: flex;
            gap: 20px;
            &__item{
                padding: 10px 30px;
                &:hover{
                    background-color:#eee;
                    color:black;
                    cursor: pointer;
                }
            }
        }
    }
</style>