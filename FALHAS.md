# Falhas e correções

| data | o que quebrou | menor correção | prompt ou infra |
|---|---|---|---|
| 2026-09-26 | Texto do atributo `data-def` foi traduzido junto com o conteúdo visível | Manter atributos da tag idênticos à origem e traduzir só o texto entre tags | prompt |
| 2026-09-26 | Tradução parcial não pôde ser serializada porque a gravação exigia chaves das partes anteriores | Mesclar o segmento novo ao JSON já existente antes de ordenar e gravar | prompt |
| 2026-09-25 | Captura da aula 12 aconteceu antes de terminar a cópia das imagens | Esperar materialização de todos os assets antes das capturas e recapturar a aula | infra |
| 2026-09-25 | Critérios rejeitavam desenho e legenda afirmava luz inexistente | Alinhar conclusão ao método permitido e distinguir proposta de observação | prompt |
