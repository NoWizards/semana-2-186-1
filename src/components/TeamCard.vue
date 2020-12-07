<template>
        <div class="col mt-5">
            <div class="card text-white bg-dark">
                <div class="d-flex justify-content-center p-2">
                    <img :src="member.image" alt="" class="team__image">
                </div>
                <div class="card-body">
                    <h5 class="card-title">{{member.codigo}}. {{member.nombre}}</h5>
                    <p class="card-text">{{member.descripcion}}</p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">{{member.rol}}</small>
                </div>
            </div>
        </div>
        
</template>

<script>
    export default {
        name: "TeamCard",
        props: {
            'member': Object
        }
    }
</script>

<style scoped>
.team__image{
    width: 250px;
    height: 250px;
    object-fit: cover;
}

</style>
