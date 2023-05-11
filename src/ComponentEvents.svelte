<script>

import Inner from "./Inner.svelte";
function handleMessage(e) {
    console.log(e.detail.text);
}
</script>
<Inner on:message={handleMessage}/>