# lab-ai-900-3
laboratório sobre Azure AI Search

## Introdução
Este projeto demonstra como configurar e utilizar o Azure AI Search para indexação e consulta de dados. O Azure AI Search é uma solução que permite enriquecer dados com habilidades de IA e realizar buscas eficientes.

## Passo a Passo para Configurar uma Pesquisa

### 1. Criar um Serviço de Azure AI Search
1. Acesse o [portal do Azure](https://portal.azure.com).
2. Clique em "Criar um recurso" e procure por "Azure AI Search".
3. Preencha os detalhes necessários (nome, grupo de recursos, localização) e clique em "Criar".
4. O ideal nesta etapa de criação usar a localização e planos com custos mais em conta para não usar todos os créditos free, neste exercício.

### 2. Criar uma Storage Account e depois um container para carregar os documentos disponibilizados pela Microsoft para realização do laboratório: https://aka.ms/mslearn-coffee-reviews

### 3. Provisionar um recurso de serviços de IA do Azure que esteja no mesmo local que o recurso de Pesquisa de IA do Azure utlizando o mesmo grupo de recursos   

### 4. Criar um Índice
1. No portal do Azure, navegue até o seu serviço de Azure AI Search.
2. Clique em "Índices" e depois em "Adicionar índice".
3. Defina o esquema do índice (campos, tipos de dados, etc.) e clique em "OK".

### 5. Carregar Dados
1. Crie um indexador para importar dados de uma fonte (Azure Blob Storage).
2. Configure o indexador com a fonte de dados e mapeie os campos para o índice.
3. Execute o indexador para carregar os dados no índice.

### 6. Explorar o Índice
1. Use o **Search Explorer** no portal do Azure para testar consultas.
2. Escreva consultas em JSON para buscar dados no índice.

### Exemplos de Consultas
- **Consulta básica**:
  ```json
  {
    "search": "*",
    "count": true
  }
### Benefícios 
Aplicações de E-commerce melhorando a experiência de busca de produtos.
Sistemas de Gestão de documentos facilitando a busca e recuperação dos mesmos.

### Aprendizados 
Configuração de Serviços no Azure.
Criação de Índices.
Enriquecimento de dados.
