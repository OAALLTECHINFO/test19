
<script>
	import { TextBox,TextBlock,ToggleSwitch,ListItem,Button,AutoSuggestBox  } from "fluent-svelte";
</script>


<style>
    @import url("https://unpkg.com/fluent-svelte/theme.css");

    /* Some base styles to get things looking right. */
    :global(body) {
        background-color: var(--fds-solid-background-base);
        color: var(--fds-text-primary);
    }
	div.relative {
           position: fixed;
           left: 36%;

		width:300px;  align-items: center;
}
		div.new {
    text-align: center;
}
			div.Text {
				    text-align: center;
				font-family: "Segoe UI";
				font-size:128px;
				font-weight: 600;
}
	
</style>

<div class="relative">
<AutoSuggestBox placeholder="Search"/>
</div>
<div class="new">
	<Button variant="accent" >Subscribe</Button>
</div>
<div class="Text">
	    <p>The<br>OA</p>
</div>