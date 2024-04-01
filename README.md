# Projeto de Mock Data com Mockaroo

## Descrição

Este projeto visa a criação de dados fictícios para fins de testes e desenvolvimento, utilizando a ferramenta online Mockaroo ([https://mockaroo.com/](https://mockaroo.com/)). O objetivo é simular uma base de dados realística que possa ser utilizada para testar aplicações, relatórios, ou qualquer sistema que necessite de dados para funcionamento.

## Estrutura do Projeto

O projeto contém os seguintes arquivos essenciais para a compreensão e replicação dos dados:

1. **Modelagem de Dados (`modelagem.json`)**: Este arquivo contém a estrutura de dados modelada para o projeto, representada em formato JSON. A modelagem inclui pelo menos um registro completo, abrangendo todos os níveis de dados previstos para o projeto.
2. **Prints da Estrutura no Mockaroo (`prints_mockaroo.pdf`)**: Um conjunto de imagens capturadas durante a montagem da estrutura de dados no site do Mockaroo. Estas imagens servem como guia visual para a configuração dos campos, tipos de dados e demais opções escolhidas na plataforma.
3. **Dados Gerados (`dados.json`)**: Arquivo contendo 1000 registros gerados pelo Mockaroo, seguindo a modelagem de dados definida. Este arquivo JSON serve como o resultado final do projeto, pronto para ser utilizado em testes e desenvolvimentos.

## Como Utilizar

Para replicar ou modificar este projeto, siga os passos abaixo:

1. **Estude a Modelagem de Dados**: Abra o arquivo `modelagem.json` e analise a estrutura de dados proposta. Este será o ponto de partida para a criação dos dados fictícios.
2. **Configure o Mockaroo**: Acesse [https://mockaroo.com/](https://mockaroo.com/) e comece a montar a estrutura de dados conforme indicado no arquivo `modelagem.json`. Utilize os prints disponibilizados no arquivo `prints_mockaroo.pdf` como referência para a configuração dos campos e tipos de dados.
3. **Gere os Dados**: Após configurar todos os campos e definições no Mockaroo, gere os 1000 registros. Certifique-se de exportar os dados no formato JSON.
4. **Utilize os Dados Gerados**: Com o arquivo `dados.json` em mãos, você pode começar a utilizar os dados fictícios gerados para seus testes, desenvolvimento de aplicações, análises, entre outros.

## Contribuições

Contribuições para o projeto são bem-vindas. Se você identificar melhorias, seja na modelagem de dados, na documentação ou na estrutura dos dados gerados, fique à vontade para propor mudanças ou adições.

## Licença

Este projeto é distribuído sob a licença MIT. Sinta-se livre para usar, modificar e distribuir, desde que o devido crédito seja dado aos criadores originais.
