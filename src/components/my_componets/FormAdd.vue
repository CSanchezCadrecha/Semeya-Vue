<script></script>

<template>
    <div class="mt-5 ms-5 mb-5 d-flex one">
         <form class=" row ms-5 g-3 d-flex flex-column form_container">
    <div class="col-md-8 ms-5">
        <label for="title" class="form-label">Título</label>
        <input type="text" class="form-control" id="title">
    </div>
    <div class="col-md-8 ms-5">
        <label for="location" class="form-label">Localización</label>
        <input type="text" class="form-control" id="location">
    </div>
    <div class="col-md-8 ms-5">
        <label for="inputAddress2" class="form-label">Escenario</label>
        <input type="text" class="form-control" id="">
    </div>
    <div class="col-md-8 ms-5">
        <label for="inputCity" class="form-label">Fecha</label>
        <input type="text" class="form-control" id="inputCity">
    </div>
    <div class="col-md-8 ms-5">
        <label for="inputCity" class="form-label">Equipo</label>
        <input type="text" class="form-control" id="inputCity">
    </div>
    <div class="col-md-8 ms-5">
        <label for="inputCity" class="form-label">Edición</label>
        <input type="text" class="form-control" id="inputCity">
    </div>
    <div class="col-12">
        <button type="submit" class="btn">Añadir</button>
    </div>
    </form>
</div>
</template>

<style>
    .form_container{
        background-color: #88ad99;
        width: 70%;
        
    }

    .one{
        margin-left: 50px;
    }

    .btn{
        background-color: #88ad99;
    }
</style>
