<template>
	<div class="component-section">
		<div class="elevation">
			<h2 class="mdc-dialog__title" id="my-dialog-title">Meu Consumo</h2>
			<div class="mdc-dialog__content" id="my-dialog-content">
				<p>	
					<h3 class="mdc-typography--subtitle1">Visitas Mensal</h3>
					<div role="progressbar" class="mdc-linear-progress ">
						<div class="mdc-linear-progress__buffering-dots"></div>
						<div class="mdc-linear-progress__buffer"></div>
						<div class="mdc-linear-progress__bar mdc-linear-progress__primary-bar" style="transform: scaleX(0.6);"><span class="mdc-linear-progress__bar-inner"></span></div>
						<div class="mdc-linear-progress__bar mdc-linear-progress__secondary-bar"><span class="mdc-linear-progress__bar-inner"></span>
						</div>
					</div>
				</p>   
				<p>	
					<h3 class="mdc-typography--subtitle1">Previsão de Consumo de Visitas do Mês</h3>
					<div role="progressbar" class="mdc-linear-progress ">
						<div class="mdc-linear-progress__buffering-dots"></div>
						<div class="mdc-linear-progress__buffer"></div>
						<div class="mdc-linear-progress__bar mdc-linear-progress__primary-bar" style="transform: scaleX(0.75);"><span class="mdc-linear-progress__bar-inner"></span></div>
						<div class="mdc-linear-progress__bar mdc-linear-progress__secondary-bar"><span class="mdc-linear-progress__bar-inner"></span>
						</div>
					</div>
				</p>
				<p>	
					<h3 class="mdc-typography--subtitle1">Produtos Cadastrados</h3>
					<div role="progressbar" class="mdc-linear-progress ">
						<div class="mdc-linear-progress__buffering-dots"></div>
						<div class="mdc-linear-progress__buffer"></div>
						<div class="mdc-linear-progress__bar mdc-linear-progress__primary-bar" style="transform: scaleX(1.0);"><span class="mdc-linear-progress__bar-inner"></span></div>
						<div class="mdc-linear-progress__bar mdc-linear-progress__secondary-bar"><span class="mdc-linear-progress__bar-inner"></span>
						</div>
					</div>
				</p>
				<p>	
					<h3 class="mdc-typography--subtitle1">Pedidos no Mercado Livre</h3>
					<div role="progressbar" class="mdc-linear-progress ">
						<div class="mdc-linear-progress__buffering-dots"></div>
						<div class="mdc-linear-progress__buffer"></div>
						<div class="mdc-linear-progress__bar mdc-linear-progress__primary-bar" style="transform: scaleX(0.8);"><span class="mdc-linear-progress__bar-inner"></span></div>
						<div class="mdc-linear-progress__bar mdc-linear-progress__secondary-bar"><span class="mdc-linear-progress__bar-inner"></span>
						</div>
					</div>
				</p>
			</div>
		</div>
	</div>
</template

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
.mdc-linear-progress{
	height: 20px;
	border-radius: 10px
}
.mdc-linear-progress__bar-inner{
	border-radius: 10px;
}
</style>