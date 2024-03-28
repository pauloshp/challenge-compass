<template>
  <main class="contacts">
    <div class="email_icon">
      <img src="@/assets/Vector.svg" alt="Icone de emails" class="icons">
      <a class="words">challenge@compass.com.br</a>
    </div>
    <div class="cell_icon">
      <img src="@/assets/TelefoneIcon.svg" alt="Icone de um telefone" class="icons">
      <a class="words">+12 3456 3789</a>
    </div>
    <div class="location_icon">
      <img src="@/assets/LocationIcon.svg" alt="Icone do ponteiro de localização" class="icons">
      <a class="words">123 Street 456 House</a>
    </div>
  </main>
</template>

<style scoped>
.contacts {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  color: white;
  padding-top: 3rem;
  padding-left: 1rem;
}

.icons {
  width: 1.1rem;
  height: auto;
}

.words {
  font-weight: 500;
  font-size: 20px;
  padding-left: 15px;
}

.email_icon, .cell_icon, .location_icon {
  align-items: center;
  display: flex;
}
</style>
