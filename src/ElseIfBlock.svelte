<script lang="ts">
    let x = 5;
</script>
{#if x < 7}
    <p>The value of x is {x}</p>
{:else if x > 7}
    <p>x is greater then 7</p>
{:else}
    <p>The x is equal to 7</p>
{/if}