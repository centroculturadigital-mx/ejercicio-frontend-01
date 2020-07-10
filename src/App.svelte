<script>

	import { Cabecera } from "@centroculturadigital-mx/ccd-sistema-diseno"

	import BarraLateral from "./BarraLateral.svelte"
	import Contenido from "./Contenido.svelte"

</script>


<style>

.Contenedor {
	display: grid;
	grid-template-columns: 1fr 2fr;
}

</style>


<Cabecera/>

<div class="Contenedor">

	<BarraLateral/>
	
	<Contenido
		titulo="Un super título nuevo"
		texto="Occaecat cillum eu commodo fugiat non duis voluptate officia sint. Non adipisicing tempor anim amet ad reprehenderit anim. Occaecat voluptate non mollit irure fugiat. Cupidatat dolore adipisicing minim do minim amet elit nulla Lorem. Velit sit irure exercitation eiusmod deserunt incididunt voluptate consequat quis."
	/>
	
</div>