# MedFlow — Protótipo de recepção hospitalar

Protótipo acadêmico desenvolvido em HTML, CSS e JavaScript.

## O que é

Protótipo de alta fidelidade de uma plataforma para organizar o atendimento hospitalar. Inclui:

- `index.html`: página inicial do protótipo
- `patient.html`: fluxo do paciente, da identificação à confirmação do atendimento
- `dashboard.html`: painel da recepção com lista e status dos atendimentos
- `design-system.html`: biblioteca de cores, tipografia e componentes

A conversa apresentada como IA é simulada por regras e opções predefinidas.

## Como abrir

1. Baixe e extraia o repositório.
2. Na pasta do repositório, abra `index.html` em um navegador.
3. Para ver a integração, abra `patient.html` e `dashboard.html` em duas abas do mesmo navegador. Os atendimentos concluídos pelo paciente aparecem no painel.

## Regras do protótipo

- Não realiza diagnósticos; encaminha para atendimento humano quando necessário.
- Exibe o status com texto e ícone.
- Oferece português, inglês e espanhol.
- Inclui navegação por teclado, foco visível e campos identificados.

## Dados

Os atendimentos ficam salvos no navegador (`localStorage`). Para restaurar os dados iniciais do painel, limpe os dados do site no navegador.
