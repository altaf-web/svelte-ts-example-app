<script>
    import { createEventDispatcher } from 'svelte';
    const dispatch = createEventDispatcher();

    function sayHello() {
        dispatch('message', {
            text : "Hi Engineer!"
        });
    }
</script>

<button on:click={sayHello}>Click to Say Hello</button>
