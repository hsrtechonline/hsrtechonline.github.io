---
layout: post
title:  "Verificar Resposta"
projeto: "fastQuestAdmin"
permalink: /fastQuestAdmin/funcoes/verificar-resposta
pasta: "funcoes"
mainsection: 5.26
section: 5.2650
---	
# $FUNCAO_RESPOSTA_NULO_OU_VAZIO (NRQUESTAO)
*Esta função está deprecada, utilizar **<a href="/fastQuestAdmin/funcoesv2/contemOpcoes">Contém Opções</a>***

Verifica se a questão informada possuí resposta caso o retorno seja 1 significa que não há resposta, caso seja 0 significa que já existe resposta

- Parametros: 
    - NrQuestao: identificador da questão
- Exemplo:
![Imagem de apoio 1]({{ "/assets/img/verificar-resposta.jpg" | prepend: site.baseurl }})
- Resultado:
    - Se existir resposta para Q1 o questionário avança para Q2, se não exisitr a mensagem "INFORME UM VALOR" será exibida.
