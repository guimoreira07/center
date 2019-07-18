<template>
	<div class="mdc-layout-grid container">
		<div class="mdc-layout-grid__inner">
			<div class="mdc-layout-grid__cell--span-12">
				<h4>Pagamento da fatura</h4>
				<div class="mdc-layout-grid container">
					<div class="mdc-layout-grid__inner">
						<div class="mdc-layout-grid__cell--span-4 elevation">
							<div class="titlef">Fatura Nº</div>
							<div class="vff">{{number_invoice}}</div>
						</div>
						<div class="mdc-layout-grid__cell--span-4 elevation">
							<div class="titlef">Vencimento</div>
							<div class="vff">{{maturity_invoice}}</div>
						</div>
						<div class="mdc-layout-grid__cell--span-4 elevation">
							<div class="titlef">Valor  da Fatura</div>
							<div class="vff">{{value_invoice}}</div>
						</div>
					</div>
				</div>
				<div class="mdc-tab-bar custom-demo-tab-bar mdc-tabs mdc-tabs-upgraded mdc-pd" role="tablist" aria-label="Navigation">
					<div class="mdc-tab-scroller">
					<div class="mdc-tab-scroller__scroll-area">
						<div class="mdc-tab-scroller__scroll-content">
						<button class="mdc-tab mdc-tab--stacked mdc-tab--active" role="tab" aria-selected="true" tabindex="-1">
							<span class="mdc-tab__content">
							<span class="mdc-tab__icon material-icons">
								<svg style="width:24px;height:24px" viewBox="0 0 24 24">
									<path  d="M2,6H4V18H2V6M5,6H6V18H5V6M7,6H10V18H7V6M11,6H12V18H11V6M14,6H16V18H14V6M17,6H20V18H17V6M21,6H22V18H21V6Z" />
								</svg>
							</span>
							<span class="mdc-tab__text-label">Boleto</span>
							</span>
							<span class="mdc-tab-indicator mdc-tab-indicator--active">
							<span class="mdc-tab-indicator__content mdc-tab-indicator__content--underline"></span>
							</span>
							<span class="mdc-tab__ripple"></span>
						</button>
						<button class="mdc-tab mdc-tab--stacked" role="tab" aria-selected="false" tabindex="0">
							<span class="mdc-tab__content">
							<span class="mdc-tab__icon material-icons">credit_card</span>
							<span class="mdc-tab__text-label">Cartão de Crédito</span>
							</span>
							<span class="mdc-tab-indicator">
							<span class="mdc-tab-indicator__content mdc-tab-indicator__content--underline"></span>
							</span>
							<span class="mdc-tab__ripple"></span>
						</button>
						<button class="mdc-tab mdc-tab--stacked" role="tab" aria-selected="false" tabindex="-1">
							<span class="mdc-tab__content">
							<span class="mdc-tab__icon material-icons">swap_horiz</span>
							<span class="mdc-tab__text-label">Transferência Bancaria</span>
							</span>
							<span class="mdc-tab-indicator">
							<span class="mdc-tab-indicator__content mdc-tab-indicator__content--underline"></span>
							</span>
							<span class="mdc-tab__ripple"></span>
						</button>
						</div>
					</div>
					</div>
				</div>
				<div class="info__invoice">
					<span class="info__title">Utilize o código de barras abaixo:</span>
					<div class="info__links">
						<a v-bind:href="link_cod" class="item-link"> Copiar código</a>
						<a v-bind:href="send_mail" class="item-link"> Enviar para email</a>
						<a v-bind:href="down_inovoice" class="item-link"> Baixar fatura</a>
					</div>
				</div>
				<svg width="675" height="60" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path d="M4.5 0v59.08H0V0h4.5zM12.83 0v59.08h-4.5V0h4.5zM18.33 59.08V0h-1.66v59.08h1.66zM29.5 0v59.08H25V0h4.5zM37.83 59.08V0h-4.5v59.08h4.5zM43.33 0v59.08h-1.66V0h1.66zM51.67
					59.08V0H50v59.08h1.67zM60 0v59.08h-1.67V0H60zM68.33 59.08V0h-1.66v59.08h1.66zM79.5 0v59.08H75V0h4.5zM85 59.08V0h-1.67v59.08H85zM93.33 0v59.08h-1.66V0h1.66zM104.5 59.08V0H100v59.08h4.5zM112.83 
					0v59.08h-4.5V0h4.5zM118.33 59.08V0h-1.66v59.08h1.66zM126.67 0v59.08H125V0h1.67zM135 59.08V0h-1.66v59.08H135zM143.33 0v59.08h-1.66V0h1.66zM154.5 59.08V0H150v59.08h4.5zM160 0v59.08h-1.66V0H160zM171.17
					59.08V0h-4.5v59.08h4.5zM176.66 0v59.08H175V0h1.66zM187.83 59.08V0h-4.5v59.08h4.5zM193.33 0v59.08h-1.66V0h1.66zM201.66 59.08V0H200v59.08h1.66zM212.83 0v59.08h-4.5V0h4.5zM221.17 59.08V0h-4.5v59.08h4.5zM226.66
					0v59.08H225V0h1.66zM237.83 59.08V0h-4.5v59.08h4.5zM246.17 0v59.08h-4.5V0h4.5zM254.5 59.08V0H250v59.08h4.5zM260 0v59.08h-1.67V0H260zM268.33 59.08V0h-1.66v59.08h1.66zM276.67 0v59.08H275V0h1.67zM285 59.08V0h-1.67v59.08H285zM296.17
					0v59.08h-4.5V0h4.5zM304.5 59.08V0H300v59.08h4.5zM310 0v59.08h-1.67V0H310zM318.33 59.08V0h-1.66v59.08h1.66zM329.5 0v59.08H325V0h4.5zM335 59.08V0h-1.67v59.08H335zM343.33 0v59.08h-1.66V0h1.66zM351.67 59.08V0H350v59.08h1.67zM360 0v59.08h-1.67V0H360zM368.33 
					59.08V0h-1.66v59.08h1.66zM379.5 0v59.08H375V0h4.5zM385 59.08V0h-1.67v59.08H385zM396.17 0v59.08h-4.5V0h4.5zM404.5 59.08V0H400v59.08h4.5zM410 0v59.08h-1.67V0H410zM421.17 59.08V0h-4.5v59.08h4.5zM429.5 0v59.08H425V0h4.5zM435 59.08V0h-1.67v59.08H435zM443.33
					0v59.08h-1.66V0h1.66zM454.5 59.08V0H450v59.08h4.5zM462.83 0v59.08h-4.5V0h4.5zM471.17 59.08V0h-4.5v59.08h4.5zM476.67 0v59.08H475V0h1.67zM487.83 59.08V0h-4.5v59.08h4.5zM496.17 0v59.08h-4.5V0h4.5zM501.67 59.08V0H500v59.08h1.67zM512.83 0v59.08h-4.5V0h4.5zM521.17
					59.08V0h-4.5v59.08h4.5zM529.5 0v59.08H525V0h4.5zM537.83 59.08V0h-4.5v59.08h4.5zM546.17 0v59.08h-4.5V0h4.5zM554.5 59.08V0H550v59.08h4.5zM562.83 0v59.08h-4.5V0h4.5zM568.33 59.08V0h-1.66v59.08h1.66zM576.66 0v59.08H575V0h1.66zM585 59.08V0h-1.66v59.08H585zM593.33
					0v59.08h-1.66V0h1.66zM604.5 59.08V0H600v59.08h4.5zM610 0v59.08h-1.66V0H610zM618.33 59.08V0h-1.66v59.08h1.66zM629.5 0v59.08H625V0h4.5zM641.67 59.08V0h-8.34v59.08h8.34zM650 0v59.08h-1.66V0H650zM658.33 59.08V0h-1.66v59.08h1.66zM666.67 0v59.08h-4.5V0h4.5zM675 59.08V0h-4.5v59.08h4.5z" fill="#000"/>
				</svg>
				<div class="info__invoice">
                    <span class="info__title">Lançamentos referente ao Período: </span>
                    <span class="e23">{{frequency_invoice}}</span>
                </div>
				<table class="mdl-data-table mdl-js-data-table elevation" style="width: 100%">
					<thead>
						<tr>
						<th>Descrição do Serviço</th>
						<th>Data Inicial</th>
						<th>Data Final</th>
						<th>Tipo de Mensalidade</th>
						<th>Valor</th>
						</tr>
					</thead>
					<tbody>
						<tr>
							<td>{{desc_service}}</td>
							<td>{{inicial_date}}</td>
							<td>{{final_date}}</td>
							<td>{{type_service}} </td>
							<td>{{value_service}} </td>
						</tr>
						<tr>
							<td>{{desc_service}}</td>
							<td>{{inicial_date}}</td>
							<td>{{final_date}}</td>
							<td>{{type_service}} </td>
							<td>{{value_service}} </td>
						</tr>
						<tr>
							<td>{{desc_service}}</td>
							<td>{{inicial_date}}</td>
							<td>{{final_date}}</td>
							<td>{{type_service}} </td>
							<td>{{value_service}} </td>
						</tr>
						<tr>
							<td>{{desc_service}}</td>
							<td>{{inicial_date}}</td>
							<td>{{final_date}}</td>
							<td>{{type_service}} </td>
							<td>{{value_service}} </td>
						</tr>
					</tbody>
					<tfoot>
						<td colspan="3"></td>
						<td colspan="1">
						Total
						</td>
						<td colspan="1">
						{{total_invoice}}
						</td>
					</tfoot>
					</table>
			</div>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				number_invoice: "311947",
				maturity_invoice: "15/04/2019",
				value_invoice: "R$ 318,00",
				link_cod: "#",
				send_mail: "#",
				down_inovoice: "#",
				frequency_invoice: "28/04/2019  a 29/05/2019",
				desc_service: "Commerce Light",
				inicial_date: "28/04/2019",
				final_date: "28/04/2019",
				type_service: "Mensal",
				value_service: "R$ 79,00",
				total_invoice: "R$ 100,00"
			}
		}
	};

	
</script>

<style scoped>
.mdc-pd{
	padding: 20px 0
}
.info__invoice {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    padding: 20px 0;
	font-family: Roboto, sans-serif;
}

.info__title {
    padding: 10px 20px;
    font-size: 16px;
    line-height: 16px
}

.item-link {
    font-weight: 500;
    font-size: 16px;
    line-height: 16px;
    letter-spacing: 1px;
    -webkit-text-decoration-line: underline;
    text-decoration-line: underline;
    color: #45a0d5;
    margin: 0 30px
}

</style>
