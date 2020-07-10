<script>

	import { TarjetaVertical } from "@centroculturadigital-mx/ccd-sistema-diseno"
	import { ThemeWrapper } from "@centroculturadigital-mx/svelte-themer";


	import CabeceraEjercicio from "./CabeceraEjercicio.svelte"

	import temas from "./temas/temas";



	import personajes from "./datos/datos.js"



</script>


<style>

	.Contenedor {
		display: grid;
		grid-template-columns: 1fr 1fr 1fr 1fr;
		grid-gap: 2rem;
	}

</style>

<ThemeWrapper themes={temas}>

	<CabeceraEjercicio/>

	<main>
			
		<div class="Contenedor">
		
			{#each personajes as personaje}
				<h4>
					{personaje.name}
				</h4>
				<h6>
					{personaje.origin.name}
				</h6>
				<img src={personaje.image} alt="">
			{/each}


		</div>

	</main>
</ThemeWrapper>