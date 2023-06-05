<script setup>
  import Presupuesto from './components/Presupuesto.vue'

</script>

<template>

  <div>
    <header>
      <h1>Planificador de gastos</h1>

      <div class="contenedor-header contenedor sombra">

      <presupuesto
      
      
      />
    </div>
    </header>

  </div>

</template>

<style lang="scss" >
$color_1: var(--blanco);
$font-family_1: 'Lato', sans-serif;
$background-color_1: var(--gris-oscuro);
$background-color_2: var(--azul);
$background-color_3: var(--blanco);

:root {
	--azul: #3b82f6;
	--blanco: #ffffff;
	--gris: #e5e7eb;
	--gris-claro: #f3f4f6;
	--gris-oscuro: #374151;
	--negro: #1a202c;
}
html {
	font-size: 62.5%;
	box-sizing: border-box;
}
* {
	box-sizing: inherit;
	&::before {
		box-sizing: inherit;
	}
	&::after {
		box-sizing: inherit;
	}
}
body {
	font-family: $font-family_1;
	font-size: 1.6rem;
	background-color: $background-color_1;
}
h1 {
	font-size: 4rem;
}
h2 {
	font-size: 3rem;
}
header {
	background-color: $background-color_2;
	h1 {
		color: $color_1;
		text-align: center;
		padding: 3rem 0;
		margin: 0;
	}
}
.contenedor {
	width: 90%;
	max-width: 80rem;
	margin: 0 auto;
}
.contenedor-header {
	margin-top: -5rem;
	transform: translateY(5rem);
	padding: 5rem;
}
.sombra {
	box-shadow: 0 2rem 3rem rgba(0, 0, 0, .2);
	background-color: $background-color_3;
	border-radius: 1.2rem;
	padding: 5rem;
}



</style>
