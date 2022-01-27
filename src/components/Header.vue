<template>
    <header>
        <nav>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/DC_Comics_logo.svg/2048px-DC_Comics_logo.svg.png" alt="">
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
        <div class="jumbotron"></div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
header{
    height: 400px;
    nav{
        display: flex;
        align-items: center;
        justify-content: space-around;
        height: 90px;

        img{
            height: 60px;
            cursor: pointer;
        }

        ul{
            display: flex;
            list-style: none;

            li{
                padding: 0 15px;
                height: 90px;
                line-height: 90px;
                font-weight: bold;

                &:hover{
                    color: #0282F9;
                    border-bottom: 4px solid #0282F9;
                }
            }
        }
    }
    .jumbotron{
        height: 400px;
        background: url("../assets/img/jumbotron.jpg");
        background-size: cover;
    }
}
</style>