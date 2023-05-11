<script lang="ts">
function handleClick() {
    alert("ok-fine");
}
</script>
<button on:click|once ={handleClick}>Click me</button>