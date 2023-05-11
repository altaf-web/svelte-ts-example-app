<script lang="ts">
    let user = {loggedIn : false};
    function toggle() {
        user.loggedIn = !user.loggedIn;
    }
</script>

{#if user.loggedIn}
    <button on:click={toggle}>
        Logg-in
    </button>
{/if}
{#if !user.loggedIn}
    <button on:click={toggle}>
        logout
    </button>
{/if}
