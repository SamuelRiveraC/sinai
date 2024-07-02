<template>
    <div class="mx-auto max-w-4xl py-12 px-12 flex flex-col gap-12">

        <div>
            <h1 class="text-4xl font-bold mb-4">Bienvenida mi amor hermoso Sinai!</h1>
            <p> Hora de chambear, cada pagina tiene su propio diseño y su propio estilo. Asi que utiliza tailwind para todo y en muy pocos casos usa la etiqueta style dentro de cada pagina </p>
        </div>

        <div>
            <h3 class="text-2xl font-bold mb-4"> Tips para el exito de nuestra mision</h3>
            <ul class="list-disc pl-12" style="line-height: 2;">
                <li>Usa Tailwind para todo, pero para todo lo demas usa css en style </li>
                <li>Para cualquier imagen puedes usar <a href="https://picsum.photos/" target="_blank">Lorem Picsum</a></li>
                <li>Para cualquier icono puedes usar <a href="https://heroicons.com/" target="_blank">Heroicons</a> Copias y pegas el SVG</li>
                <li>Para cualquier color puedes usar <a href="https://tailwindcss.com/docs/customizing-colors" target="_blank">Tailwind Colors</a></li>
                <li>Para cualquier fuente puedes usar <a href="https://fonts.google.com/" target="_blank">Google Fonts</a></li>
                <li>Todas las fuentes estan en google fonts y en el figma dicen el nombre y el tamaño</li>
                <li>Instala la extension de visual code para tailwind llamada intellisense</li>
            </ul>
        </div>

        <div class="grid grid-cols-4 gap-12">
            <nuxt-link class="hover:text-red-800" to="/4xagency">
                <div class="flex items-center justify-center border hover:bg-red-50 border-red-800 min-h-12 "> 4X Agency </div>
            </nuxt-link>

            <nuxt-link class="hover:text-red-800" to="/mvpasap">
                <div class="flex items-center justify-center border hover:bg-red-50 border-red-800 min-h-12 "> MVP ASAP </div>
            </nuxt-link>

            <nuxt-link class="hover:text-red-800" to="/wordpress">
                <div class="flex items-center justify-center border hover:bg-red-50 border-red-800 min-h-12 "> Wordpress </div>
            </nuxt-link>

            <nuxt-link class="hover:text-red-800" to="/src">
                <div class="flex items-center justify-center border hover:bg-red-50 border-red-800 min-h-12 "> SRC </div>
            </nuxt-link>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomePage',
}
</script>

<style>
/* Add your custom styles here */
</style>