<script>
    import { onMount } from "svelte";
    const url = "http://localhost:3000"
    onMount(async()=>{
        await fetch("http://localhost:3000/api/projects",{method : 'GET'}).then(res => res.json()).then(res => console.log(res))
    })
</script>