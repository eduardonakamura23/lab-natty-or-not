# 06 — Vídeo: produção no Codex com Pika.art

## Objetivo

Comercial vertical de 15 segundos para Briefing Blend — Creative Roast. Narrativa: bloqueio criativo → ritual do café → retomada do foco → produto → assinatura.

## Base documental e execução

Este registro utiliza os prompts e o estado de produção salvos em 09–10/09/2026, além da seleção do usuário. Os textos nos blocos abaixo foram copiados dos arquivos de produção; os nomes V01/V02 representam tentativas reais. Não houve novas gerações durante a organização do repositório.

O Codex conduziu a produção pelo site Pika.art. Foram registradas sete gerações concluídas com Pika 2.5, cada uma solicitada com 5 segundos e resolução 480p. Os arquivos retornados tinham 470 × 784 e aproximadamente 5,03 segundos. As cenas 1 e 2 usaram texto para vídeo; as demais tentativas usaram imagem de referência.

| Cena | Gerações efetivas | Resultado da seleção |
|---|---|---|
| 1 — Bloqueio | V01 | V01, 0–3s no filme |
| 2 — Ritual | V01 | V01, 3–6s |
| 3 — Lifestyle | V01 e V02 | V01 escolhida pelo usuário, 6–10s |
| 4 — Hero Shot | V01 e V02 | V01 escolhida pelo usuário, 10–13s |
| 5 — Encerramento | V01 no Pika | Substituída por cartela V02 local, 13–15s |

O [Hero Shot](../assets/product/hero-shot.png) e o [Lifestyle](../assets/product/lifestyle.png) foram adaptados por expansão do cenário antes do envio. Prompts dessa preparação: [fotografia de produto](03-product-photography.md) e [Lifestyle](04-lifestyle.md). As referências utilizadas estão em [Hero vertical](../assets/video/references/hero-shot-vertical-v01.png) e [Lifestyle vertical](../assets/video/references/lifestyle-vertical-v01.png).

## Cena 1 — Bloqueio criativo, V01

Prompt preservado em `cena-01.txt` no pacote de produção:

```text
Comercial cinematográfico hiper-realista de uma marca premium de café. Um jovem profissional criativo adulto está sentado em um home office minimalista e contemporâneo pela manhã. Cabelo castanho escuro levemente ondulado, barba curta bem cuidada, óculos discretos e camisa preta minimalista. Mesa organizada com notebook aberto, caderno, caneta e caneca de cerâmica. Paleta creme, preto carvão, madeira clara e marrom café.

O plano começa em enquadramento médio, mostrando o personagem e parte do notebook. Ele olha a tela com concentração e um pequeno bloqueio criativo. Durante alguns instantes permanece pensando, com respiração e pequenos movimentos oculares naturais, sem conseguir avançar. A dúvida e a leve frustração são discretas e contidas. Termina ainda contemplando a tela, permitindo um corte para o ritual do café.

Câmera: um único push-in extremamente lento e suave em direção ao personagem, sem cortes internos. Luz natural quente da manhã entrando lateralmente por uma janela grande, sombras suaves, profundidade de campo rasa, pele e materiais naturais, fotografia editorial sofisticada.

Preservar rosto, roupa, objetos, exposição e direção da luz ao longo do plano. Não mostrar texto legível no notebook, legendas ou logotipos. Não adicionar outras pessoas. Evitar mãos deformadas, dedos extras, objetos duplicados, expressões exageradas, elementos surreais ou movimento rápido da câmera.
```

Resultado: personagem diante do notebook em ambiente quente; o gesto de mão no rosto reforça o bloqueio. A montagem utiliza os três segundos finais do take.

## Cena 2 — Ritual do café, V01

Prompt preservado em `cena-02.txt`:

```text
Comercial cinematográfico hiper-realista de café premium. Close macro extremamente detalhado do preparo artesanal de café em um dripper minimalista. O enquadramento começa focado na superfície do café recém-moído.

Água quente é despejada lentamente e de maneira controlada sobre o pó. O café inicia naturalmente o blooming, pequenas bolhas surgem, o pó absorve a água gradualmente e a extração se desenvolve. Um vapor muito suave sobe. A ação termina com a superfície úmida expandida e o fluxo estabilizado. Mostrar textura realista, gravidade e movimento fisicamente correto da água, pequenos reflexos naturais sobre o líquido.

Câmera: um pequeno push-in cinematográfico contínuo e muito lento durante o blooming. Profundidade de campo muito rasa e bokeh natural. Luz quente lateral suave da manhã, paleta creme, preto, madeira clara e marrom café. Sensação íntima, sensorial e sofisticada, fotografia profissional de lente macro.

Não gerar texto, logotipo ou embalagem. Não exagerar o vapor, criar respingos irreais ou movimentos fisicamente impossíveis. Evitar mãos deformadas, dedos extras, aparência artificial do líquido ou elementos fantasiosos.
```

Resultado: close de água chegando ao pó e expansão do café. A montagem utiliza um trecho de três segundos.

## Cena 3 — Lifestyle, V01

Prompt enviado, preservado em `cena-03.txt`:

```text
Anime a fotografia de referência preservando a identidade do personagem, a embalagem, a mesa, os objetos, a iluminação e a composição. A fotografia determina a pose inicial. Preserve rosto, cabelo castanho escuro ondulado, barba curta, óculos, roupa preta e proporções corporais. Mantenha o mesmo notebook, caderno, caneca e ambiente criativo.

Comece exatamente na posição de trabalho da fotografia. O personagem interrompe calmamente a escrita, apoia a caneta, pega a caneca de cerâmica, toma um pequeno gole, coloca a caneca de volta e volta sua atenção para o notebook. Ele inicia a digitação com naturalidade, concentração e propósito. A mudança emocional é muito sutil: contemplativo no começo e discretamente mais focado ao final. A ação tem preparação e repouso; nada de sorriso exagerado ou transformação dramática.

Câmera: deslocamento lateral muito suave durante o gesto com a caneca, desacelerando para um pequeno avanço final quando o personagem volta ao trabalho. Preservar luz quente lateral da manhã, profundidade de campo rasa e fotografia editorial premium.

A embalagem deve permanecer estável e idêntica à referência, com formato, proporções, cores, logotipo, tipografia, textos e linhas gráficas intactos. Preservar também a headline já presente na imagem. Não gerar novos textos ou duplicar a headline. O café é um ritual de concentração: sem partículas, brilhos mágicos ou efeitos fantasiosos. Não modificar rosto, roupa ou cenário. Evitar mãos deformadas, dedos extras e objetos que surgem ou desaparecem.
```

Problema observado: movimento de câmera maior que o solicitado, embalagem parcialmente cortada e headline fora de quadro ao final.

### Refinamento V02

Prompt enviado, preservado em `cena-03-v02.txt`:

```text
Plano único de 5 segundos com CÂMERA TOTALMENTE FIXA EM TRIPÉ. Anime a fotografia de referência sem alterar seu enquadramento: preserve exatamente a distância focal, a escala dos objetos e a composição vertical original do primeiro ao último quadro. ZERO zoom, ZERO avanço, ZERO deslocamento lateral, ZERO panorâmica, ZERO reenquadramento, ZERO cortes. A embalagem inteira, incluindo suas bordas e base, e a frase inteira "Your next idea starts here." devem permanecer visíveis nas mesmas posições até o último quadro. O produto e a frase são elementos estáticos.

Apenas o homem se movimenta discretamente dentro dessa composição fixa. Preserve seu rosto, cabelo castanho escuro ondulado, barba curta, óculos e roupa preta. Partindo da pose de escrita da fotografia, ele apoia a caneta, pega a caneca de cerâmica já existente, toma um pequeno gole, devolve a mesma caneca ao mesmo lugar e volta sua atenção ao notebook, iniciando a digitação. Gestos econômicos e naturais, sem pressa, sem sorriso exagerado. Não mover ou substituir outros objetos.

Preserve integralmente a embalagem Briefing Blend: formato, proporções, logo, textos, tipografia, cores e linhas gráficas. Preserve a headline existente, sem duplicá-la ou modificá-la. Mantenha a luz quente lateral da manhã, a profundidade de campo e a fotografia editorial original. Sem mudanças de foco ou iluminação. Sem novas letras, objetos, partículas ou efeitos mágicos. Sem mãos deformadas ou dedos extras.

A prioridade absoluta é manter o enquadramento inicial inalterado durante todo o vídeo, com embalagem e headline sempre inteiras. A câmera permanece imóvel mesmo quando o homem toma café ou olha para o notebook.
```

Resultado: movimento reduzido, mas ainda houve deriva do enquadramento e perda da headline. A correção foi parcial. O usuário escolheu V01, que permanece no vídeo final com esse comportamento.

## Cena 4 — Hero Shot, V01

Prompt enviado, preservado em `cena-04-v01.txt`. Esta versão acrescenta o limite de aproximação de 3% ao rascunho de produção:

```text
Anime a fotografia publicitária preservando com máxima fidelidade a embalagem original do Briefing Blend. O primeiro quadro deve corresponder à referência. A embalagem permanece imóvel, com o mesmo formato, proporções, acabamento preto fosco, logotipo, tipografia, paleta, layout, ícone, textos e elementos gráficos. Não redesenhar nenhuma parte da embalagem.

O movimento vem exclusivamente de um push-in cinematográfico muito lento em direção ao produto, com deslocamento lateral mínimo no mesmo percurso para criar profundidade. Aproximação total muito pequena, de no máximo 3%, mantendo todas as bordas e a base da embalagem visíveis, com margem durante os 5 segundos. A câmera termina em um enquadramento estável e utilizável do produto. Luz quente lateral, reflexos discretos e contínuos, profundidade de campo rasa, fundo creme minimalista. Se a xícara aparecer, permitir apenas quantidade mínima e realista de vapor. Grãos e demais objetos permanecem imóveis.

Fotografia premium de produto, aparência de filmagem em estúdio profissional. Não alterar palavras ou logotipo, deformar ou duplicar embalagem, girar o produto, adicionar objetos, partículas, efeitos de brilho ou movimento dramático. Sem cortes ou mudanças de cena. Não adicionar headline ou legenda; preservar somente os textos já presentes na embalagem.
```

Problema observado: a aproximação superou visualmente o limite solicitado, embora a embalagem estivesse inteira nos quadros de início e fim inspecionados.

### Refinamento V02

Prompt enviado, preservado em `cena-04-v02.txt`:

```text
Plano único de produto com câmera fixa em tripé durante os 5 segundos. Preserve exatamente o enquadramento vertical da fotografia de referência: mesma distância, mesma escala e mesma posição da embalagem em todos os quadros. Sem zoom, avanço, deslocamento lateral, panorâmica, rotação ou cortes. A embalagem Briefing Blend permanece inteira e imóvel no centro, com margem ao redor de todas as bordas e da base.

A única animação é um fio muito sutil de vapor natural subindo da xícara ao lado, quase imperceptível, dissipando lentamente. Embalagem, grãos, caderno, caneta, planta e demais objetos permanecem imóveis. Luz quente lateral de manhã constante, sombras suaves estáveis, fotografia publicitária premium hiper-realista.

Preserve sem alterações o acabamento preto fosco, formato, proporções, logotipo BRIEFING BLEND, CREATIVE ROAST e todos os textos pequenos, ícone e linhas laranja da embalagem. Não redesenhar letras, substituir palavras, deformar o saco, mudar foco, criar reflexos intensos ou acrescentar elementos. Nenhuma headline ou legenda nova. Não produzir fumaça densa, partículas, brilhos mágicos ou efeitos dramáticos. O último quadro deve manter exatamente a composição e a escala do primeiro.
```

Resultado: enquadramento mais estável, ainda com pequena aproximação. O usuário escolheu V01 para o filme. A revisão não certificou fidelidade de todas as letras pequenas ao longo de todo o take.

## Cena 5 — Tentativa Pika V01

Prompt enviado, preservado em `cena-05-v01.txt`:

```text
Anime a fotografia como packshot final de um comercial premium de café. Preserve integralmente a embalagem Briefing Blend: formato, proporções, cores, acabamento, logotipo, tipografia, textos e identidade visual. A embalagem permanece frontal, perfeitamente estável e idêntica ao primeiro quadro. Mantenha todas as bordas e a base da embalagem inteiras e com margem.

Plano único de 5 segundos. Executar somente um push-in extremamente lento e quase imperceptível nos primeiros 3 segundos, desacelerando até a câmera parar completamente. Nos últimos 2 segundos, manter uma composição limpa e imóvel para a assinatura final que será adicionada na montagem. Preservar o espaço livre acima do produto. Sem deslocamento lateral, rotação, reenquadramento ou cortes. Iluminação quente natural constante, sombras suaves, paleta creme, preto carvão e marrom café, profundidade de campo suave. Ambiente minimalista e sofisticado, produto protagonista absoluto. Objetos e grãos imóveis.

Não adicionar texto ou logotipos externos. Não duplicar produtos, deformar a embalagem, alterar palavras ou letras, adicionar objetos, partículas, efeitos fantasiosos ou movimentos dramáticos. Não fazer fade para preto: terminar com a embalagem visível e estável.
```

Resultado: embalagem inteira e espaço acima do produto; a aproximação continuou levemente durante a pausa solicitada. A revisão identificou repetição da composição da cena 4. Essa versão não integra o comercial final.

### Substituição por cartela local V02

Foi criada uma imagem de produto isolado em fundo carvão para diferenciar o encerramento. Prompt de imagem preservado em `cena-05-v02-image.txt`:

```text
Edit the supplied official Briefing Blend product photograph for the final brand end card of a premium coffee commercial. Preserve the EXACT original coffee package including its silhouette, seams, matte texture, logo, typography, spelling, cream and orange ink, cup icon, contour lines and all label text. Isolate that same package and replace the surrounding scene with a minimalist seamless dark charcoal #1A1A1A studio background and matching dark matte floor, subtly lit by warm soft light from upper left and a gentle rim light separating the black bag. Remove the cup, notebooks, pen, beans, plants, vase, original tabletop and all other props. Front-facing product centered horizontally in the LOWER HALF of a 9:16 portrait composition, occupying about 42 percent of canvas height, bottom of package at 85 percent canvas height. A realistic soft contact shadow anchors the bag. Upper 40 percent of image must be clean dark charcoal negative space for a typographic signature added later; do not put any text there. Do not add any graphics, headline, logo outside the package, particles or decorative elements. This is a still cinematic photorealistic closing product photograph, restrained, premium, tactile. Preserve the existing package words accurately: BRIEFING BLEND, CREATIVE ROAST, 100% ARABICA, IDEIAS COMEÇAM DEPOIS DO CAFÉ., 250 g, CAFÉ TORRADO E MOÍDO. Output 1080x1920 or exact 9:16 portrait.
```

Resultado: [base da cartela final](../assets/video/references/packshot-final-v02.png). Produto e enquadramento ficam estáticos; a assinatura foi composta localmente e recebe entrada suave. Essa cena tem 2 segundos e não foi uma nova geração de vídeo Pika. A base é uma derivação gerada, sem garantia de identidade pixel a pixel com a fotografia original.

## Textos de tela

| Cena | Texto |
|---|---|
| 1 | Briefing aberto. |
| 2 | Ideas: loading... |
| 3 | Your next idea starts here. — já presente na referência |
| 4 | Ideias começam / depois do café. |
| 5 | BRIEFING BLEND / Creative Roast / Fuel your next idea. |

## Locução, trilha e finalização

A locução em português e a trilha instrumental foram geradas no vidIQ dentro do fluxo conduzido pelo Codex. O registro identifica a voz Brian. A montagem local sincronizou frases, compôs textos, adicionou efeitos sonoros sintéticos discretos de água, cerâmica e teclado e exportou o filme. Não se atribui geração de áudio ao Pika.

Texto preservado da locução:

```text
Toda ideia começa em algum lugar.

Às vezes, começa com café.

Um ritual.

Um foco.

Briefing Blend.

Ideias começam depois do café.
```

O texto exato do prompt de geração musical não foi recuperado nos arquivos usados para esta consolidação. Não foi inventada uma versão para preencher essa lacuna.

## Entrega e limites

[Comercial final V01](../assets/video/briefing-blend-commercial-final.mp4): 15 segundos, 1080 × 1920, 30 fps, H.264 e áudio AAC. A entrega amplia os takes de 470 × 784; não é geração nativa em 1080p.

A validação anterior registrada informa 450 quadros decodificados, −16,01 LUFS integrados e −1,48 dBTP de pico verdadeiro. A revisão auditiva de pronúncia e equilíbrio não foi registrada naquela execução. A seleção final conserva as V01 das cenas 3 e 4, conforme escolha do usuário.

## Aprendizados

- Restrições de câmera mais fortes reduziram movimento, mas não garantiram enquadramento totalmente fixo.
- Pedir preservação de embalagem e texto não basta para certificar fidelidade durante toda a animação.
- A comparação de versões e a seleção humana fazem parte do processo; a versão mais recente não é automaticamente a escolhida.
- Uma cartela estática composta localmente deu ao encerramento uma função visual diferente da cena de produto.
- Documentar resolução de origem, seleção e limitações torna o resultado verificável sem prometer perfeição.
