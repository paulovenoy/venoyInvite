import os

# Conteúdo do README.md
readme_content = """
# 🧺 Piquenique de 20 Anos - Convite Digital & Gestão 💜

![Banner do Projeto](https://img.shields.io/badge/Tema-Roxo%20%7C%20Valente%20%7C%20Crep%C3%BAsculo-blueviolet?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Um convite digital interativo e personalizado para uma celebração de 20 anos, unindo estética, funcionalidade e uma experiência única para os convidados.

---

## 📸 Visual do Projeto

O site apresenta uma paleta de tons roxos vibrantes, tipografia elegante e elementos visuais que remetem aos filmes **Valente** e **Crepúsculo**, além de toques de biologia e gatinhos.

> **[Inserir aqui o Screenshot do Site]** > *(Sugestão: Adicione uma imagem da pasta assets ou um link de imagem do projeto hospedado)*

---

## ✨ Funcionalidades

### 🏠 Site de Convite (Index)
- **📍 DNA da Festa:** Detalhes dinâmicos de Data, Hora e Local carregados em tempo real do banco de dados.
- **🗺️ Mapa Integrado:** Localização exata via Google Maps incorporado.
- **✅ RSVP Flexível:** Confirmação de presença via Google Login ou apenas digitando o nome (com geração automática de avatar).
- **🧺 Mesa Colaborativa:** Lista em tempo real onde convidados adicionam o que pretendem levar para o piquenique.
- **💌 Cápsula do Tempo:** Envio de mensagens secretas (anônimas ou não) que ficam trancadas até o dia do evento (10/05/2026).
- **🎁 Guia de Presentes:** Sugestões temáticas incluindo itens roxos, de biologia, gatinhos e itens católicos.

### 🛠️ Painel Administrativo (Admin)
- **🔐 Guardião do Bosque:** Acesso protegido por um enigma temático.
- **📝 Editor CMS:** Alteração de títulos, textos, citações, datas e links do mapa sem mexer no código.
- **👥 Gestão de Convidados:** Visualização da lista de confirmados com opção de remover entradas.
- **📋 Gestão da Mesa:** Edição e exclusão de itens da lista do piquenique.
- **⌛ Visualizador de Mensagens:** Acesso às mensagens da Cápsula do Tempo (liberado automaticamente apenas na data do evento).
- **📤 Exportação:** Botões para copiar listas formatadas diretamente para o WhatsApp.

---

## 🚀 Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3 (Moderno/Responsivo), JavaScript (ES6+).
- **Backend/Database:** [Firebase](https://firebase.google.com/) (Firestore & Authentication).
- **Icons/Favicon:** Emoji-based SVG Icons.
- **UI Avatars:** API para geração de fotos de perfil automáticas.

---

## ⚙️ Configuração do Firebase

Para colocar o projeto no ar, você precisará configurar o seu próprio projeto no Firebase:

1. Crie um projeto no [Firebase Console](https://console.firebase.google.com/).
2. Ative o **Firestore Database** e o **Authentication** (Provedor Google).
3. Nas **Regras do Firestore**, permita leitura e escrita para testes:
   ```javascript
   service cloud.firestore {
     match /databases/{database}/documents {
       match /{document=**} {
         allow read, write: if true;
       }
     }
   }