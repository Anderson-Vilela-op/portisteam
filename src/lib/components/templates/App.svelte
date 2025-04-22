<div class="background">
    <slot />
</div>

<style>

    .background {
        background-image: url("https://cdn.fastly.steamstatic.com/steamcommunity/public/images/items/655100/994c4d37d8a2f35d1681a8f8bf0367d4ecda7abe.jpg");
        background-repeat: no-repeat;
        background-attachment: fixed;
        width: 100vw;
        min-height: 100vh;
    }

    @media (max-width:  976px) {
        .background{
            background-size: cover;
        }
    }
</style>
