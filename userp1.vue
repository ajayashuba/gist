<template>
	<q-page  class="row justify-center">
	<div style='max-width:728px;width:100%'>
<div class='shadow-1 '>
<div class='row  q-ml-sm q-pt-sm '>
	<div class='col-auto '>
<img style='width:100px;height:100px ; border: 1px solid #ddd; ;border-radius: 50%;' class=' self-top q-ml-sm' src="https://pbs.twimg.com/profile_images/822921351249825792/M3Y9lsNs_400x400.jpg">	
</div>
<div class='q-pl-md q-mt-sm col '>
	<div class='col'>
	<div  class='row ' >
		<div class='col'>
<span  class='q-display-1 text-weight-medium  self-center fnt '>Ajay Kumar </span>

</div> 

</div>
</div> 

<div class='fnt text-weight-light q-my-xs'>

</div>



</div>

</div>
  <q-card-separator />

<div class='q-my-xs q-ml-sm text-weight-medium col fnt' >
	
<a class='fnt'><q-icon name="score" />&bull;<span style='color:grey'>Score</span> 29K</a>&bull;<q-icon name="message" />
<a href="" class='link'>Message</a>

 </div>
  <q-card-separator />


<q-tabs class='q-mt-xs'>
        <q-tab slot="title" label="Post"  default />
               <q-tab slot="title" label="Comments"  />

      </q-tabs> 
  </div>
      

  <router-view />

</div>  
</q-page>
</template>
<style type="text/css">
	


.fnt{
font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;

}
.link{
	text-decoration: none;
	color:black;
}

</style>
