<script lang="ts">
    let user = {loggedIn: false};

    function toggle() {
        user.loggedIn = !user.loggedIn;
    }
</script>

{#if user.loggedIn}
<button on:click={toggle}>
    Logged-in
</button>
{:else}
    <button on:click={toggle}>
        Logout
    </button>
{/if}
