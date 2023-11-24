<script>


		
	let container;


	
	import {  onMount} from "svelte";

	onMount(() => {
var aa = eval(`var aa = function () {
const button =  document.createElement("button");
	button.innerHTML = "hi";
	button.addEventListener("click", () => {alert()});
	return button;
};; (() => aa)()`);

		
		container.appendChild(aa());
	});

	
</script>

<div bind:this={container}></div>
