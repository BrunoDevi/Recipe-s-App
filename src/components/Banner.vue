<template>
  <header class="banner">
    <div class="apresentacao">
      <img src="../assets/imagens/logo.svg" alt="Icone da Cook'Up" class="logo">
      <p class="cabecalho-lg frase-cabecalho">
        <span class="texto-verde">Um banquete de ideia para</span>  despertar o chef que há em você!
      </p>
      <p class="subtitulo-lg">Explore novas receitas todos os dias com os ingredientes que estão ao seu alcance!</p>
    </div>
    <img src="../assets/imagens/foto-banner.png" alt="foto-banner" class="foto-banner">
  </header>
</template>
  
<style scoped>
.banner {
  padding: 4rem 7.5rem;
  color: var(--creme);

  display: flex;
  justify-content: space-between;
  align-items: center;
  column-gap: 3.25rem;
}

.logo {
  height: 4.5rem;
  margin-bottom: 3rem;
}

.frase-cabecalho {
  margin-bottom: 2rem;
}

.texto-verde {
  color: var(--verde-medio, #3D6D4A);
}

.foto-banner {
  width: 35rem;
}

.subtitulo-lg {
  font-size: 26px;
}

@media only screen and (max-width: 1300px) {
  .banner {
    padding: 4rem 3.75rem;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
  }

  .logo {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }
}

@media only screen and (max-width: 767px) {
  .banner {
    padding: 4rem 1.5rem;
  }

  .foto-banner {
    width: min(100%, 21.25rem);
  }
}
</style>
