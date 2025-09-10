# Laboratório - Azure Machine Learning (Modelo de Previsão)

Este projeto faz parte do desafio de criar um **laboratório de Machine Learning no Azure**, configurando um modelo de previsão e expondo-o através de um endpoint.

---

## 🚀 Passo a Passo

### 1. Criação do Repositório
- Acesse o [GitHub](https://github.com).
- Clique em **New Repository**.
- Escolha um nome (exemplo: `azure-ml-lab`) e crie o repositório vazio.

---

### 2. Acesso ao Azure Machine Learning
- Entre no portal do [Azure](https://portal.azure.com/).
- No menu de serviços, pesquise por **Azure Machine Learning**.
- Crie um novo **workspace** preenchendo:
  - Nome do workspace
  - Grupo de recursos
  - Região

---

### 3. Criação do Laboratório
- Dentro do workspace, acesse o **Azure Machine Learning Studio**.
- No menu lateral, clique em **Automated ML** (Aprendizado de Máquina Automatizado).
- Crie um novo **experimento**:
  - Nome do experimento
  - Dataset (exemplo: dados de preços de casas, vendas ou outro dataset público)
  - Tipo de tarefa: **Regressão** (previsão de valores) ou **Classificação** (previsão de categorias).
- Configure os parâmetros básicos (métricas, limitação de tempo de execução, etc.).
- Inicie o treinamento do modelo.
