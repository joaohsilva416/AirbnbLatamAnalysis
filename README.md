# Análise do Airbnb - América Latina

## 📌 Visão Geral
O objetivo principal deste projeto é analisar a quantidade de diárias reservadas por turistas estrangeiros nos 4 principais países da América Latina (Brasil, Argentina, México e Colômbia).

## 💼 Entendimento do Negócio
Durante a análise montamos um funil de conversão de visitantes para reservar uma hospedagem nos países, essa análise nos mostrou uma dificuldade que os países tem de converter clientes em uma
das etapas, que seria durante a pesquisa dos detalhes do imóveis e o check-out dos clientes.

**Tipo de análise realizado**
- Análise Exploratória dos Dados

## 🛠 Pré-processamento
_Consideração Importante:_
- Os dados serão mantidos anônimos por boa prática e respeito a proteção dos mesmos.

_Etapas do Pré-Processamento de Dados:_
1. Importação das libs
2. Carregamento e leitura do excel
3. Análise descritiva

## 📈 Insights e Conclusões

### 1. Estratégia de Preços
- Brasil apresenta maior dispersão de preços, considerar estratégias de segmentação mais claras
- Colômbia oferece o melhor custo-benefício, potencial para atrair mais turistas estrangeiros

### 2. Funil
- Focar na etapa "Detalhes do imóvel -> Check-out" (problema comum em todos os países)
- Investigar causas da alta taxa de abandono nesta etapa:
  - Informações incompletas/confusas
  - Processo de check-out complexo

## 📜 Estrutura do Projeto
A estrutura de diretórios do projeto foi organizada da seguinte forma:
```
├── notebooks
├── src
│ ├── __init__.py
├── .gitignore  
├── .python-version  
├── README.md  
├── poetry.lock  
├── pyproject.toml
```
