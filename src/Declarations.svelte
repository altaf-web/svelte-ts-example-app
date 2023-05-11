<script lang="ts">
    let count = 0;
    $: doubled = count * 2;
    function handleClick() {
        count += 1;
    }
</script>
<p>{count} double is {doubled}</p>
<button on:click={handleClick}>
    Clicked {count} {count === 0 ? 'time' : 'times'}
</button>