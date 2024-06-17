# BigData03-pyspark-analise

#Equipe:
- Pablo Rocha
- Luiz Filipe
- Maria Clara
- João Victor
- João pedro
- Wanessa Nicolly

# Análise de Incêndios Florestais nos EUA (1992-2020)

Este projeto realiza uma análise exploratória de um conjunto de dados extenso de incêndios florestais nos Estados Unidos, abrangendo o período de 1992 a 2020. Os dados incluem informações detalhadas sobre a localização, data de início, causa, tamanho e outras variáveis relevantes dos incêndios.

## Objetivo

O objetivo principal deste projeto é explorar e extrair insights dos dados de incêndios florestais nos EUA, identificando padrões temporais, espaciais e causas predominantes. Essas análises são fundamentais para entender melhor as dinâmicas dos incêndios florestais e podem ser úteis para pesquisadores, gestores de recursos naturais e formuladores de políticas públicas.

## Estrutura do Projeto

- **Notebook Principal:** `AT03-pyspark`
  - Notebook principal que contém todo o código necessário para análise e visualização dos dados.
  - Inclui carregamento dos dados, pré-processamento, análise exploratória, visualizações e conclusões.
  
- **Dados:**
  - Os dados utilizados estão disponíveis no arquivo `file2.csv`. Este arquivo contém todas as informações necessárias para realizar a análise.
  - **Instruções para Baixar os Dados:**
    - Os dados estão hospedados no Google Drive e podem ser baixados automaticamente através de um script Python incluído no notebook principal.

## Configuração e Execução

Para executar este projeto, siga as instruções abaixo:

1. **Abra o Notebook no Google Colab:**
   - Você pode acessar o notebook `AT03-pyspark` diretamente no Google Colab. Certifique-se de estar conectado à sua conta do Google.

2. **Carregue os Dados:**
   - Execute a célula de código que contém o script para baixar e carregar os dados do Google Drive. Certifique-se de que o arquivo `file2.csv` seja carregado corretamente.

3. **Execute o Notebook:**
   - Execute todas as células do notebook sequencialmente para carregar os dados, realizar a análise exploratória, gerar visualizações e obter insights dos dados de incêndios florestais.

4. **Visualizações e Conclusões:**
   - Ao final do notebook, você encontrará visualizações geradas e conclusões extraídas da análise dos dados. Documente quaisquer insights ou padrões identificados durante o processo.

## Dependências

- O notebook utiliza Python 3 e inclui as seguintes bibliotecas principais:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `google.colab` (para interação com o Google Drive no ambiente Colab)

Certifique-se de que todas as bibliotecas estejam instaladas no ambiente do Google Colab antes de executar o notebook.

## Contribuições

Contribuições são bem-vindas! Se você encontrar problemas ou melhorias possíveis, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT).

