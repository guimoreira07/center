<template>
	<div class="mdc-layout-grid container">
		<div class="mdc-layout-grid__inner">
			<div class="mdc-layout-grid__cell--span-12">
				<table  class="mdl-data-table mdl-js-data-table elevation">
					<thead>
						<tr>
						<td>
							<div class="features-title">escolha seu <strong>Plano</strong></div>
						</td>
						<th>
							<div class="plan-information">
								<div class="plan-header">
									<h2 class="plan-title">{{name_light}}</h2>
									<p class="plan-starting">a partir de</p>
									<p class="plan-pricing">{{price_light_month}}</p>
									<p class="plan-periodicity">{{info_month}}</p>
									<div class="box-toggle">
										<div class="toggle-button-cover">
										<div class="button-cover">
											<div class="button r" id="button">
											<input type="checkbox" class="checkbox">
											<div class="knobs"></div>
											<div class="layer"></div>
											</div>
										</div>
										</div>
										<span id="tt3"class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
										<div class="mdl-tooltip" data-mdl-for="tt3">
											Lorem ipsum dolor sit amet
										</div>
									</div>
									<button  class="mdc-button mdc-button--raised"> Escolher</button>
								</div>
							</div>
						</th>
						<th>
							<div class="plan-information">
								<div class="plan-header">
									<h2 class="plan-title">{{name_basic}}</h2>
									<p class="plan-starting">a partir de</p>
									<p class="plan-pricing">{{price_basic_month}}</p>
									<p class="plan-periodicity">{{info_month}}</p>
									<div class="box-toggle">
										<div class="toggle-button-cover">
										<div class="button-cover">
											<div class="button r" id="button">
											<input type="checkbox" class="checkbox">
											<div class="knobs"></div>
											<div class="layer"></div>
											</div>
										</div>
										</div>
										<span id="tt4"class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
										<div class="mdl-tooltip" data-mdl-for="tt4">
											Lorem ipsum dolor sit amet
										</div>
									</div>
									<button  class="mdc-button mdc-button--raised"> Escolher</button>
								</div>
							</div>
						</th>
						<th>
							<div class="plan-information">
								<div class="plan-header">
									<h2 class="plan-title">{{name_plus}}</h2>
									<p class="plan-starting">a partir de</p>
									<p class="plan-pricing">{{price_plus_month}}</p>
									<p class="plan-periodicity">{{info_month}}</p>
									<div class="box-toggle">
										<div class="toggle-button-cover">
										<div class="button-cover">
											<div class="button r" id="button">
											<input type="checkbox" class="checkbox">
											<div class="knobs"></div>
											<div class="layer"></div>
											</div>
										</div>
										</div>
										<span id="tt5"class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
										<div class="mdl-tooltip" data-mdl-for="tt5">
											Lorem ipsum dolor sit amet
										</div>
									</div>
									<button  class="mdc-button mdc-button--raised" disabled> Plano Atual</button>
								</div>
							</div>
						</th>
						<th>
							<div class="plan-information">
								<div class="plan-header">
									<h2 class="plan-title">{{name_master}}</h2>
									<p class="plan-starting">a partir de</p>
									<p class="plan-pricing">{{price_master_month}}</p>
									<p class="plan-periodicity">{{info_month}}</p>
									<div class="box-toggle">
										<div class="toggle-button-cover">
										<div class="button-cover">
											<div class="button r" id="button">
											<input type="checkbox" class="checkbox">
											<div class="knobs"></div>
											<div class="layer"></div>
											</div>
										</div>
										</div>
										<span id="tt6"class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
										<div class="mdl-tooltip" data-mdl-for="tt6">
											Lorem ipsum dolor sit amet
										</div>
									</div>
									<button  class="mdc-button mdc-button--raised"> Escolher</button>
								</div>
							</div>
						</th>
						<th>
							<div class="plan-information">
								<div class="plan-header">
									<h2 class="plan-title">{{name_pro}}</h2>
									<p class="plan-starting">a partir de</p>
									<p class="plan-pricing">{{price_pro_month}}</p>
									<p class="plan-periodicity">{{info_month}}</p>
									<div class="box-toggle">
										<div class="toggle-button-cover">
										<div class="button-cover">
											<div class="button r" id="button">
											<input type="checkbox" class="checkbox">
											<div class="knobs"></div>
											<div class="layer"></div>
											</div>
										</div>
										</div>
										<span id="tt7"class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
										<div class="mdl-tooltip" data-mdl-for="tt7">
											Lorem ipsum dolor sit amet
										</div>
									</div>
									<button  class="mdc-button mdc-button--raised"> Escolher</button>
								</div>
							</div>
						</th>
						</tr>
					</thead>
					<tbody>
						<tr>
							<th class="mdc-title-item">Produtos
								<span id="tt8"class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
								<div class="mdl-tooltip" data-mdl-for="tt8">
									Lorem ipsum dolor sit amet
								</div>
							</th>
							<td>200</td>
							<td>500</td>
							<td>1000</td>
							<td>2500</td>
							<td>5000</td>
						</tr>
						<tr>
							<th class="mdc-title-item">Visitas
								<span id="tt9"class="mdc-list-item__meta material-icons" aria-hidden="true">info</span>
								<div class="mdl-tooltip" data-mdl-for="tt9">
									Lorem ipsum dolor sit amet
								</div>
							</th>
							<td>15.000</td>
							<td>25.000</td>
							<td>35.000</td>
							<td>45.000</td>
							<td>60.000</td>
						</tr>
						<tr>
							<th>Pedidos Mercado Livre</th>
							<td>150</td>
							<td>300</td>
							<td>500</td>
							<td>1.000</td>
							<td>2.000</td>
						</tr>
						<tr>
							<th>Disparos de email</th>
							<td>1.000</td>
							<td>5.000</td>
							<td>7.000</td>
							<td>10.000</td>
							<td>15.000</td>
						</tr>
						<tr>
							<th>Contas de email</th>
							<td>5</td>
							<td>10</td>
							<td>15</td>
							<td>20</td>
							<td>30</td>
						</tr>
					</tbody>
				</table>
			</div>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				name_light: "Light",
				price_light_annuaLly: "89",
				price_light_month: "99",
				name_basic: "Basic",
				price_basic_annuaLly: "139",
				price_basic_month: "149",
				name_plus: "Plus",
				price_plus_annuaLly: "179",
				price_plus_month: "189",
				name_master: "Master",
				price_master_annuaLly: "269",
				price_master_month: "279",
				name_pro: "Pro",
				price_pro_annuaLly: "399",
				price_pro_month: "409",
				info_annaully: "/ por mês no plano anual",
				info_month: "/ por mês no plano mensal",
			}
		}
	};
</script>

<style scoped>
@font-face {
    font-family: "Diodrum";
	font-weight: 700;
    font-style: bold;
    src: local("Diodrum"), url("/fonts/Diodrum-Bold.woff2") format("woff2"), local("Diodrum"), url("/fonts/Diodrum-Bold.woff") format("woff")
}
@font-face {
    font-family: Diodrum;
    src: url("/fonts/Diodrum-Regular.ttf") format("truetype");
    font-weight: 400;
    font-style: normal
}
.mdc-title-item{
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 0;
}
.mdc-list-item__meta{
	margin: 0;
}
.mdl-data-table td {
	border-left: 1px solid rgba(0,0,0,.12);
	border-bottom: none;
	border-top: none;
	letter-spacing: .5px;
	font-family: Diodrum;
}
.mdl-data-table th {
    text-align: left;
	letter-spacing: .5px;
	font-family: Diodrum;
}
.plan-information {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    width: 100%;
	padding-bottom: 15px;
}

.plan-information .plan-header {
    text-align: center;
    width: 100%
}

.plan-information .plan-header .plan-title {
    color: #42a0d7;
    font-family: Diodrum;
    font-size: 28px;
    font-weight: 700;
    line-height: 35px;
    text-transform: capitalize;
	margin: 15px 0;
}

.plan-information .plan-header .plan-starting {
    color: #999;
    font-size: 14px;
    font-weight: 700;
    line-height: 18px;
    text-transform: lowercase;
	margin: 0;
	letter-spacing: .5px;
	font-family: Diodrum;
}

.plan-information .plan-header .plan-pricing {
    color: #42a0d7;
    font-family: Diodrum;
    font-size: 72px;
    font-weight: 900;
    letter-spacing: -.02em;
    line-height: 72px;
    text-transform: uppercase;
	margin: 0;
	
}

.plan-information .plan-header .plan-pricing:before {
    content: 'R$';
    color: #42a0d7;
    font-size: 18px;
    font-weight: 700;
    letter-spacing: -.02em;
    line-height: 23px;
    text-transform: uppercase;
}

.plan-information .plan-header .plan-pricing:after {
    content: ',00';
    color: #42a0d7;
    font-size: 18px;
    font-weight: 700;
    letter-spacing: -.02em;
    line-height: 23px;
    text-transform: uppercase
}

.plan-information .plan-header .plan-periodicity {
    color: #42a0d7;
    font-size: 12px;
    font-weight: 700;
    line-height: 12px;
    text-transform: lowercase;
	margin: 0;
	letter-spacing: .5px;
	font-family: Diodrum;
	
}
.features-title {
    -webkit-box-align: start;
    -ms-flex-align: start;
    color: #42a0d7;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    font-family: Diodrum;
    font-size: 22px;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    letter-spacing: .05em;
    text-transform: uppercase;
	text-align: left;
	font-weight: normal;
}
.box-toggle {
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: space-evenly;
    -ms-flex-pack: space-evenly;
    justify-content: space-evenly
}

.toggle-button-cover {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    display: table-cell;
    height: 70px;
    position: relative;
    width: 100px
}

.tooltip svg {
    -webkit-transition: .5s ease all;
    transition: .5s ease all
}

.tooltip svg:hover {
    fill: #333
}

.button-cover,
.knobs,
.layer {
    bottom: 0;
    left: 0;
    position: absolute;
    right: 0;
    top: 0
}

.button {
    height: 36px;
    margin: -20px auto 0 auto;
    position: relative;
    top: 50%;
    width: 90px
}

.button.r,
.button.r .layer {
    border-radius: 100px
}

.checkbox {
    cursor: pointer;
    height: 100%;
    margin: 0;
    opacity: 0;
    padding: 0;
    position: relative;
    width: 100%;
    z-index: 3
}

.knobs {
    z-index: 2
}

.layer {
    background-color: #3fa3da;
    -webkit-transition: .3s ease all;
    transition: .3s ease all;
    width: 100%;
    z-index: 1
}

#button .knobs:before {
    content: '';
    background: #fff;
    border-radius: 50%;
    font-size: 10px;
    font-weight: 700;
    height: 10px;
    left: 4px;
    line-height: 1;
    padding: 9px 4px;
    position: absolute;
    text-align: center;
    top: 4px;
    -webkit-transition: .5s cubic-bezier(.18, .89, .35, 1.15) all;
    transition: .5s cubic-bezier(.18, .89, .35, 1.15) all;
    width: 20px
}

#button .knobs:after {
    content: 'MENSAL';
    position: absolute;
    top: 4px;
    right: 5px;
    color: #fff;
    font-size: 10px;
    font-weight: 400;
    text-align: center;
    line-height: 1;
    padding: 9px 4px;
    -webkit-transition: .5s cubic-bezier(.18, .89, .35, 1.15) all;
    transition: .5s cubic-bezier(.18, .89, .35, 1.15) all;
	font-family: diodrum;
    letter-spacing: 1px;
}

#button .checkbox:checked+.knobs:before {
    content: '';
    background-color: #3fa3da;
    left: 62px
}

#button .checkbox:checked+.knobs:after {
    content: 'ANUAL';
    color: #3fa3da;
    font-size: 10px;
    font-weight: 700;
    left: -15px;
    padding: 9px 4px
}

#button .checkbox:checked~.layer {
    background-color: #fff;
    border: 2px solid #3fa3da;
    -webkit-transition: .3s cubic-bezier(.18, .89, .35, 1.15) all;
    transition: .3s cubic-bezier(.18, .89, .35, 1.15) all
}

#button .checkbox:checked~.plan-pricing {
    display: none
}

#button .knobs,
#button .layer,
#button-1 .knobs:before {
    -webkit-transition: .5s ease all;
    transition: .5s ease all
}
</style>
