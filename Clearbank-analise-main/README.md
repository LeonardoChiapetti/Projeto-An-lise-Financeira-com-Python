# Análise Financeira com Python

## Descrição

Este projeto foi desenvolvido como desafio final do módulo de Python para Análise de Dados. O objetivo é realizar a leitura, validação e análise de transações financeiras a partir de um arquivo CSV, gerando métricas mensais e exportando um relatório em formato JSON.

## Funcionalidades

* Leitura de arquivos CSV utilizando o módulo nativo `csv`;
* Validação e limpeza dos dados;
* Cálculo de métricas financeiras mensais;
* Identificação de transações suspeitas;
* Exibição de um relatório formatado no terminal;
* Geração do arquivo `relatorio.json`.

## Como executar

1. Abra o notebook no **Google Colab**.
2. Faça o upload do arquivo `Transacoes.csv` para o seu Google Drive.
3. Atualize a variável `CAMINHO_ARQUIVO` no notebook para apontar para o local onde o arquivo foi salvo em seu Google Drive.
4. Monte o Google Drive no Colab, caso ainda não esteja montado.
5. Execute todas as células do notebook em ordem.

> **Observação:** O caminho configurado no notebook corresponde ao meu Google Drive. Caso o projeto seja executado em outro ambiente ou por outro usuário, será necessário ajustar apenas a variável `CAMINHO_ARQUIVO` para o local onde o arquivo `Transacoes.csv` estiver armazenado.

## Arquivos gerados

* `relatorio.json` contendo o resumo da análise financeira.

## Tecnologias utilizadas

* Python 3
* csv
* json
* datetime
