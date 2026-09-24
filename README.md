# Clube de Tiro — GitHub Pages

Este pacote é um site estático pronto para subir no GitHub Pages.

## Como publicar

1. Crie um repositório no GitHub.
2. Extraia todos os arquivos deste pacote.
3. Envie os arquivos para a raiz do repositório — principalmente `index.html`, `styles.css`, `app.js`, as outras páginas HTML e as imagens PNG.
4. No GitHub, abra **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Escolha a branch `main` e a pasta `/ (root)`.
7. Salve e aguarde o GitHub gerar o endereço.

## Acessos de teste

- Usuário: `instrutor`
- Senha: `1234`

Também é possível criar novos usuários pela tela de cadastro. Os dados ficam salvos no navegador usando `localStorage`; para compartilhar os mesmos cadastros entre vários dispositivos, será necessário um banco de dados.

As páginas de menu, consulta, treino e confirmação exigem uma sessão de login. O cadastro continua acessível pela tela inicial para permitir a criação do primeiro usuário, e o botão **Cancelar** retorna ao login.

> Importante: como este projeto é hospedado apenas como HTML/CSS/JavaScript no GitHub Pages, essa proteção é de interface e pode ser contornada por alguém com conhecimento técnico. Para permissões realmente seguras, é necessário um backend com autenticação e banco de dados.
