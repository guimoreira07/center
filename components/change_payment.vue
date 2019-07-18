<template>
	<div class="mdc-layout-grid container">
		<div class="mdc-layout-grid__inner">
			<div class="mdc-layout-grid__cell--span-12">
				<div class="alter-periodicity">
					<h3>Alteração da Forma de Pagamento</h3>
					<span  class="informationn">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non sem rhoncus, mollis lorem nec, volutpat felis.</span>
					<h5 class="w23">Forma de Pagamento Atual: <span class="item-link">{{current_payment}} </span></h5>
					<button  class="mdc-button mdc-button--raised"> Mudar Forma de Pagamento</button>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				current_payment: "Boleto",
			}
		}
	};
</script>

<style scoped>
.item-link{
	color: #45a0d5;
	letter-spacing: 1px;
}

</style>
