# Exemplos

Situações fictícias, para calibrar o formato. Adapte o vocabulário ao time e ao líder.

## 1. Reconhecimento

**Pedido do líder:** "Quero elogiar a analista de suporte que resolveu o problema da empresa cliente ontem."

**Situação:** Ontem à tarde, no chamado da empresa cliente que estava sem acesso ao Portal RH.
**Comportamento:** Você reproduziu o erro, identificou que era a configuração de permissão, acionou o time de produto com o passo a passo e manteve o RH do cliente informado a cada hora.
**Impacto:** O acesso voltou em três horas, o cliente agradeceu no canal e o time de produto corrigiu a causa sem precisar pedir mais informação.

**Como falar**
> "Quero te agradecer pelo chamado de ontem. Você reproduziu o erro, mandou o passo a passo pro produto e manteve o cliente informado o tempo todo. Por causa disso, resolvemos em três horas e o cliente saiu satisfeito. Esse cuidado com a comunicação é exatamente o que queremos no time — continue assim."

## 2. Ajuste pontual

**Pedido do líder:** "O dev apresentou a demo sem testar e deu erro na frente da diretoria."

**Situação:** Na demo da sprint para a diretoria, na quinta-feira.
**Comportamento:** A funcionalidade foi apresentada direto no ambiente de homologação sem um teste prévio do fluxo, e o cadastro falhou duas vezes durante a apresentação.
**Impacto:** Usamos 15 minutos da reunião tentando contornar o erro, a diretoria saiu sem ver o fluxo completo e a aprovação para produção ficou para a próxima semana.

**Como falar**
> Abertura: "Quero conversar sobre a demo de quinta, porque acho que a gente consegue evitar aquele aperto nas próximas."
> SBI: "Na demo pra diretoria, o fluxo foi apresentado sem um teste antes, e o cadastro falhou duas vezes. Perdemos uns 15 minutos e a aprovação ficou pra semana que vem."
> Pergunta: "Como foi pra você? Teve algo que impediu o teste antes?"
> Acordo: "O que você acha de a gente rodar o fluxo completo uma hora antes de cada demo?"
> Apoio e acompanhamento: "Posso deixar esse horário bloqueado na agenda do time. Na próxima demo a gente vê como foi."

## 3. Padrão recorrente

**Pedido do líder:** "Ela sempre atrasa nas dailies."

Pergunta necessária antes de escrever: "Você consegue apontar dois ou três dias específicos?" → Líder: "Segunda, quarta e sexta da semana passada, entre 10 e 15 minutos."

**Situação:** Nas dailies de segunda, quarta e sexta da semana passada.
**Comportamento:** Você entrou entre 10 e 15 minutos depois do início.
**Impacto:** Nas três, repetimos a atualização das tarefas para te incluir e a daily, que é de 15 minutos, passou de 25.

**Como falar**
> Abertura: "Quero falar sobre o horário das dailies, porque quero entender se tem algo atrapalhando."
> SBI: (como acima)
> Pergunta: "Tem algo acontecendo no início do dia que dificulta? O horário funciona pra você?"
> Acordo: "Se o horário for o problema, a gente pode avaliar mudar. Se não, combinamos que você entra no horário ou avisa antes no canal."
> Acompanhamento: "Vamos ver como estão as próximas duas semanas."

**Nota:** se na conversa surgirem sinais de que algo maior está acontecendo (cansaço extremo, problema pessoal, sofrimento), pause o feedback e mude para acolhimento — skill `guia-lider-acolhimento`.

## 4. Revisão de rascunho

**Rascunho do líder:**
> "Você é muito desorganizado e parece que não liga pro time. A documentação da API está sempre incompleta e todo mundo reclama."

**Ajustes de linguagem**
- "você é muito desorganizado" → removido — é rótulo de personalidade, não comportamento.
- "parece que não liga pro time" → removido — supõe intenção; a pessoa vai se defender disso em vez de ouvir o resto.
- "sempre incompleta" → "na documentação do endpoint de agendamento, publicada na terça, faltavam os códigos de erro" — situação específica.
- "todo mundo reclama" → "o time do app precisou te procurar duas vezes para entender os erros 409 e 422" — impacto concreto, sem invocar terceiros genéricos.

**Versão SBI**
> "Na documentação do endpoint de agendamento que você publicou na terça, faltavam os códigos de erro. O time do app precisou te procurar duas vezes pra entender os erros 409 e 422, e a integração atrasou um dia. Como você vê isso? O que ajudaria a documentação sair completa — um template, um checklist no PR?"

## 5. Caso que não é feedback

**Pedido do líder:** "Preciso dar um feedback pra uma pessoa que tem chorado no trabalho e as entregas caíram."

**Resposta esperada:** Não escrever feedback corretivo agora. Explicar em poucas linhas que choro e queda de desempenho juntos sugerem sofrimento, e que acolher primeiro aumenta a chance de a pessoa se recuperar e de o desempenho voltar. Conduzir o líder com a skill `guia-lider-acolhimento` e oferecer retomar o feedback depois, se ainda for necessário.
