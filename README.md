# MedFlow — Protótipo de recepção hospitalar com IA

Protótipo acadêmico de recepção hospitalar digital, com fluxo para pacientes e painel da recepção, desenvolvido em HTML, CSS e JavaScript.

## O que é
-------
Protótipo de alta fidelidade em HTML/CSS/JS puro (sem dependências nem
build) de uma plataforma de recepção hospitalar inteligente, com três partes:

- index.html ............ hub de acesso ao protótipo
- patient.html .......... fluxo completo do paciente
  (identificação → motivo → conversa com IA → encaminhamento → resumo → confirmação)
- dashboard.html ........ painel da recepção (KPIs, lista de atendimentos,
  dados coletados pela IA e ações: assumir, encaminhar, finalizar)
- design-system.html .... biblioteca de design (cores, tipografia, componentes)

Como abrir
----------
1. Baixe o repositório e abra index.html no navegador
2. Dentro da pasta MedFlow, abra o arquivo index.html em um navegador
(Chrome, Edge ou Firefox).
Para ver a integração entre as telas, abra o fluxo do paciente e o
dashboard em duas abas do mesmo navegador: um atendimento concluído pelo
paciente aparece no dashboard com um aviso.

Regras do protótipo
-------------------
- A IA nunca diagnostica e nunca inventa informação: sempre que não tem
  certeza, encaminha para atendimento humano, com número de atendimento.
- Status sempre exibidos com texto e ícone (nunca apenas cor).
- Fluxo do paciente com opção de idioma (português, inglês, espanhol).
- Acessibilidade: navegação por teclado, foco visível, labels em todos os
  campos e um objetivo por tela.

Dados
-----
Os atendimentos ficam salvos no navegador (localStorage). Para voltar ao
estado inicial do dashboard, é só limpar os dados do site no navegador.
