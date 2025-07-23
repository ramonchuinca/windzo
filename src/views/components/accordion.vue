<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-white">Segunda Etapa de Autenticação</h1>


    
    <img 
      :src="bannerImage" 
      alt="Ilustração da Segunda Etapa" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

    <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
      Após inserir seu <strong>e-mail</strong> e <strong>senha</strong>, você será direcionado para esta tela de <strong>autenticação adicional</strong>. 
      Essa etapa garante mais segurança ao seu acesso e confirma que está tudo certo com suas informações antes de liberar o uso completo do sistema.
    </p>

   <router-link
      to="/component/badge"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo ➤
    </router-link>
  </div>
</template>

<script>
import { Icon } from "@iconify/vue";
import AppAccordion from "../../components/AppAccordion.vue";
import MenuAccordion from "../../components/MenuAccordion.vue";

// Importa a imagem para o bundler entender
import bannerImage from '../../assets/img/tela do segundo fator.jpeg';

export default {
  components: {
    Icon,
    AppAccordion,
    MenuAccordion,
  },
  data() {
    return {
      bannerImage, // aqui fica o caminho importado
    };
  },
  mounted() {},
};
</script>
