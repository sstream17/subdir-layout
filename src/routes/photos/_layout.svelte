<script lang="ts">
    import PhotosNav from "../../components/PhotosNav.svelte";

    export let segment: string;
</script>

<PhotosNav {segment} />

<main>
    <slot />
</main>
