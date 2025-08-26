# Site estático com Bootstrap, Flex e Grid

Projeto de exemplo com múltiplas páginas HTML utilizando Bootstrap 5, CSS com variáveis, pseudo-classes, listas estilizadas, demonstração de box model, Flexbox e CSS Grid.

## Estrutura

- `index.html` — página inicial com hero (Flexbox) e grids de conteúdo
- `about.html` — página sobre com cards responsivos
- `contact.html` — formulário validado com Bootstrap
- `styles.css` — estilos customizados (cores, listas, pseudo-classes, grid, box model)

## Rodar localmente

Abra `index.html` no navegador. Não há dependências além de internet para CDN do Bootstrap.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub (público), por exemplo `seu-usuario/meu-site`.
2. No terminal PowerShell, dentro da pasta do projeto:

```powershell
git init
git add .
git commit -m "Site inicial: Bootstrap + CSS"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/meu-site.git
git push -u origin main
```

3. No GitHub, acesse Settings → Pages → Build and deployment → Source: `Deploy from a branch`.
4. Selecione a branch `main` e a pasta `/root` (ou `/docs` se mover os arquivos).
5. Salve. O link do seu site aparecerá como `https://seu-usuario.github.io/meu-site`.

## Observações

- O projeto usa CDN do Bootstrap 5.3 e `styles.css` próprio.
- Exibe utilitários de texto, cores, listas personalizadas, pseudo-classes de links/botões, além de Flex e Grid.


