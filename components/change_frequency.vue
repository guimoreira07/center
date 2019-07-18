<template>
	<div class="mdc-layout-grid container">
		<div class="mdc-layout-grid__inner">
			<div class="mdc-layout-grid__cell--span-12">
				<div class="alter-periodicity">
					<h3>Alteração da Periodicidade do Plano</h3>
					<span  class="informationn">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non sem rhoncus, mollis lorem nec, volutpat felis.</span>
					<h5 class="w23">Periodicidade do Plano Atual: <span class="item-link">{{current_frequency}} </span></h5>
					<button  class="mdc-button mdc-button--raised">{{new_frenquency}} </button>
					<button  class="mdc-button mdc-button--raised mdc-f" disabled>{{current_frequency}}</button>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				current_frequency: "Mensal",
				new_frenquency: "Mudar para Anual",
			}
		}
	};
</script>

<style scoped>
.item-link{
	color: #45a0d5;
	letter-spacing: 1px;
}
.mdc-f{
	margin-left: 15px 
}
</style>
