<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6">Bem-vindo à Tela de Login</h1>

    <img 
      src="../assets/img/teste.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

    <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  Para acessar o sistema, informe seu <strong>e-mail</strong> e <strong>senha</strong> cadastrados. 
  Esta tela foi criada para ser simples, segura e fácil de usar, garantindo uma experiência tranquila para todos os usuários.
  Após o login, você será direcionado para uma <strong>segunda etapa de autenticação</strong>, onde confirmaremos que está tudo certo com suas informações antes de liberar o acesso completo ao sistema.
</p>

    <router-link
      to="/component/accordion"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo ➤
    </router-link>
  </div>
</template>



<script>


</script>

<style scoped>
/* Personalize como quiser */
</style>
