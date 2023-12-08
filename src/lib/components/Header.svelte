<script>
import NavBar from "$lib/components/NavBar.svelte";
import Icons from "$lib/components/Icons.svelte";
import Profile from "$lib/components/Profile.svelte";
</script>

<header class="header">
    <div class="flex">
        <a href="/" class="logo">Ferme Bio <span>KmerPlus</span></a>

        <NavBar>
            <a href="/"> Accueil</a>
            <a href="/shop"> Boutique</a>
            <a href="/orders"> Mes commandes</a>
            <a href="/comment"> Commentaire</a>
        </NavBar>

        <Icons>
            <div id="menu-btn" class="fas fa-bars"></div>
            <div id="user-btn" class="fas fa-user"></div>
            <a href="/search" class="fas fa-search"></a>
            <a href="/cart"><i class="fas fa-shopping-cart"></i></a>
        </Icons>

        <Profile>
             <div class="flex-btn">
                 <a href="" class="option-btn"></a>
                 <a href="" class="option-btn"></a>
             </div>
        </Profile>
    </div>
</header>