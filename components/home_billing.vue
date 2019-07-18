<template>
	<div class="component-section">
		<div class="elevation">
			<h2 class="mdc-dialog__title" id="my-dialog-title">Faturas</h2>
			<div class="box_billing">
				<h3>R$ {{ billing }}<small> Em Aberto</small></h3>
				<button class="mdc-button mdc-button--raised">Pagar Fatura</button>
			</div>
			<br>
			<hr class="mdc-list-divider">
			<h2 class="mdc-dialog__title" id="my-dialog-title" style="padding-top: 24px;">Detalhes de Faturamento</h2>
			<ul class="mdc-list mdc-list--two-line mdc-list--avatar-list ">
				<li class="mdc-list-item mdc-ripple-upgraded">
					<span class="mdc-list-item__graphic material-icons" aria-hidden="true">toc</span>
					<span class="mdc-list-item__text"><span class="mdc-list-item__primary-text">Histórico</span>
					<span class="mdc-list-item__secondary-text"><a href="#">Consultar</a></span>
					</span>
				</li>
				<li class="mdc-list-item mdc-ripple-upgraded" style="--mdc-ripple-fg-size:360px; --mdc-ripple-fg-scale:1.7064;">
					<span class="mdc-list-item__graphic" role="presentation">
					<i class="material-icons" aria-hidden="true">payment</i>
					</span>
					<span class="tst">
							Forma de Pagamento ( {{ billing_type }} )
							<span class="mdc-list-item__secondary-text"><a href="">Alterar</a></span>
							</span>
					<span id="tt33" class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
					<div class="mdl-tooltip" data-mdl-for="tt33">
						Lorem ipsum dolor sit amet
					</div>
				</li>
				<li class="mdc-list-item mdc-ripple-upgraded" style="--mdc-ripple-fg-size:360px; --mdc-ripple-fg-scale:1.7064;">
					<span class="mdc-list-item__graphic" role="presentation">
					<i class="material-icons" aria-hidden="true">event</i>
					</span>
					<span class="tst">
							Data de Vendimento ( {{ billing_day }} )
							<span class="mdc-list-item__secondary-text"><a href="">Alterar</a></span>
							</span>
					<span id="tt31" class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
					<div class="mdl-tooltip" data-mdl-for="tt31">
						Lorem ipsum dolor sit amet
					</div>
				</li>
				<li class="mdc-list-item mdc-ripple-upgraded" style="--mdc-ripple-fg-size:360px; --mdc-ripple-fg-scale:1.7064;">
					<span class="mdc-list-item__graphic" role="presentation">
					<i class="material-icons" aria-hidden="true">date_range</i>
					</span>
					<span class="tst">
							Periodicidade ( {{ billing_frequency }} )
							<span class="mdc-list-item__secondary-text"><a href="">Alterar</a></span>
							</span>
					<span id="tt30" class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
					<div class="mdl-tooltip" data-mdl-for="tt30">
						Lorem ipsum dolor sit amet
					</div>
				</li>
			</ul>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				billing_type: "Boleto",
				billing_day: "15",
				billing_frequency: "Mensal",
				billing: "382,90",
			}
		}
	};
</script>

<style scoped>
.box_billing{
	display: flex;
    justify-content: space-between;
    align-items: flex-start;
    padding: 0 25px;
}
h3 {
  color: #FF7F00;
  font-size: 18px;
  float: left;
  margin: 0px;
}

h3 small {
  font-size: 15px;
  font-weight: 100; 
}
#actions{
	padding-top: 20px;
}
#actions a{
	font-size: 10px;
}

</style>
