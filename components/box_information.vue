<template>
	<div class="mdc-layout-grid container">
		<div class="mdc-layout-grid__inner">
			<div class="mdc-layout-grid__cell--span-12">
				<div class="mdc-layout-grid__cell--span-4 elevation">
					<div>{{information}}</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	module.exports = {
		data: function () { 
			return {
				information: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non sem rhoncus, mollis lorem nec, volutpat felis. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non sem rhoncus, mollis lorem nec, volutpat felis.",
				
			}
		}
	};
</script>

<style scoped>
.elevation{
	background: #FFFCDC;
	color: #9C9C9C;
	font-size: 14px;
	letter-spacing: 1px;
}

</style>
