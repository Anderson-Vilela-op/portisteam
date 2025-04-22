<section class="head">
    <div class="left">
        <div class="profile">
            <img  class="overlay" src="https://cdn.fastly.steamstatic.com/steamcommunity/public/images/items/2308870/09942fe0b52e8abdf54a2977e5e59543e4d11e5e.jpg" alt="overlay">
            <img class="icon" src="https://avatars.fastly.steamstatic.com/359cc60a757bb28d647aa9f4e51d5bfea9d61810_full.jpg" alt="Icon">
        </div>
        <div class="titleContent">
            <span class="nickname">
                Anderson Vilela
            <img class="flag" src="https://community.cloudflare.steamstatic.com/public/images/countryflags/br.gif" alt="brasil">
            Brasil
            </span>
            <h3>Desenvolvedor de software.
                Usando WSL, aliás. JS/TS/DEV. /// Não é
                mágica. É muito esforço e determinação.</h3>
            <span class="subtitle">transformando código em soluções</span>
            <a href="https://github.com/Anderson-Vilela-op" target="_blank"  class="more">Ver mais informações</a>
        </div>
    </div>
    <div class="right">
        <div class="level">
            <p>Nível</p>
            <span>22</span>
        </div>
        <div class="bedget">
            <img src="https://community.cloudflare.steamstatic.com/public/images/badges/30_steamawardnominations/level04_80.png" alt="">
            <div>
                <p>Junior Software Developer</p>
                <span>21,434 XP</span>
            </div>
        </div>
        <div class="other">
            <a class="request" href="https://github.com/Anderson-Vilela-op">Enviar solicitação de amizade</a>
            <a href="https://github.com/Anderson-Vilela-op" class="award">
                <img src="/award_icon.svg" alt="award">
            </a>
            <a href="https://github.com/Anderson-Vilela-op" class="equipped">
                <img src="/equipped_items_icon.svg" alt="person">
            </a>
            <a href="https://github.com/Anderson-Vilela-op" class="points">...</a>
        </div>
    </div>
</section>


<style>
    .head {
        width: 976px;
        height: 256px;
        background-color: rgba(0, 0, 0, 0.6);
        padding: 20px;
        display: flex;
    }

    .head > .left {
        display: flex;
        width: 60%;
    }
    .profile {
        position: relative;
        width: 208px;
        height: 208px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .icon {
        width: 176px;
        height: 176px;
    }
    .overlay {
        position: absolute;
    }
    .titleContent {
        padding-left: 20px;
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
    }
    .titleContent > h3 {
        color: #1FB5F1;
        line-height: 23px;
        font-size: 18px;
        font-weight: 400;
        height: 55px;
    }
    .subtitle {
        color: #9b9b9b;
        font-size: 14px;
        font-style: italic;
    }
    .flag {
        padding-left: 8px;
    }
    .nickname  {
        color: #9b9b9b;
        font-size: 14px;
    }
    .more {
        color: #fff;
        font-size: 14px;
        line-height: 40px;
        text-decoration: none;
    }

    .right  {
        display: flex;
        flex-direction: column;
        width: 40%;
    }

    .level {
        display: flex;
        align-items: center;
        gap: 10px;
    }
    .level > p {
        font-weight: 100;
        font-size: 24px;
        color: #fff;
    }

    .level > span {
        border: 2px solid #1FB5F1;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 5px;
        border-radius: 100%;
        color: #fff;
        font-size: 18px;
        font-weight: 100;
        width: 23px;
        height: 23px;

    }

    .bedget {
        background: rgba(0, 0, 0, .2);
        backdrop-filter: blur(20px);
        margin: 1.1rem 0px;
        width: 315px;
        display: flex;
        gap: 10px;
        align-items: center;
        justify-content: flex-start;
        padding: 15px;
    }

    .bedget > img {
        width: 48px;
        height: 48px;
    }

    .bedget > div  {
        height: 100%;
        display: flex;
        align-items: flex-start;
        flex-direction: column;
        justify-content: center;
        
    }

    .bedget > div > p {
        font-weight: 100;
        color: #fff;
        font-size: 14px;
        height: 16px;
        margin: 0px;
    }

    .bedget > div > span {
        color: #fff;
        font-weight: 500;
        font-size: 14px;
    }

    .other {
        display: flex;
        align-items: center;
        gap: 5px;
    }

    .other > a {
        background-color: rgba(0, 0, 0, 0.6);
        border: 0   ;
        text-decoration: none;
    }

    .request {
        color: #9B9B9B;
        font-weight: 500;
        font-size: 15px;
        padding: 10px;
    }

    .award, .equipped {
        padding:8px;
    }
    .award > img, .equipped > img {
        width: 20px;
        height: 20px;
    }
    .points {
        padding: 12px;

        text-align: center;
        color: #fff;
        font-size: 14px;
    }

    @media (max-width: 976px) {
        .head {
            flex-direction: column;
            align-items: center;
            height: 430px;
            width: 800px;
        }
        .titleContent > h3 {
        color: #1FB5F1;
        line-height: 23px;
        font-size: 18px;
        font-weight: 400;
        height: 75px;
    }
    }

</style>