# Banca Simulada — Revisão Crítica do Projeto de Tese

**5 prompts para revisar seu projeto de tese ou dissertação antes da qualificação — usando IA como banca simulada.**

Cole o projeto (texto ou PDF) no Claude, ChatGPT ou Gemini e rode **um prompt por vez**, substituindo `[ÁREA]` e `[TEMA]` pelos seus. Misturar os prompts dilui a análise.

---

## Prompt 1 — Arguição simulada

> Encontra as perguntas difíceis antes da arguição. A exigência do trecho exato impede crítica genérica.

```
Atue em duas etapas separadas. Não misture as etapas.

ETAPA 1 — LEITURA: resuma os pontos centrais deste projeto de tese
(problema, objetivos, hipóteses, método).

ETAPA 2 — ARGUIÇÃO: agora ignore que foi você quem escreveu o resumo
e atue como um examinador rigoroso da área de [ÁREA] em uma banca de
qualificação. Formule as 10 perguntas mais difíceis que você faria na
arguição. Para cada pergunta, indique o trecho exato do projeto onde
a fragilidade aparece. Não suavize.
```

## Prompt 2 — Alinhamento interno

> Pega a inconsistência mais comum em projetos: objetivos órfãos (sem método) e métodos órfãos (sem objetivo).

```
Verifique a coerência interna deste projeto entre problema de pesquisa,
objetivos, hipóteses e metodologia.

1. Para cada objetivo específico, indique qual procedimento metodológico
   o responde, citando o trecho.
2. Liste os objetivos órfãos: objetivos sem procedimento metodológico
   correspondente.
3. Liste os métodos órfãos: procedimentos descritos que não respondem
   a nenhum objetivo declarado.
4. Verifique se as hipóteses são testáveis pelos métodos propostos.
```

## Prompt 3 — Afirmações sem lastro

> Classifica cada afirmação do projeto pelo grau de sustentação que ela tem no próprio texto.

```
Identifique as afirmações centrais deste projeto e classifique cada uma em:

CLASSE A — sustentada no próprio texto por citação, dado ou justificativa
explícita.
CLASSE B — sustentação parcial: a fonte existe, mas o vínculo com a
afirmação é frágil ou indireto.
CLASSE C — afirmada sem sustentação alguma, ou apoiada em premissa
implícita.

Para cada item da CLASSE C, indique: (a) o trecho exato, (b) o que a
banca poderia contestar, (c) que tipo de sustentação resolveria o problema.
```

## Prompt 4 — Lacunas de literatura ⚠️

> Útil e perigoso na mesma medida: é **aqui que a IA mais inventa referências**. Verifique cada sugestão no Google Scholar antes de citar.

```
Analise a fundamentação teórica deste projeto sobre [TEMA].

Quais autores, obras ou debates centrais da área estão ausentes ou
subrepresentados? Aponte apenas ausências que um especialista da área
notaria — não liste autores tangenciais para preencher a resposta.

Para cada ausência apontada, declare seu nível de confiança de que a
referência existe e é central ao tema (alto / médio / baixo) e o que
eu deveria verificar antes de citá-la.
```

## Prompt 5 — Pré-mortem de viabilidade

> Em vez de perguntar "o que pode dar errado?", declara que já deu errado e pede a autópsia.

```
Avance 6 meses no futuro. Assuma como FATO ABSOLUTO que a banca de
qualificação reprovou este projeto por inviabilidade. Não questione SE
foi reprovado — a reprovação já aconteceu.

Escreva o relatório de autópsia:
1. Causa principal: qual premissa do cronograma, da amostra/corpus ou
   do método se provou falsa?
2. Ponto cego: que variável externa, ignorada no projeto, contribuiu
   para a reprovação?
3. Ajuste: reescreva apenas a parte inviável, mitigando especificamente
   esses riscos.
```

---

## Três ressalvas que ninguém publica junto com os prompts

1. **Crítica sem trecho citado costuma ser crítica inventada.** Modelos de linguagem preenchem o formato pedido mesmo quando não têm o que dizer. Se a IA apontar uma fragilidade sem localizá-la no seu texto, desconfie.
2. **Referências sugeridas pela IA podem não existir.** O Prompt 4 é onde os modelos mais alucinam: inventam autores, títulos e anos com fluência perfeita. Confirme tudo no Google Scholar ou na base da sua área.
3. **Isto não substitui seu orientador.** Os prompts encontram lacunas formais — alinhamento, sustentação, viabilidade. Eles não sabem o que a sua banca específica valoriza. Use a IA para chegar mais preparado à conversa humana, não para substituí-la.

---

## Origem

Os prompts 1, 3 e 5 adaptam as técnicas **Ator-Observador**, **Granularidade Calibrada** e **Pré-Mortem Cognitivo** do livro ***IA Confiável***, de Sérgio Camargos (Edições Zopyra, 2026 — [disponível na Amazon](https://www.amazon.com.br/CONFI%C3%81VEL-DEFINITIVO-IDENTIFICAR-Fundamentos-Metacognitiva-ebook/dp/B0GN9KLHXG)) — um método completo para extrair de qualquer IA não só respostas, mas os sinais de confiabilidade dessas respostas.

🔗 [zopyra.com.br](https://zopyra.com.br)


## Licença

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.pt-br) — compartilhe e adapte livremente, com atribuição a **Sérgio Camargos / zopyra.com.br**. Veja [LICENSE.md](LICENSE.md).
