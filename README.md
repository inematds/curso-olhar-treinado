# Olhar Treinado v6.2 — Gosto Visual e Estéticas

Curso aberto e gratuito: quatro módulos, 12 aulas de aproximadamente 15 minutos.
Observe referências, descreva escolhas e produza estudos próprios para a feira fictícia Bairro Vivo.

[Abra o curso](https://inematds.github.io/curso-olhar-treinado/).

As ilustrações didáticas foram geradas exclusivamente com Codex image_gen. O formato segue o estilo OSWork v6.2.
As práticas podem ser feitas com fotos próprias, recortes autorizados ou desenhos. Não exigem uma ferramenta paga.

## Fontes e montagem

`context/conteudo-base.json` e `context/aulas-editoriais.json` contêm o conteúdo autoral.
`python3 montar.py` gera as aulas e invoca o montador oficial INEMA v6.
`assets/aula.css` e `assets/curso.js` são cópias do motor oficial sem alterações.
`context/imagens-codex.json` registra os prompts e originais; `context/leitor-*.md` registra revisões simuladas.
Não há publicação de vídeos, transcrições ou imagens do acervo privado de terceiros.

## Mais no INEMA.CLUB

- [Ficha do curso](https://www.inema.club/cursos/285-olhar-treinado-v6-2-gosto-visual-e-esteticas/)
- [Guia para aprender IA](https://www.inema.club/aprender-inteligencia-artificial/)
- [Catálogo](https://www.inema.club/cursos/)

## English / Español

[English](https://inematds.github.io/curso-olhar-treinado/en/) · [Español](https://inematds.github.io/curso-olhar-treinado/es/)

Textos traduzidos com GPT-6 Luna por subagentes nativos da assinatura Codex, sem API externa. Ilustrações originais compartilhadas; progresso e anotações separados por idioma.

Após montar o português, reaplique os catálogos salvos:

```sh
python3 scripts/i18n_local.py build .
python3 scripts/verify_i18n.py .
node scripts/check_i18n_browser.cjs . /tmp/curso-i18n-checks
```

Requer Python/BeautifulSoup e os pacotes locais Babel/Playwright indicados nos scripts. A montagem não chama modelos nem redes. Mudanças na fonte PT exigem revisar os catálogos `i18n/`. O motor oficial `assets/curso.js` é preservado; a proteção de importação é gerada em `assets/curso-i18n.js` e nas edições traduzidas.

Evidências em `context/validacao-i18n.md`. Revisões por agentes são simuladas, não testes com alunos reais.
