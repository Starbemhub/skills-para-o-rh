# Skills para o RH

Skills do Claude para apoiar o RH e as lideranças de qualquer empresa. Feito pela Starbem.

| Skill | Para quê |
|---|---|
| [`guia-lider-acolhimento`](guia-lider-acolhimento/SKILL.md) | Acolher e encaminhar um colaborador em sofrimento emocional, com protocolo de urgência para trabalho presencial e remoto |
| [`feedback-sbi`](feedback-sbi/SKILL.md) | Preparar feedback de desempenho no modelo Situação–Comportamento–Impacto, com checagem de risco no meio do caso |

**Cada skill funciona sozinha.** As duas trazem o essencial uma da outra: o `feedback-sbi` inclui um resumo de acolhimento e o protocolo de risco; o `guia-lider-acolhimento` inclui o básico do feedback SBI. Instalar as duas só aprofunda cada tema.

## Antes de usar na sua empresa

1. **Mapeie os canais de apoio** que a empresa oferece (benefício de saúde emocional, plano de saúde, RH, medicina do trabalho, canal de ética) e divulgue para os líderes. As skills orientam por tipo de canal e não inventam contatos.
2. **Valide com psicologia/saúde, RH e jurídico/DPO** o protocolo de urgência e as orientações de registro (LGPD).
3. **Teste com alguns líderes** usando casos reais anonimizados e ajuste a linguagem.

## Guardrails comuns

- Nenhuma skill faz diagnóstico, prescrição ou orientação clínica individual.
- Decisões sobre pessoas (afastamento, advertência, desligamento, nota) ficam com humanos e com o RH.
- Dado de saúde é dado pessoal sensível (LGPD, art. 5º, II): não registrar sintomas, diagnósticos ou medicações; não usar o nome do colaborador no chat.
- Em risco à vida: **SAMU 192** (informando a cidade da pessoa, se ela estiver em outro lugar) e **CVV 188**.
- Exemplos usam campos entre colchetes, nunca fatos inventados.

## Estrutura

```
<skill>/
├── SKILL.md          # instruções principais (frontmatter com name e description)
└── references/       # material carregado sob demanda
```

## Como instalar

Cada pasta é uma skill independente. Para usar no Claude, compacte a pasta da skill (ou use o arquivo `.skill`) e envie em **Configurações → Capacidades → Skills**, ou distribua pela organização.
