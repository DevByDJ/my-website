<script>
    import Header from "../components/Header.svelte";
    import "../style.css";
    import { page } from '$app/stores';

</script>

<div>
    <Header />
    <slot />
</div>
