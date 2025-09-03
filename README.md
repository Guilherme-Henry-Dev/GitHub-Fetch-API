# 🐙 Projeto: Buscador de Usuário do GitHub

Um aplicativo simples e funcional que consome a **API pública do GitHub** para buscar informações de qualquer usuário.  
Basta digitar o nome de usuário e visualizar dados como **foto de perfil, bio e repositórios públicos**.

---

## 🛠️ Tecnologias Utilizadas

- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=fff)  
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=fff)  
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)  
- ![GitHub API](https://img.shields.io/badge/GitHub%20API-181717?style=for-the-badge&logo=github&logoColor=fff)  

---

## 🚀 Demonstração

### 🖥️ Tela inicial
![Usuário não encontrado](./src/img/projeto-github-1.jpg)

### 👤 Perfil encontrado
![Perfil encontrado](./src/img/projeto-github-2.jpg)

### 🔎 Usuário não encontrado
![Tela inicial](./src/img/projeto-github-3.jpg)

---

## 📂 Estrutura do Projeto

```bash
📁 PROJETO-FETCH-GITHUB
 ┣ 📂 src
 ┃ ┣ 📂 css
 ┃ ┃ ┣ 📜 reset.css           # Reset de estilos
 ┃ ┃ ┗ 📜 styles.css          # Estilo principal
 ┃ ┣ 📂 scripts
 ┃ ┃ ┣ 📂 objects
 ┃ ┃ ┃ ┣ 📜 screen.js         # Renderização de dados na tela
 ┃ ┃ ┃ ┗ 📜 user.js           # Estrutura do objeto usuário
 ┃ ┃ ┣ 📂 services
 ┃ ┃ ┃ ┣ 📜 repositories.js   # Consumo de repositórios da API
 ┃ ┃ ┃ ┣ 📜 user.js           # Consumo de dados do usuário da API
 ┃ ┃ ┃ ┣ 📜 variables.js      # Seletores e variáveis globais
 ┃ ┃ ┃ ┗ 📜 index.js          # Ponto inicial do app (lógica principal)
 ┣ 📜 index.html              # Estrutura da página
 ┗ 📜 README.md               # Documentação
```

---

## ⚙️ Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Guilherme-Henry-Dev/GitHub-Fetch-API.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd GitHub-Fetch-API
   ```

3. Abra o arquivo `index.html` no navegador:
   ```bash
   start index.html   # (Windows)
   open index.html    # (MacOS)
   xdg-open index.html # (Linux)
   ```

---

## 📌 Funcionalidades

- [x] Buscar usuário pelo nome no GitHub  
- [x] Exibir foto de perfil, bio e repositórios públicos  
- [x] Tratamento de erro quando o usuário não existe  
- [x] Layout **totalmente responsivo**  
- [x] Melhorar visualização dos repositórios (grid/cards clicáveis)  
- [x] Exibir seguidores/seguindo  
- [ ] Dark/Light mode  

---

## 🛣️ Próximos Passos (Roadmap)
 
- 🔹 Exibir principais linguagens de programação utilizadas em gráfico dinâmico  
- 🔹 Criar modo **Dark/Light** com alternância no botão  
- 🔹 Melhorar UI/UX com animações e microinterações  

---

## 🤝 Contribuição

Contribuições são bem-vindas!  
Se quiser melhorar o projeto, siga estes passos:

1. Faça um fork do repositório  
2. Crie uma branch para sua feature (`git checkout -b minha-feature`)  
3. Commit suas alterações (`git commit -m 'Adicionei uma nova feature'`)  
4. Envie para o repositório (`git push origin minha-feature`)  
5. Abra um Pull Request 🚀  

---

## 📝 Licença

Este projeto está sob a licença MIT.  
Sinta-se livre para usar e modificar ✨

---

## 🙋‍♂️ Autor
- 👨‍💻 Desenvolvido com dedicação por **Guilherme Henry**  
- 📍 Belo Horizonte  
- 📧 guilherme.henrydesigner@gmail.com  
