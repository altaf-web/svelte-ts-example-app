<script lang="ts">

import Nested from "./Nested.svelte";
import Info from "./Info.svelte";
const pkg = {
    name: 'svelte',
    version: 3,
    speed: 'blazing',
    website: 'https://svelte.dev',
    source:"linked-in"
};

</script>

<Nested answer={42} />
<Info {...pkg} />