# 🧺 Piquenique de 20 Anos - Convite Digital & Gestão 💜

![Banner do Projeto](https://img.shields.io/badge/Tema-Roxo%20%7C%20Valente%20%7C%20Crep%C3%BAsculo-blueviolet?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Um convite digital interativo e personalizado para uma celebração de 20 anos. Este projeto une um design acolhedor a um sistema completo de gestão de convidados, lista de itens e até uma cápsula do tempo secreta!

---

## 📸 Preview do Projeto

### 💜 Visão do Convidado (Site Principal)
Aqui é onde a mágica acontece! O site interativo onde os convidados confirmam presença, escolhem o que levar e deixam mensagens.

![Página Principal](/preview/inicial.jpg)

---

### 🛠️ Visão da Aniversariante (Painel de Controlo)
O sistema de gestão completo para organizar a festa com facilidade e em tempo real.

**📝 Edição do Site (Sem tocar em código)**
![Editar Site](/preview/admin-inicial.png)

**👥 Gestão de Convidados Confirmados**
![Lista de Convidados](/preview/admin-convidados.png)

**🧺 Gestão da Mesa do Piquenique**
![O que vão levar](/preview/admin-lista.png)

**💌 Cápsula do Tempo (Magicamente Trancada!)**
![Cápsula Bloqueada](/preview/admin-mensagem.png)

---

## ✨ Funcionalidades

### 🏠 O Convite (Visão dos Convidados)
- **📍 Informações Dinâmicas:** Data, Hora e Local atualizados em tempo real.
- **🗺️ Mapa Integrado:** Localização exata com Google Maps.
- **✅ RSVP Flexível:** Confirmação de presença fazendo login com o Google ou apenas digitando o nome (com geração automática de foto de perfil).
- **🧺 Mesa Colaborativa:** Lista ao vivo onde os convidados adicionam o que vão levar para comer/beber.
- **💌 Cápsula do Tempo:** Um sistema de envio de mensagens (anônimas ou identificadas) que ficam trancadas para a aniversariante até o dia da festa.
- **🎁 Sugestões de Presentes:** Guia visual com os temas favoritos da aniversariante.

### 🛠️ Painel de Controlo (Visão Admin)
- **🔐 Guardião do Bosque:** Acesso protegido por um enigma temático.
- **📝 Editor CMS:** Permite alterar os textos principais, data, hora e link do mapa sem precisar tocar no código.
- **👥 Gestão de Convidados:** Lista de quem confirmou presença com opção de excluir nomes.
- **📋 Gestão da Mesa:** Edição e exclusão de itens adicionados na lista do piquenique.
- **⌛ Leitor da Cápsula:** Ecrã bloqueado por data que só revela as mensagens no dia exato do aniversário.
- **📤 Exportação:** Botões rápidos para copiar as listas prontas direto para as suas mensagens.

---

## 🚀 Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3 (Responsivo), JavaScript (ES6+).
- **Backend (BaaS):** Firebase (Firestore Database & Authentication).
- **Integrações:** Google Maps e UI Avatars (para geração de ícones com as iniciais).

---

## 🔑 Como configurar as Credenciais do Firebase

Para que o banco de dados funcione, é necessário conectar o projeto ao Firebase:

1. Aceda ao [Firebase Console](https://console.firebase.google.com/) e crie um novo projeto.
2. No menu lateral, ative o **Firestore Database** (crie em Modo de Teste) e o **Authentication** (habilite o provedor do Google).
3. Na página inicial do seu projeto no Firebase, clique no ícone Web (`</>`) para registar uma aplicação.
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

5. Copie apenas o que está dentro das chavetas { ... } e substitua a variável firebaseConfig que se encontra no final dos seus ficheiros index.html e admin.html.

🎨 Temas e Inspirações
Este projeto foi desenhado à medida, refletindo a personalidade e os gostos da aniversariante. A identidade visual e as funcionalidades foram inspiradas em:

Cores e Flores: Domínio absoluto de tons Roxos (do lilás ao escuro) e a beleza da flor Bougainville 🌺.

Vibe Cinematográfica: O espírito livre e os ventos das Highlands escocesas de Valente 🏹, misturados com o clima misterioso e acolhedor de fim de tarde das florestas de Forks em Crepúsculo 🌲.

Música: A poesia de Djavan, especificamente a música "Sina" 🎵.

Paixões Pessoais: O amor pela Biologia 🧬 e o aconchego dos Gatinhos 🐈.

Fé e Devoção: A bênção e inspiração na natureza de São Francisco de Assis, com um espaço especial para itens católicos 🕊️.

✒️ Créditos
Este site foi idealizado, desenhado e desenvolvido com muito carinho para criar memórias inesquecíveis.

Feito com ❤️ por Venoy Studio

Venoy Studio • Agência de Desenvolvimento 💚