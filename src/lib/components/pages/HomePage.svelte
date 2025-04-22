<script>
    import ContentPage from "../organisms/ContentPage.svelte";
    import FooterPage from "../organisms/FooterPage.svelte";


    import HeadPage from "../organisms/HeadPage.svelte";

</script>
<section class="container">
    <HeadPage />
    <ContentPage />
    <FooterPage />
</section>

<style>
    .container {
        width: 100%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        flex-direction: column;
    }
</style>