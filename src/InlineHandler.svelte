<script lang="ts">
    let m = {x: 0, y: 0};
</script>
<div on:mousemove={e => m = {x: e.clientX, y: e.clientY}}>
    The Mouse position is {m.x} X {m.y}
</div>
