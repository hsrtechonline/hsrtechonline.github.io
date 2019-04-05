---
layout: post
title:  "Gravar Pontuação"
projeto: "fastQuestAdmin"
permalink: /fastQuestAdmin/funcoes/gravarPontuacao
pasta: "funcoes"
---	

# Gravar Pontuação
*Atribui uma pontuação para uma determinada questão.*

- Sintaxe:
  - `Pontuacao().GravarPontuacao("NRQUESTAO","PONTUACAO")`
- Parâmetros:
  - NRQUESTAO: Código da questão entre aspas duplas ou variável
  - PONTUACAO: Valor decimal com (.) ponto entre aspas duplas ou variável
- Exemplo 1:
  - `Pontuacao().GravarPontuacao("Q1","5.5")`
- Exemplo 2:
  - <pre>
    <code>var nrquestao = (pode ser o retorno de uma função ou estático)
    var pontuacao = (pode ser o retorno de uma função ou estático)
    Pontuacao().GravarPontuacao(nrquestao,pontuacao)<code>
    <pre>