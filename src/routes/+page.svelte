<main>
    <div>count: {count}</div>
    <button on:click={counter}>add</button>
</main>
<script lang="ts">
    export let count = 0
    export function counter(e: Event){
        count += 1
        console.log('#9')
    }
</script>