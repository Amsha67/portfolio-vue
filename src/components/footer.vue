
<template>
    <footer class="pied">
        <div class="pied-contenu">

            <div class="contact-mail">
                <h3>Me contacter</h3>
                <a class="btn-rouge" href="mailto:eric.schmoelzlin@gmail.com" aria-label="Envoyer un mail">
                    <img src="@/assets/Gmail.png" alt="icone d'une enveloppe gmail">
                    <span class="libelle">Gmail</span>

                </a>
            </div>

            <div class="CV">
                <h3>MON CV</h3>
                <a class="btn-rouge cv-footer" href="@/assets/CV ES SIO.pdf" download>
                    <img src="@/assets/CV.png" alt="icone d'un CV"> Télécharger
                </a>
            </div>

            <div class="liens-sociaux">
                <h3>Réseaux</h3>
                <a class="btn-rouge" href="https://www.linkedin.com/in/eric-schmoelzlin-824274220/" target="_blank"
                    rel="noopener" aria-label="LinkedIn">
                    <img src="@/assets/linkedin.png" alt="icone bleu de linkedin" width="22" height="22">
                    <span class="libelle">LinkedIn</span>
                </a>
                <a class="btn-rouge" href="https://github.com/Amsha67" target="_blank" rel="noopener"
                    aria-label="GitHub">
                    <img src="@/assets/git.png" alt="icon du chat noir de git" width="24" height="24">
                    <span class="libelle">GitHub</span>
                </a>
            </div>
        </div>

        <p class="credit">© 2025 — Eric Schmoelzlin</p>
    </footer>

</template>

<script>
export default {
    name: 'footer'
}
</script>