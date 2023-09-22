<template>
    <div class="content">
        <h1 class="Company-Name">Bizsync</h1>
        <div class="links">
            <a href="#">Sobre nós</a>
            <a href="#">Serviços</a>
            <a href="#">Contactos</a>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.content{
    display: flex;
    justify-content: space-between;
    border-bottom: solid 1px gray;
    width: 80dvw;
}

.links{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    width: 60%;
}

.Company-Name{
    color: #008ECC;
    font-family: papyrus;
}

a{
    text-decoration: none;
}
</style>