<template>
	
	<div id="home_billing" class="component-section">
		<div class="elevation">
			    <h2 class="mdc-dialog__title" id="my-dialog-title">Meu Plano</h2>
			    <div class="mdc-dialog__content" id="my-dialog-content">
			      <ul>
			      	<li>Plano Contratado: <strong>{{ plan }}</strong></li>
			      	<li>Produtos: <strong>{{ products }}</strong></li>
			      	<li>Visitas: <strong>{{ visits }}</strong></li>
			      	<li>Pedidos no Mercado Livre: <strong>{{ ml_orders }}</strong></li>
			      	<li>Disparos de E-mail: <strong>{{ emails }}</strong></li>
			      	<li>Contas de E-mail: <strong>{{ email_accounts }}</strong></li>
			      </ul>
			    </div>
			    <footer class="mdc-dialog__actions">
			      <button class="mdc-button mdc-button--raised">Mudar Plano</button>
			    </footer>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				plan: "Plus",
				products: "1000",
				visits: "35.000",
				ml_orders: "500",
				emails: "7.000",
				email_accounts: "15"
			}
		}
	};
</script>

<style scoped>

ul{
	list-style: none;
	padding: 0
}
li{
	padding: 5px 0
}
strong{
	margin-left: 10px;
	color: #42A0D7;
	letter-spacing:  1px;
}
</style>
