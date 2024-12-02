
# Formulário de Feedback Anônimo

Este é um projeto simples de formulário de feedback anônimo, desenvolvido em HTML e CSS, que permite aos usuários enviar opiniões de forma confidencial. O formulário utiliza o **Formspree** para capturar e gerenciar as respostas enviadas.

## 🎯 Funcionalidades
- Interface moderna e responsiva.
- Envio de feedback anônimo ou identificado (opcional).
- Permite ao usuário:
  - Compartilhar opiniões sobre você.
  - Descrever a primeira impressão que tiveram.
  - Sugerir melhorias.
- Processamento de dados com integração ao **Formspree**.

---

## 🚀 Tecnologias Utilizadas
- **HTML5**: Estrutura do formulário.
- **CSS3**: Estilização moderna com gradientes, sombras e responsividade.
- **Formspree**: Serviço externo para envio e gestão de formulários.

---

## 📂 Estrutura do Projeto

```
.
├── index.html  # Página principal do formulário
├── README.md   # Documentação do projeto
```

---

## 💻 Como Rodar o Projeto Localmente

1. **Clone o repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

2. **Acesse o diretório do projeto**:
   ```bash
   cd <nome-da-pasta>
   ```

3. **Abra o arquivo `index.html` em um navegador**:
   - Em sistemas operacionais com interface gráfica, basta clicar duas vezes no arquivo `index.html`.
   - Ou use um servidor local, como o [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code.

---

## 🌐 Como Hospedar

1. **Hospedagem com GitHub Pages**:
   - Faça o upload dos arquivos para o branch principal ou `gh-pages` do repositório.
   - No GitHub, vá em **Settings > Pages** e configure o branch para hospedar a página.
   - O link será algo como: `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.

2. **Outras opções**:
   - [Netlify](https://www.netlify.com/): Arraste e solte o arquivo `index.html`.
   - [Vercel](https://vercel.com/): Deploy simples com integração Git.

---

## 📝 Como Personalizar

### 1. Alterar perguntas do formulário
- Edite o conteúdo dentro das tags `<label>` e `<textarea>` no arquivo `index.html`.

### 2. Configurar o e-mail de destino
- Substitua o endpoint do atributo `action` no formulário:
  ```html
  <form action="https://formspree.io/f/xwpeoklg" method="post">
  ```
- Para configurar o seu próprio endpoint, acesse o [Formspree](https://formspree.io/) e crie um formulário.

---

## 🛠 Melhorias Futuras
- Adicionar validação de entrada de dados com JavaScript.
- Implementar alertas de sucesso ou erro no envio do formulário.
- Possibilidade de salvar respostas localmente em um banco de dados.

---

## 📜 Licença

Este projeto está licenciado sob a licença MIT. Sinta-se livre para utilizá-lo e modificá-lo conforme necessário.
