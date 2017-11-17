<template>
  <div class="headerBlock">
  	<div class="headerBlockItem">
	  <div class="left">
		<span><img class="oval" src="~/assets/me.jpg"></img>Ivan Frias</span>
	  </div>
	</div>
	<div class="headerBlockItem">
		<div class="right">
		  <div style="display: flex">
		   <div class="icon">
		  	<i class="fa fa-facebook-official" aria-hidden="true"></i>
		   </div>
		   <div class="icon">
			<i class="fa fa-twitter" aria-hidden="true"></i>
		   </div>
		   <div class="icon">
			<i class="fa fa-instagram" aria-hidden="true"></i>
		   </div>
		   <div class="icon">
			<i class="fa fa-linkedin-square" aria-hidden="true"></i>
		   </div>
		   <div class="icon">
			<i class="fa fa-google-plus" aria-hidden="true"></i>
			</div>
		  </div>
		</div>
	</div>
  </div>
</template>

<style>

.oval {
  width: 35px;
  height: 35px;
  border-radius: 30%;
}

.icon {
margin-left: 5px;
}

.logo {
  width: 35px;
  height: 35px;
}

.headerBlock {
  font-family: 'Amatic SC', cursive;
  color: white;
  display: flex;
  align-items: center;
  font-size: 30px;
  width: 100%;
  text-align: center;
  border-bottom: 1px solid grey dotted;
}

.left {
 float: left; 
}

.inline {
  display: inline
}

.headerBlockItem {
  flex-grow: 1;
}

.right {
  float: right;
}

</style>
