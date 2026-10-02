# Automação de Conteúdo SEO com IA no n8n

Template de uma automação que transforma uma pauta em conteúdo SEO estruturado, gera ou seleciona imagens e prepara a publicação no WordPress.

## Problema resolvido

Produzir conteúdo para blog costuma exigir etapas manuais repetitivas: selecionar palavras-chave, construir a estrutura do artigo, gerar texto, preparar imagens, configurar categorias e publicar. Este fluxo organiza essas etapas em uma única automação rastreável.

## Fluxo

```text
Agendamento ou execução manual
  -> Google Sheets: leitura da pauta
  -> IA: estrutura, conteúdo e FAQ
  -> Fontes de imagem / geração de imagem
  -> Tratamento e upload de mídia
  -> WordPress: post, categorias e tags
  -> Google Sheets: atualização de status e tratamento de erro
```

## Tecnologias e integrações

- n8n
- Google Sheets
- Modelos de IA e saída estruturada em JSON
- APIs de geração ou busca de imagens
- WordPress REST API
- JavaScript nos nós Code

## Como importar

1. No n8n, importe `workflow.template.json`.
2. Crie suas próprias credenciais para Google Sheets, modelos de IA, imagens e WordPress.
3. Substitua todos os campos `REPLACE_WITH_*` e URLs `example.invalid`.
4. Execute primeiro com gatilho manual e dados de teste.
5. Ative o agendamento somente depois de validar o fluxo completo.

## Segurança e escopo

Este é um template de portfólio derivado de um fluxo real. Credenciais, IDs, endpoints, links, mensagens e dados de clientes foram removidos intencionalmente. O workflow está inativo por padrão e exige configuração própria antes de qualquer execução.

