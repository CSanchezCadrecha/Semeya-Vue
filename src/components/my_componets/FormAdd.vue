<script></script>

<template>
    <!-- <form class="g-1  form_container rounded">
        <div class="mt-4 ms-5 me-5 d-flex">
            <label for="image" class="form-label me-5">Imagen</label>
            <input class="form-control" type="file" id="image">
        </div>
        <div class="form-group mt-3 ms-5 me-5 d-flex">
            <label for="title" class="form-label me-5">Título</label>
            <input type="text" class="form-control shadow bg-body rounded" id="title">
        </div>
        <div class="form-group mt-3 ms-5 me-5 d-flex">
            <label for="location" class="form-label me-5">Localización</label>
            <input type="text" class="form-control shadow bg-body rounded" id="location">
        </div>
        <div class="mt-3 ms-5 me-5 d-flex">
            <label for="scene" class="form-label me-5">Escenario</label>
            <input type="text" class="form-control shadow bg-body rounded" id="scene">
        </div>
        <div class="mt-3 ms-5 me-5 d-flex">
            <label for="date" class="form-label me-5">Fecha</label>
            <input type="text" class="form-control shadow bg-body rounded" id="date">
        </div>
        <div class="mt-3 ms-5 me-5 d-flex">
            <label for="equipment" class="form-label me-5">Equipo</label>
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
        <button type="submit" class="btn">Añadir</button>
        </div>
    </form> -->
    <form class="g-1  mt-5 form_container rounded">
        <div class="form-group row mt-5 ms-5 me-5">
            <label for="image" class="col-sm-2 col-form-label mt-4">Imagen</label>
            <div class="col-sm-10 mt-4">
                <input type="file" class="form-control shadow bg-body rounded" id="image">
            </div>
        </div>
        <div class="form-group row mt-3 ms-5 me-5">
            <label for="title" class="col-sm-2 col-form-label">Título</label>
            <div class="col-sm-10">
                <input type="text" class="form-control shadow bg-body rounded" id="title">
            </div>
        </div>
        <div class="form-group row mt-3 ms-5 me-5">
            <label for="location" class="col-sm-2 col-form-label">Localización</label>
            <div class="col-sm-10">
                <input type="text" class="form-control shadow bg-body rounded" id="location">
            </div>
        </div>
        <div class="form-group row mt-3 ms-5 me-5">
            <label for="scene" class="col-sm-2 col-form-label">Escenario</label>
            <div class="col-sm-10">
                <input type="text" class="form-control shadow bg-body rounded" id="scene">
            </div>
        </div>
        <div class="form-group row mt-3 ms-5 me-5">
            <label for="date" class="col-sm-2 col-form-label">Fecha</label>
            <div class="col-sm-10">
                <input type="text" class="form-control shadow bg-body rounded" id="date">
            </div>
        </div>
        <div class="form-group row mt-3 ms-5 me-5">
            <label for="equipment" class="col-sm-2 col-form-label">Equipo</label>
            <div class="col-sm-10">
                <input type="text" class="form-control shadow bg-body rounded" id="equipment">
            </div>
        </div>
        <div class="form-group row mt-3 ms-5 me-5">
            <label for="light" class="col-sm-2 col-form-label">Iluminación</label>
            <div class="col-sm-10">
                <input type="text" class="form-control shadow bg-body rounded" id="light">
            </div>
        </div>
        <div class="form-group row mt-3 ms-5 me-5">
            <label for="edition" class="col-sm-2 col-form-label">Edición</label>
            <div class="col-sm-10">
                <input type="text" class="form-control shadow bg-body rounded" id="edition">
            </div>
        </div>
        <div class="mt-4 mb-5 me-5 d-flex justify-content-end">
            <button type="submit" class="btn mb-3">Añadir</button>
        </div>
    </form>
</template>

<style>
.form_container {
    background-color: #88ad99;
    width: 50%;
    margin-left: 25%;
    margin-top: 4%;
    margin-bottom: 4%;
    border: none;
    box-shadow: 3px 3px 5px 0px rgb(114, 113, 114);
}

label {
    font-family: 'Klee One', cursive;
    ;
}

input {
    width: 100px;
}


.btn {
    background-color: #71917f;
    min-width: 10%;
}

.btn:hover {
    background-color: black;
}
</style>
