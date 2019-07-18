<template>
	
	<div id="home_billing" class="component-section">
		<div class="elevation">
			<h2 class="mdc-dialog__title" id="my-dialog-title">Serviços Adicionais</h2>
			<ul class="mdc-list inline-demo-listt ">
				<li class="mdc-list-item mdc-ripple-upgraded" style="--mdc-ripple-fg-size:360px; --mdc-ripple-fg-scale:1.7064;">
					<span class="mdc-list-item__graphic" role="presentation">
					<i class="material-icons" aria-hidden="true">extension</i>
					</span>
					<span>
							Email Marketing ( {{ email_marketing }} )
							</span>
					<span id="tt20" class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
					<div class="mdl-tooltip" data-mdl-for="tt20">
						Lorem ipsum dolor sit amet
					</div>
				</li>
				<li class="mdc-list-item mdc-ripple-upgraded" style="--mdc-ripple-fg-size:360px; --mdc-ripple-fg-scale:1.7064;">
					<span class="mdc-list-item__graphic" role="presentation">
					<i class="material-icons" aria-hidden="true">extension</i>
					</span>
					<span>
							Aplicativo Mobile ( {{ app_mobile }} )
							</span>
					<span id="tt21" class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
					<div class="mdl-tooltip" data-mdl-for="tt21">
						Lorem ipsum dolor sit amet
					</div>
				</li>
				<li class="mdc-list-item mdc-ripple-upgraded" style="--mdc-ripple-fg-size:360px; --mdc-ripple-fg-scale:1.7064;">
					<span class="mdc-list-item__graphic" role="presentation">
					<i class="material-icons" aria-hidden="true">extension</i>
					</span>
					<span>
							Selo Loja Protegida ( {{ seal_loja_protegida }} )
							</span>
					<span id="tt22" class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
					<div class="mdl-tooltip" data-mdl-for="tt22">
						Lorem ipsum dolor sit amet
					</div>
				</li>
				<li class="mdc-list-item mdc-ripple-upgraded" style="--mdc-ripple-fg-size:360px; --mdc-ripple-fg-scale:1.7064;">
					<span class="mdc-list-item__graphic" role="presentation">
					<i class="material-icons" aria-hidden="true">extension</i>
					</span>
					<span>
							SSL ( {{ ssl_expiration_date }} )
							</span>
					<span id="tt23" class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
					<div class="mdl-tooltip" data-mdl-for="tt23">
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
				ssl_expiration_date: "Expira em 12/04/2020",
				email_marketing: "R$ 140,00",
				app_mobile: "R$ 230,00",
				seal_loja_protegida: "R$ 190,00"
			}
		}
	};
</script>

<style scoped>
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
