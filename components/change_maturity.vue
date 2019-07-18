<template>
	<div class="mdc-layout-grid container">
		<div class="mdc-layout-grid__inner">
			<div class="mdc-layout-grid__cell--span-12">
				<div class="alter-periodicity">
					<h3>Alteração da Data de Vencimento</h3>
					<span  class="informationn">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non sem rhoncus, mollis lorem nec, volutpat felis.</span>
					<h5 class="w23">Data de Vencimento Atual: <span class="item-link">{{current_day}} </span></h5>
					<div class="mdc-select mdc-select--outlined"><i class="mdc-select__dropdown-icon"></i>
						<select id="outlined" class="mdc-select__native-control">
							<option value="" disabled=""></option>
							<option value="01">01</option>
							<option value="02">02</option>
							<option value="03">03</option>
							<option value="04">04</option>
							<option value="05">05</option>
							<option value="06">06</option>
							<option value="07">07</option>
							<option value="08">08</option>
							<option value="09">09</option>
							<option value="10">10</option>
							<option value="11">11</option>
							<option value="12">12</option>
						</select>
						<div class="mdc-notched-outline mdc-notched-outline--upgraded mdc-notched-outline--notched">
							<div class="mdc-notched-outline__leading"></div>
							<div class="mdc-notched-outline__notch" style="width: 33.5px;">
								<label for="outlined" class="mdc-floating-label mdc-floating-label--float-above" style="">Dia</label>
							</div>
							<div class="mdc-notched-outline__trailing"></div>
						</div>
					</div>
				</div>
			</div>
			<button  class="mdc-button mdc-button--raised"> Alterar</button>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				current_day: "14",
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
