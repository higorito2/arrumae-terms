# Arrumaê — documentos legais

Site público com os documentos legais do aplicativo Arrumaê.

- [Termos de Uso](https://higorito2.github.io/arrumae-terms/terms/)
- [Política de Privacidade](https://higorito2.github.io/arrumae-terms/privacy/)
- [Exclusão de Conta e Dados](https://higorito2.github.io/arrumae-terms/account-deletion/)

## Publicação

O workflow `.github/workflows/pages.yml` gera o site com Jekyll e publica o
artefato no GitHub Pages a cada push na branch `main`.

Se o Pages ainda não estiver habilitado no repositório, abra **Settings → Pages**
e selecione **GitHub Actions** em **Build and deployment → Source**. Depois,
execute novamente o workflow **Deploy GitHub Pages** na aba **Actions**.

## Atualização dos documentos

Edite os arquivos Markdown na raiz e faça push para `main`. Os caminhos públicos
permanecem estáveis por causa dos `permalink` definidos no front matter.
