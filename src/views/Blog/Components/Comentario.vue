<template>
<main class="contenedor seccion contenido-centrado">
    <div class="contenedor">
        <div class="contenedor-inputs">            
            <form class="comentario">                 

                <fieldset>                 

                    <label for="nombres">Nombre:</label>
                    <input type="text" id="nombres" name="nombres" placeholder="Ingresa tus Apellidos y Nombres" required>                  
                    
                    <label for="ciudad"> Ciudad en la cual vive actualmente:</label>
                    <input type="text" id="ciudad" name="ciudad"
                           placeholder="Ingresa el nombre de la ciudad en la cual vive actualmente" required>

                    <label for="mensaje">Comentario:</label>
                    <textarea name="mensaje" id="mensaje"  placeholder="Ingresa tus Apellidos y Nombres" required></textarea>
                </fieldset>

                <input type="submit" value="Enviar comentario" class="boton boton-verde">

            </form>
        </div>
    </div>
</main>
</template>

<style>
img {
    max-width: 100%;
}

.contenedor {
    max-width: 120rem;
    margin: 0 auto;
}

h1 {
    font-size: 3.8rem;
}

h2 {
    font-size: 3.4rem;
}

h3 {
    font-size: 3rem;
}

h4 {
    font-size: 2.6rem;
}


/**Utilidades**/

.seccion {
    margin-top: 2rem;
    margin-bottom: 2rem;
}

.fw-300 {
    font-weight: 300;
}

.centrar-texto {
    text-align: center;
}

.d-block {
    display: block!important;
}

.contenido-centrado {
    max-width: 800px;
}


/*Botones*/

.boton {
    color: white;
    font-weight: 50;
    text-decoration: none;
    font-size: 1rem;
    padding: 1rem 3rem;
    margin-top: 1rem;
    display:inline-flex;
    text-align: center;
    border: none;
}

.boton:hover {
    cursor: pointer;
}

.boton-amarillo {
    background-color: #e08709;
}

.boton-verde {
    background-color: #71B100;
}

.contacto p {
    font-size: 1.5rem;
    color: #4f4f4f;
    margin: 2rem 0 0 0;
}

legend {
    font-size: 2.4rem;
    color: #333333;
}

label {
    font-weight: 700;
    text-transform: uppercase;
    display: block;
}

input:not([type="submit"]),
textarea,
select {
    padding: 1rem;
    display: block;
    width: 100%;
    background-color: #e1e1e1;
    margin-bottom: 2rem;
    border: none;
    border-radius: .5rem;
}

input[type="radio"] {
    width: auto;
    margin: 0;
}

select {
    -webkit-appearance: none;
    appearance: none;
}

.forma-contacto {
    max-width: 30rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}


</style>