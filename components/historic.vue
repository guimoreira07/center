<template>
	<div class="mdc-layout-grid container">
		<div class="mdc-layout-grid__inner">
			<div class="mdc-layout-grid__cell--span-12">
				<h3>Consulte seu Histórico</h3>
            	<h6>Lembramos que a sua fatura é Boleto. Cadastre sua fatura no débito automático  e fique tranquilo.</h6>
				<table class="mdl-data-table mdl-js-data-table elevation" style="width: 100%">
					<thead>
						<tr>
						<th>Vencimento</th>
						<th>Nota Fiscal</th>
						<th>Valor</th>
						<th>Status</th>
						<th></th>
						<th></th>
						<th></th>
						</tr>
					</thead>
					<tbody>
						<tr>
							<td>{{hist_invoice_maturity}} </td>
							<td>{{hist_invoice_note}} </td>
							<td>{{hist_invoice_value}} </td>
							<td>{{hist_invoice_status}} </td>
							<td><a v-bind:href="hist_invoice_view" class="item-link"> VISUALIZAR</a></td>
							<td><a v-bind:href="hist_invoice_down" class="item-link"> BAIXAR</a></td>
							<td><a v-bind:href="hist_invoice_send" class="item-link"> ENVIAR</a></td>
						</tr>
						<tr>
							<td>{{hist_invoice_maturity}} </td>
							<td>{{hist_invoice_note}} </td>
							<td>{{hist_invoice_value}} </td>
							<td>{{hist_invoice_status}} </td>
							<td><a v-bind:href="hist_invoice_view" class="item-link"> VISUALIZAR</a></td>
							<td><a v-bind:href="hist_invoice_down" class="item-link"> BAIXAR</a></td>
							<td><a v-bind:href="hist_invoice_send" class="item-link"> ENVIAR</a></td>
						</tr>
						<tr>
							<td>{{hist_invoice_maturity}} </td>
							<td>{{hist_invoice_note}} </td>
							<td>{{hist_invoice_value}} </td>
							<td>{{hist_invoice_status}} </td>
							<td><a v-bind:href="hist_invoice_view" class="item-link"> VISUALIZAR</a></td>
							<td><a v-bind:href="hist_invoice_down" class="item-link"> BAIXAR</a></td>
							<td><a v-bind:href="hist_invoice_send" class="item-link"> ENVIAR</a></td>
						</tr>
						<tr>
							<td>{{hist_invoice_maturity}} </td>
							<td>{{hist_invoice_note}} </td>
							<td>{{hist_invoice_value}} </td>
							<td>{{hist_invoice_status}} </td>
							<td><a v-bind:href="hist_invoice_view" class="item-link"> VISUALIZAR</a></td>
							<td><a v-bind:href="hist_invoice_down" class="item-link"> BAIXAR</a></td>
							<td><a v-bind:href="hist_invoice_send" class="item-link"> ENVIAR</a></td>
						</tr>
						<tr>
							<td>{{hist_invoice_maturity}} </td>
							<td>{{hist_invoice_note}} </td>
							<td>{{hist_invoice_value}} </td>
							<td>{{hist_invoice_status}} </td>
							<td><a v-bind:href="hist_invoice_view" class="item-link"> VISUALIZAR</a></td>
							<td><a v-bind:href="hist_invoice_down" class="item-link"> BAIXAR</a></td>
							<td><a v-bind:href="hist_invoice_send" class="item-link"> ENVIAR</a></td>
						</tr>
						<tr>
							<td>{{hist_invoice_maturity}} </td>
							<td>{{hist_invoice_note}} </td>
							<td>{{hist_invoice_value}} </td>
							<td>{{hist_invoice_status}} </td>
							<td><a v-bind:href="hist_invoice_view" class="item-link"> VISUALIZAR</a></td>
							<td><a v-bind:href="hist_invoice_down" class="item-link"> BAIXAR</a></td>
							<td><a v-bind:href="hist_invoice_send" class="item-link"> ENVIAR</a></td>
						</tr>
					</tbody>
				</table>
				<div class="elevation mdc-margin">
					Estão disponíveis para consulta as faturas dos últimos dozes vencimentos.
					As faturas estarão disnponíveis no site em até 10 dias antes do vencimento.
					Para faturas com pagamento através de Débito em Conta, o status “Em aberto” é exibido até 4 dias úteis após a data de vencimento, que é o periodo para compensação bancária.
					Para segunda via do seu boleto do acordo de pamento, clique aqui
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				hist_invoice_maturity: "10/11/2018",
				hist_invoice_note: "13932232",
				hist_invoice_value: "R$ 318,00",
				hist_invoice_status: "Pago",
				hist_invoice_view: "#",
				hist_invoice_down: "#",
				hist_invoice_send: "#",
			}
		}
	};
	
</script>

<style scoped>
.mdc-margin{
	margin: 20px 0
}

</style>
