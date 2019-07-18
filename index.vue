<template>
	<div id="app" class="main-content container">
		<div class="mdc-layout-grid container">
			<div class="mdc-layout-grid__inner">
				<div class="mdc-layout-grid__cell--span-6"><Billing/></div>
				<div class="mdc-layout-grid__cell--span-6"><Plan/></div>
				<div class="mdc-layout-grid__cell--span-6"><Details/></div>
				<div class="mdc-layout-grid__cell--span-6"><Consumption/></div>
			</div>
		</div>
		<BoxInformation/>
		<Invoice/>
		<Historic/>
		<ChangeFrequency/>
		<ChangePayment/>
		<ChangeMaturity/>
		<Exchange/>
	</div>
</template>
<style>
body, .main-content{
	    background-color: #f5f5f5;
}
.mdc-dialog__container{
	display: block;
	width: 100%;
}
.mdc-button--raised:not(:disabled), .mdc-button--unelevated:not(:disabled){
	background-color: #98BF11
}
a{
	color: #42A0D7
}
.elevation{
	background: #fff;
	padding: 24px;
	border-radius: 4px;
	box-shadow: 0px 1px 3px 0px rgba(0,0,0,0.2), 0px 1px 1px 0px rgba(0,0,0,0.14), 0px 2px 1px -1px rgba(0,0,0,0.12);
}
.mdl-data-table{
	font-family: Roboto, sans-serif;
}
.mdc-dialog__title:before{
		display: none;
}

.mdl-data-table th{
	text-align: center;
	font-size: 14px;
	letter-spacing: .5px
}

.mdl-data-table td{
	text-align: center;
}

</style>
<script>
	import Plan from './components/home_plan.vue'
	import Consumption from './components/home_consumption.vue'
	import Details from './components/home_details.vue'
	import Billing from './components/home_billing.vue'
	import Invoice from './components/invoice.vue'
	import Historic from './components/historic.vue'
	import ChangeFrequency from './components/change_frequency.vue'
	import ChangePayment from './components/change_payment.vue'
	import ChangeMaturity from './components/change_maturity.vue'
	import Exchange from './components/exchange_plan.vue'
	import BoxInformation from './components/box_information.vue'

	export default {
		components: {
			Plan,
			Consumption,
			Details,
			Billing,
			Invoice,
			Historic,
			ChangeFrequency,
			ChangePayment,
			ChangeMaturity,
			Exchange,
			BoxInformation
		}
	}
</script>
