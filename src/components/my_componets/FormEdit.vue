<script></script>

<template>
    <h5>Editar Ficha</h5>
    <form class="g-1 d-flex flex-column form_container rounded">
        <div class="mt-4 ms-5 me-5">
            <label for="image" class="form-label">Imagen</label>
            <input class="form-control" type="file" id="image">
        </div>
        <div class="mt-3 ms-5 me-5">
            <label for="title" class="form-label">Título</label>
            <input type="text" class="form-control shadow bg-body rounded" id="title">
        </div>
        <div class="mt-3 ms-5 me-5">
            <label for="location" class="form-label">Localización</label>
            <input type="text" class="form-control shadow bg-body rounded" id="location">
        </div>
        <div class="mt-3 ms-5 me-5">
            <label for="scene" class="form-label">Escenario</label>
            <input type="text" class="form-control shadow bg-body rounded" id="scene">
        </div>
        <div class="mt-3 ms-5 me-5">
            <label for="date" class="form-label">Fecha</label>
            <input type="text" class="form-control shadow bg-body rounded" id="date">
        </div>
        <div class="mt-3 ms-5 me-5">
            <label for="equipment" class="form-label">Equipo</label>
            <input type="text" class="form-control shadow bg-body rounded" id="equipment">
        </div>
        <div class="mt-3 ms-5 me-5">
            <label for="light" class="form-label">Iluminación</label>
            <input type="text" class="form-control shadow bg-body rounded" id="light">
        </div>
        <div class="mt-3 ms-5 me-5">
            <label for="edition" class="form-label">Edición</label>
            <input type="text" class="form-control shadow bg-body rounded" id="edition">
        </div>
        <div class="mt-4 mb-5 me-5 d-flex justify-content-end">
            <a href="/details" class="btn me-5 pb-3">Cancelar</a>
            <button type="submit" class="btn">Añadir</button>
        </div>
    </form>
</template>

<style>
    h5{
        font-family: 'Klee One', cursive;
    }
    
    .form_container{
        background-color: #88ad99;
        width: 50%;
        margin-left: 25%;
        margin-top: 4%;
        margin-bottom: 4%;
        border:none;
        box-shadow: 3px 3px 5px 0px rgb(114, 113, 114);
    }

    label{
        font-family: 'Klee One', cursive;
    }


    .btn{
        background-color: #71917f;
        min-width: 11.5%;
    }

    .btn:hover{
        background-color: black;
    }

</style>