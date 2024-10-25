# Projeto KNIME - Normalização de Tabelas de Filmes e Visualização Gráfica

Este projeto foi desenvolvido em KNIME com o objetivo de processar dados de uma base de dados de filmes, realizar a normalização das tabelas e apresentar os resultados através de gráficos para análise visual.

## Objetivo

O objetivo principal deste trabalho é normalizar uma base de dados de filmes, organizando as tabelas de forma eficiente para evitar redundâncias e garantir a consistência dos dados. Após a normalização, o projeto também gera gráficos que ilustram várias métricas e resultados obtidos a partir dos dados.

## Estrutura do Projeto

- **Base de Dados de Filmes**: A base de dados contém informações sobre filmes, como título, género, ano de lançamento, realizador, elenco, classificação, entre outros dados.
  
- **Normalização de Tabelas**: O processo de normalização é feito para otimizar a estrutura das tabelas, eliminando duplicações e criando relações adequadas entre elas. A normalização segue as regras da 1ª, 2ª e 3ª formas normais.

- **Visualização de Dados**: Após a normalização, foram gerados gráficos em KNIME para representar métricas relevantes, como:
  - Distribuição de géneros de filmes.
  - Avaliação média dos filmes ao longo dos anos.
  - Número de filmes por realizador.
  - Relação entre ano de lançamento e popularidade.

## Ferramentas Utilizadas

- **KNIME Analytics Platform**: A plataforma de ciência de dados foi utilizada para todo o fluxo de trabalho, desde a importação dos dados, passando pela normalização até a visualização gráfica.
- **Base de Dados**: Foi utilizada uma base de dados contendo milhares de filmes, com várias colunas e categorias de dados.

## Instruções para Executar o Projeto

1. **Instalar KNIME**: Se ainda não tens o KNIME, podes fazer o download [aqui](https://www.knime.com/downloads).
2. **Importar o Workflow**:
   - Abre o KNIME e importa o ficheiro do workflow associado a este projeto.
3. **Configurar a Base de Dados**:
   - Garante que a base de dados de filmes está disponível no mesmo diretório especificado no workflow ou ajusta o caminho conforme necessário.
4. **Executar o Workflow**:
   - Executa o workflow para normalizar as tabelas e gerar os gráficos.
5. **Visualizar os Resultados**:
   - A seguir à execução, poderás visualizar os gráficos na secção de output do KNIME, onde são apresentados os resultados obtidos com a normalização dos dados.

## Conclusão

Este projeto demonstra como o KNIME pode ser usado para normalizar dados e gerar visualizações gráficas de uma forma eficiente e escalável. O uso de uma base de dados de filmes como exemplo permite explorar dados reais e obter insights importantes.

