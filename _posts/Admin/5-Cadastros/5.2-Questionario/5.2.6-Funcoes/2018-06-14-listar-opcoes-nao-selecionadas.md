---
layout: post
title:  "Listar Opções não Selecionadas"
projeto: "fastQuestAdmin"
permalink: /fastQuestAdmin/funcoes/listar-opcoes-nao-selecionadas
pasta: "funcoes"
mainsection: 5.26
section: 5.2627
---
# $FUNCAO_RETORNA_OPCOES_NAO_SELECIONADAS (NRQUESTAO)
*Esta função está deprecada, utilizar **<a href="/fastQuestAdmin/funcoesv2/listarOpcoes">Listar Opções</a>***

Independente de ser uma RU ou RM devolve a lista de opções que não foram selecionadas separadas por pipe. 
Obs. caso queira uma lista de opções selecionadas consulte __$FUNCAO_RETORNA_RESPOSTA__

- Parâmetros: 
    - NRQUESTAO: código da questão
- Exemplo:
    - *IF ($FUNCAO_EXECUTA_ACAO(OCULTAROPCAO;Q11)($FUNCAO_RETORNA_OPCOES_NAO_SELECIONADAS(Q10))*
- Resultado:
    - Supondo que a questão Q10 possuí as seguintes opções e a opção 3 foi selecionada: 
        1. Sim
        2. Talvez
        3. **_Não tenho certeza_**
        4. Não mesmo
        5. Recusa responder
    - O resultado será: 1\|2\|4\|5
