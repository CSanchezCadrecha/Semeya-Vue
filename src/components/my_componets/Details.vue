<script>
</script>

<template>
    <h3 class="mt-5 ms-5">Ficha Detalle</h3>
    <div class="card mt-3 ms-5 me-5 mb-5 card_detail d-flex justify-content-center">
        <div class=" mt-3 me-3 ms-3 d-flex" >
            <div class="img_card">
                <img src="src/assets/foto.jpg" class="card-img-top pb-4 pe-3 ps-3 pt-3" alt="fotografía">
            </div>
            <div class="card mt-5 ms-5 me-5 text_detail">
                <!-- <h5 class="mb-5">Blanco y Negro</h5> -->
                <ul class="list-group list-group-flush">
                    <li class="list-group-item">Título: Blanco y Negro</li>
                    <li class="list-group-item">Localización: Avilés</li>
                    <li class="list-group-item">Escenario: Ciudad</li>
                    <li class="list-group-item">Temporada: Invierno</li>
                    <li class="list-group-item">Fecha: 21/Diciembre/2021</li>
                    <li class="list-group-item">Hora: Amanecer</li>
                    <li class="list-group-item">Equipo: Xiaomi Redmi Note Pro</li>
                    <li class="list-group-item">Objetivo: No</li>
                    <li class="list-group-item">Iluminación: Natural</li>
                    <li class="list-group-item">Edición: Si</li>
                    <li class="list-group-item"></li>
                </ul>
                <div class="buttons mt-3 d-flex justify-content-end">
                    <a href="#" class="btn ms-5 me-3 pb-3"><i class="bi bi-pencil-fill"></i></a>
                    <a href="#" class="btn ms-5 pb-3"><i class="bi bi-trash3-fill"></i></a>
                </div>
            </div> 
        </div>
    </div>
</template>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css");

.card_detail{
    width: 90%;
    box-shadow: 3px 3px 5px 0px rgb(114, 113, 114);
}

.card-img-top{
    width: 100%;
}

.img_card{
    width: 60%;
}

.text_detail{
    border:none;
    width: 40%;
}

.btn{
    background-color: #88ad99;
    box-shadow: 3px 3px 5px 0px rgb(114, 113, 114);
}

.btn:hover{
    background-color:  #88ad99;
}

</style>