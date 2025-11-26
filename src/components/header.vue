<template>

    <header>

        <!-- ===== MENU BURGER (affiché seulement sur mobile) ===== -->
        <div class="menuburger">
            <!-- Checkbox qui sert de déclencheur -->
            <input type="checkbox" id="hamburger">

            <!-- Bouton burger -->
            <label id="hamburger-logo" for="hamburger">☰</label>

            <!-- Navigation du menu -->
            <nav class="menu-mobile">
                <a href="#apropos">À propos</a>
                <a href="#technologie">Technologies</a>
                <a href="#softskill">Soft skills</a>
                <a href="#realisation">Réalisations</a>
                <a href="#parcours">Parcours</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>


        <menu>
            <a href="#apropos"><button type="button">À propos</button></a>
            <a href="#technologie"><button type="button">Technologies</button></a>
            <a href="#softskill"><button type="button">Soft skills</button></a>
            <a href="#realisation"><button type="button">Réalisations</button></a>
            <a href="#parcours"><button type="button">Parcours</button></a>
        </menu>



    </header>

</template>


<script>
export default {
    name: 'header'
}
</script>
