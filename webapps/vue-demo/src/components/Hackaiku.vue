<template>
    <div class="hello">
        <img @click="hackaikuCount++" alt="Hackaiku logo" src="../assets/hackaiku.png" class="logo">

        <h1>Hello hackaiku #<code class="count">{{hackaikuCount}}</code></h1>

        <p>Buildable Webapps project by</p>
        <div>
            <img src="../assets/andrey.jpg" class="team">
            <img src="../assets/lance.jpg" class="team">
            <img src="../assets/thibault.jpg" class="team">
        </div>
        <p>Slack <span class="slack">#hackaiku-buildable-webapps</span></p>

    </div>
</template>

<script>
    export default {
        name: 'Hackaiku',
        data: () => {
            return {
                hackaikuCount: 2,
            }
        },
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .slack{
        font-weight: bold;
    }
    .team{
        border-radius: 100%;
        height: 80px;
        padding: 20px;
    }
    .count {
        font-size: 50px;
        color: #12b2ad;
    }
    .logo {
        height: 200px
    }

    h3 {
        margin: 40px 0 0;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }

    a {
        color: #42b983;
    }
</style>
