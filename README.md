# Hub de Skills para RH — Starbem

Skills do Claude para apoiar o RH interno e as lideranças da Starbem.

| Skill | Para quê | Status |
|---|---|---|
| [`guia-lider-acolhimento`](guia-lider-acolhimento/SKILL.md) | Acolher e encaminhar um colaborador em sofrimento emocional, com protocolo de urgência | Carro-chefe · v1 |
| [`feedback-sbi`](feedback-sbi/SKILL.md) | Preparar feedback de desempenho no modelo Situação–Comportamento–Impacto | Complemento · v1 |

As duas skills se conectam: quando um feedback revela sinais de sofrimento, o `feedback-sbi` direciona para o `guia-lider-acolhimento` antes de qualquer feedback corretivo.

## Antes de publicar para os líderes

1. **Preencher os contatos internos** em [`guia-lider-acolhimento/references/contatos.md`](guia-lider-acolhimento/references/contatos.md). Enquanto houver `[PREENCHER]`, a skill orienta o líder a procurar o RH e não inventa canais.
2. **Validar com psicologia/saúde, RH e jurídico/DPO** o conteúdo do protocolo de urgência e as orientações de registro (LGPD).
3. **Testar com 3 a 5 líderes** usando casos reais anonimizados e ajustar a linguagem.

## Guardrails comuns

- Nenhuma skill faz diagnóstico, prescrição ou orientação clínica individual.
- Decisões sobre pessoas (afastamento, advertência, desligamento, nota) ficam com humanos e com o RH.
- Dado de saúde é dado pessoal sensível (LGPD, art. 5º, II): não registrar sintomas, diagnósticos ou medicações; não usar nome do colaborador no chat.
- Em risco à vida: SAMU 192, CVV 188, e o protocolo de urgência.

## Estrutura

```
<skill>/
├── SKILL.md          # instruções principais (frontmatter com name e description)
└── references/       # material carregado sob demanda
```

## Como instalar

Cada pasta é uma skill independente. Para usar no Claude, compacte a pasta da skill (ou use o arquivo `.skill` gerado) e envie em **Configurações → Capacidades → Skills**, ou distribua pela organização.
