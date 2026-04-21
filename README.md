# 🧺 Piquenique de 20 Anos - Convite Digital & Gestão 💜

![Banner do Projeto](https://img.shields.io/badge/Tema-Roxo%20%7C%20Valente%20%7C%20Crep%C3%BAsculo-blueviolet?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Um convite digital interativo e personalizado para uma celebração de 20 anos. Este projeto une um design acolhedor a um sistema completo de gestão de convidados, lista de itens e até uma cápsula do tempo secreta!

---

## 📸 Visual do Projeto

*(Substitua o link abaixo pela imagem real do seu site)*
![Visual do Site](https://via.placeholder.com/800x400/5E2C85/FFFFFF?text=Coloque+a+imagem+do+site+aqui)

---

## ✨ Funcionalidades

### 🏠 O Convite (Visão dos Convidados)
- **📍 Informações Dinâmicas:** Data, Hora e Local atualizados em tempo real.
- **🗺️ Mapa Integrado:** Localização exata com Google Maps.
- **✅ RSVP Flexível:** Confirmação de presença fazendo login com o Google ou apenas digitando o nome (com geração automática de foto de perfil).
- **🧺 Mesa Colaborativa:** Lista ao vivo onde os convidados adicionam o que vão levar para comer/beber.
- **💌 Cápsula do Tempo:** Um sistema de envio de mensagens (anônimas ou identificadas) que ficam trancadas para a aniversariante até o dia da festa.
- **🎁 Sugestões de Presentes:** Guia visual com os temas favoritos da aniversariante.

### 🛠️ Painel de Controle (Visão Admin)
- **🔐 Guardião do Bosque:** Acesso protegido por um enigma temático.
- **📝 Editor CMS:** Permite alterar os textos principais, data, hora e link do mapa sem precisar tocar no código.
- **👥 Gestão de Convidados:** Lista de quem confirmou presença com opção de excluir nomes.
- **📋 Gestão da Mesa:** Edição e exclusão de itens adicionados na lista do piquenique.
- **⌛ Leitor da Cápsula:** Tela bloqueada por data que só revela as mensagens no dia exato do aniversário.
- **📤 Exportação:** Botões rápidos para copiar as listas prontas direto para o WhatsApp.

---

## 🚀 Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3 (Responsivo), JavaScript (ES6+).
- **Backend (BaaS):** Firebase (Firestore Database & Authentication).
- **Integrações:** Google Maps e UI Avatars (para geração de ícones com as iniciais).

---

## 🔑 Como copiar as Credenciais do Firebase

Para que o banco de dados funcione, você precisa conectar o seu projeto do Firebase. Siga os passos:

1. Acesse o [Firebase Console](https://console.firebase.google.com/) e crie um novo projeto.
2. No menu lateral, ative o **Firestore Database** (crie em Modo de Teste) e o **Authentication** (habilite o provedor do Google).
3. Na página inicial do seu projeto no Firebase, clique no ícone Web (`</>`) para registrar um aplicativo.
4. O Firebase vai gerar um bloco de código parecido com este:
   ```javascript
   const firebaseConfig = {
       apiKey: "SUA_API_KEY",
       authDomain: "SEU_DOMINIO.firebaseapp.com",
       projectId: "SEU_PROJECT_ID",
       storageBucket: "SEU_BUCKET.appspot.com",
       messagingSenderId: "SEU_SENDER_ID",
       appId: "SEU_APP_ID"
   };