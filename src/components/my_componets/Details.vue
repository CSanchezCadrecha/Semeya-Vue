<script></script>

<template>
    <h3 class="mt-5 title_detail">Ficha Detalle</h3>
     <div class="card card_detail mb-5">
        <div class="mt-3 me-3 ms-3 d-flex card_responsive">
            <div class="img_card">
                <img src="src/assets/foto.jpg" class="card-img-top img-fluid pb-4 pe-3 ps-3 pt-3" alt="fotografía">
            </div>
            <div class="card mt-5 mb-5 ms-5 me-5 text_detail">
                <ul class="list-group list-group-flush">
                    <li class="list-group-item"><span>Título:</span> Blanco y Negro</li>
                    <li class="list-group-item"><span>Localización:</span> Avilés</li>
                    <li class="list-group-item"><span>Escenario:</span> Ciudad</li>
                    <li class="list-group-item"><span>Fecha:</span> 21/12/2021</li>
                    <li class="list-group-item"><span>Equipo:</span> Xiaomi Redmi Note Pro</li>
                    <li class="list-group-item"><span>Iluminación:</span> Natural</li>
                    <li class="list-group-item"><span>Edición:</span> Si</li>
                    <li class="list-group-item"></li>
                </ul>
                <div class="buttons mt-3 d-flex justify-content-end">
                    <a href="/edit" class="btn ms-5 me-3 pb-3"><i class="bi bi-pencil-fill"></i></a>
                    <a href="/gallery" class="btn ms-5 pb-3"><i class="bi bi-trash3-fill"></i></a>
                </div>
            </div> 
        </div>
     </div> 
</template>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css");

@media only screen and (max-width: 1090px) {
    .card_responsive {
        display: flex;
        flex-wrap: wrap;
    } 
}

span{
    font-weight: bold;
}

.title_detail{
    margin-left: 15%;
    font-family: 'Klee One', cursive;
}

 .card_detail{
    width: 70%;
    border:none;
    box-shadow: 3px 3px 5px 0px rgb(114, 113, 114);
    margin-left: 15%;
    
} 

.card-img-top{
    width: 100%;
}

.img_card{
    width: 100%;
    height: 100%;
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
    background-color: black;;
}

</style>