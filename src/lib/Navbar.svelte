<script>
    import Dropdown from "./Dropdown.svelte";
</script>

<div class="sticky top-0 z-50 uppercase bg-nav w-ful h-12 flex justify-end">
    <Dropdown></Dropdown>
</div>

<style>
    .bg-nav{
        background-image: url("./logo.png");
        background-size: 200px;
        background-repeat: no-repeat;
        background-position: center;
        background-color: #216469;
    }
</style>