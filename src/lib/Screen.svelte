<script lang="ts">
    export let bg:string = '';
</script>

<div style={`width:100%; height:100vh; background-image:url(./${bg});background-size: cover;`}>
    <slot/>
</div>