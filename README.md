# jsonfmt

Ferramenta web para **formatar, minificar e validar JSON**. Roda inteiramente no navegador: nada é enviado para servidor.

**Demo:** https://vinnenlm.github.io/jsonfmt/

## O que faz

- **Formatar**: deixa o JSON legível, com indentação de 2 espaços, 4 espaços ou tab.
- **Minificar**: remove espaços e quebras de linha e mostra a economia de bytes.
- **Validar**: confere se o JSON é válido. Em caso de erro, mostra a mensagem do parser com **linha e coluna** e seleciona o ponto do erro na entrada.
- **Ordenar chaves** em ordem alfabética, de forma recursiva.
- Copiar o resultado com um clique.
- Atalho **Ctrl+Enter** (ou Cmd+Enter) para formatar.
- Tema claro/escuro automático e layout responsivo.

## Privacidade

Todo o processamento acontece localmente, com `JSON.parse` e `JSON.stringify`. Não há back-end, requisições externas nem armazenamento de dados.

## Como usar localmente

É um único arquivo, sem dependências nem build:

```bash
git clone https://github.com/VinnenLM/jsonfmt.git
cd jsonfmt
# abra o index.html no navegador
```

## Publicação

Como é um site estático, pode ser hospedado em qualquer serviço do tipo (GitHub Pages, Netlify, Cloudflare Pages etc.), sem back-end. Este projeto usa o **GitHub Pages**, a partir da branch `main`.

## Tecnologias

HTML, CSS e JavaScript puros.
