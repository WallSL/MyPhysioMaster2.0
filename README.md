MyPhysioMaster — Hub de Guidelines (GitHub Pages + Jekyll)
Como usar:
- Suba estes arquivos no repositório público.
- Em Settings → Pages, selecione Branch = main / root.
- Acesse: https://SEU-USUARIO.github.io/NOME-DO-REPO/
Criar nova guideline:
- Duplique _guidelines/_TEMPLATE.md, preencha e faça commit.

## Administração (editar via navegador)

1. Instale as dependências Ruby com Bundler:
   ```
   bundle install
   ```
2. Defina usuário e senha para o painel (exemplo):
   ```
   export JEKYLL_ADMIN_USERNAME=admin
   export JEKYLL_ADMIN_PASSWORD=segredo
   ```
3. Inicie o servidor com o plugin de administração:
   ```
   bundle exec jekyll serve --config _config.yml,_config.admin.yml
   ```
4. Acesse [http://localhost:4000/admin](http://localhost:4000/admin) e entre com as credenciais.
