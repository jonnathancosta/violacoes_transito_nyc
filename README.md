# Análise de Violações de Trânsito em Nova York

Este projeto (desenvolvido em meados de 2024) realiza uma análise detalhada das violações de trânsito registradas em Nova York, utilizando um conjunto de dados público. O objetivo é explorar padrões, tendências e insights úteis relacionados às infrações de estacionamento.

## Estrutura do Projeto

- **`violacoes_transito.ipynb`**: Notebook principal contendo o código e as análises realizadas.
- **`Parking_Violations_Issued.csv`**: Conjunto de dados com informações detalhadas sobre as violações de trânsito.

## Análises Realizadas

1. **Transformação de Dados**:
   - Conversão de datas no formato string para o formato datetime.
   - Filtragem de dados para incluir apenas registros até o ano de 2024.

2. **Análise Temporal**:
   - Contagem de violações por ano.
   - Visualização das infrações ao longo dos anos.

3. **Análise por Estado**:
   - Identificação dos estados com maior número de infrações.
   - Visualização das infrações por estado.

4. **Análise por Tipo de Veículo**:
   - Identificação dos tipos de veículos mais frequentemente envolvidos em infrações.
   - Cálculo da proporção de cada tipo em relação ao total de violações.

5. **Códigos de Violação Mais Frequentes**:
   - Identificação dos códigos de violação mais recorrentes.
   - Visualização das infrações mais comuns.

6. **Distribuição ao Longo do Dia**:
   - Análise dos horários de pico para infrações durante a manhã, tarde e noite.
   - Comparação entre os períodos do dia.

## Tecnologias Utilizadas

- **Python**: Linguagem principal para análise de dados.
- **Bibliotecas**:
  - `pandas`: Manipulação e análise de dados.
  - `numpy`: Operações matemáticas e manipulação de arrays.
  - `seaborn` e `matplotlib`: Visualização de dados.

## Como Executar

1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale as dependências necessárias:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Abra o arquivo `violacoes_transito.ipynb` em um ambiente Jupyter Notebook ou similar.
4. Execute as células sequencialmente para reproduzir as análises.

## Conjunto de Dados

O conjunto de dados utilizado neste projeto é público e contém informações detalhadas sobre violações de trânsito em Nova York, incluindo:
- Data da infração.
- Estado de registro do veículo.
- Tipo de veículo.
- Código da violação.
- Horário da infração.

## Visualizações

O projeto inclui diversas visualizações para facilitar a interpretação dos dados, como:
- Gráficos de linha para análise temporal.
- Gráficos de barras para comparações entre estados, tipos de veículos e períodos do dia.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias no projeto.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais informações.
