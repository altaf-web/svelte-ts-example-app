<script lang="ts">
    const ApiUrl = "https://www.random.org/integers/?num=10&min=1&max=6&col=1&base=10&format=plain&rnd=new";
    async function getRandomNumber() {
        const res = await fetch(ApiUrl);
        const text = await res.text();
        return text;
    }
    let promise = getRandomNumber();
    function handleClick() {
        promise = getRandomNumber();
    }
</script>
<button on:click={handleClick}>
    generate random number
</button>
{#await promise}
    <p>...waiting</p>
{:then promise}
    <p>The number is {promise}</p>
{:catch error}
    <p style="color: red">{error.message}</p>
{/await}
