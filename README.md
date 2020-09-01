WorkSearch
=========

Projeto Código-Aberto de Sistema de Boletos bancários em PHP

## Qual o principal motivo deste projeto?
Este projeto foi criado por Elizeu Alcantara desde Maio/2006 e teve origem do Projeto BBBoletoFree que tiveram colaborações de Daniel William Schultz e Leandro Maniezo que por sua vez foi derivado do PHPBoleto de João Prado Maia e Pablo Martins F. Costa.

Criar um sistema de geração de Boletos que seja mais simples do que o PhpBoleto e que se estenda ao desenvolvimento de boletos dos bancos mais usados no mercado, além do Banco do Brasil do projeto BBBoletoFree. Este sistema é de Código Aberto e de Livre Distribuição conforme Licença GPL.

Este projeto visa atender exclusivamente aos profissionais e desenvolvedores na área técnica de programação PHP dos boletos, portanto se faz necessário conhecimento desejado e estudo do mesmo para a perfeita configuração do boleto a ser usado, sendo de inteira responsabilidade do profissional a instalação, funcionamento, testes e compensação do mesmo em conta bancária, pois não damos suporte técnico, portanto mensagens enviadas a nós com dúvidas gerais, técnicas ou solicitações de Suporte não serão respondidas.

O projeto BoletoPhp não tem foco na questão administrativa, comercial ou jurídica, pois isto compete exclusivamente aos bancos devido as suas particularidades existentes de cada carteira de cada boleto. Maiores informações sobre o conceito de Boleto de Cobrança, você pode acessar aqui o site da Wikipédia

## Qual a principal idéia deste projeto?
Padronizar um formato simples de geração de boletos de cada banco baseado em um padrão composto somente de 3 arquivos php

Tomamos como exemplo o Boleto do Caixa Econômica, onde temos:

- boleto_cef.php : Aqui ficam os DADOS usados para a geração do boleto
- layout_cef.php : Aqui fica a estrutura HTML para a geração do boleto
- funcoes_cef.php : Aqui ficam as FUNÇOES usadas para a geração do boleto 

## Este conceito do BoletoPHP facilita a criação de boletos de outros bancos?
Sim, pois facilita para um desenvolvedor para que seja dado continuidade no Projeto BoletoPHP para o desenvolvimento dos demais bancos, pois o principal trabalho para criar o boleto de um novo banco é criar o arquivo php de funções ( no caso acima o funcoes_cef.php) , onde estão as regras de cada banco para a geração das 2 principais informações do boleto que são a Linha Digitável e o Código de Barras, já que no layout_xxxx.php muda apenas a logo do banco e no arquivo boleto_xxxx.php acrescenta poucas variáveis específicas de cada banco.

## Integrantes da Equipe
- Germano Manente Neto
- Matheus Gavelli (preencher o nome completo)
- Bruno (preencher o nome completo)
- Thiago (preencher o nome completo)

## Cronograma de Desenvolvimento - Projeto Integrador I

| Atividade                                       | Fase RUP  |   %  | Início     | Término    |
|-------------------------------------------------|-----------|------|------------|------------|
|Diagrama de Problema/Solução                     | Iniciação | 100% | 05/08/2019 | 08/08/2019 |
|Plano de Negócio                                 | Iniciação | 100% | 08/08/2019 | 10/08/2019 |
|Canvas de Negócio                                | Iniciação | 100% | 10/08/2019 | 14/08/2019 |
|Mapeamento de Processos                          | Iniciação | 30%  | 14/08/2019 | 19/08/2019 |
|Fluxo do Modelo de Processos de Negócio (BPMN)   | Iniciação | 25%  | 19/08/2019 | 24/08/2019 |
|Descritivo de Análise do Processo                | Iniciação | 70%  | 24/08/2019 | 29/08/2019 |
|Desenho do Processo de Negócio - Diagrama (BPMN) | Iniciação | 50%  | 09/08/2019 | 11/08/2019 |
|-------------------------------------------------|-----------|------|------------|------------|
## Cronograma de Desenvolvimento - Projeto Integrador II

| Atividade                                       | Fase RUP  |   %  | Início     | Término    |
|-------------------------------------------------|-----------|------|------------|------------|
|Documento de Visão do Software	                  | Concepção | 0%   | 17/02/2020 | 30/06/2020 |
|Especificação de Regras de Negócio	              | Concepção | 0%   | 18/02/2020 | 01/07/2020 |
|Glossário	                                      | Concepção | 0%	 | 19/02/2020 | 02/07/2020 |
|Planilha de Contagem de Pontos de Função         | Concepção | 0%	 | 20/02/2020 | 03/07/2020 |
|Documento de Aspectos Críticos de Segurança*	  | Concepção | 0%   | 21/02/2020 | 04/07/2020 |
|Estratégia de Desenvolvimento (Escolha)	      | Concepção | 0%   | 22/02/2020 | 05/07/2020 |
|Ambiente Virtual Colaborativo Criado*	          | Concepção | 0%   | 23/02/2020 | 06/07/2020 |
|Plano de Iteração	                              | Concepção | 0%   | 24/02/2020 | 07/07/2020 |
|Plano de Teste	                                  | Concepção | 0%	 | 25/02/2020 | 08/07/2020 |
|Plano de Sustentação de Software	              | Concepção | 0%   | 26/02/2020 | 09/07/2020 |
|Parecer de Infraestrutura de TI	              | Concepção | 0%   | 27/02/2020 | 10/07/2020 |
|Especificação de Requisitos	                  | Concepção | 0%   | 28/02/2020 | 11/07/2020 |
|Diagrama de Casos de Uso	                      | Concepção | 0%   | 29/02/2020 | 12/07/2020 |
|Protótipos de Tela 	                          | Concepção | 0%   | 01/03/2020 | 13/07/2020 |
|-------------------------------------------------|-----------|------|------------|------------|
## Cronograma de Desenvolvimento - Projeto Integrador III
|-------------------------------------------------|-----------|------|------------|------------|
| Atividade                                       | Fase RUP  |   %  | Início     | Término    |
|-------------------------------------------------|-----------|------|------------|------------|
Especificação de Caso de Uso                      | Elaboração| 0%   | 15/08/2020 | 13/12/2020 |
Contagem de Referência (FPA)                      | Elaboração| 0%   | 16/08/2020 | 14/12/2020 |
Plano de Gerenciamento de Requisitos              | Elaboração| 0%   | 17/08/2020 | 15/12/2020 |
Planilha de Rastreabilidade                       | Elaboração| 0%   | 18/08/2020 | 16/12/2020 |
Diagrama de Classes	                              | Elaboração| 0%   | 19/08/2020 | 17/12/2020 |
Diagrama de Sequência                             | Elaboração| 0%   | 20/08/2020 | 18/12/2020 |
Diagrama de Colaboração	                          | Elaboração| 0%   | 21/08/2020 | 19/12/2020 |
Documento de Arquitetura do Software              | Elaboração| 0%   | 22/08/2020 | 20/12/2020 |
Parecer de Segurança da Informação                | Elaboração| 0%   | 23/08/2020 | 21/12/2020 |
Plano de Testes	                                  | Elaboração| 0%   | 24/08/2020 | 22/12/2020 |
Modelo de Dados	                                  | Elaboração| 0%   | 25/08/2020 | 23/12/2020 |
Casos de Teste	                                  | Elaboração| 0%   | 26/08/2020 | 24/12/2020 |
Plano de Implantação                              | Elaboração| 0%   | 27/08/2020 | 25/12/2020 |
|-------------------------------------------------|-----------|------|------------|------------|