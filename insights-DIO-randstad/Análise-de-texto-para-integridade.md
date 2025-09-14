 ## 📊 **Análise de Texto para Integridade**
 
 
 A Análise de Texto para saúde usa o aprendizado de máquina para identificar e rotular informações médicas em texto não estruturado, como anotações médicas, documentos clínicos e registros eletrônicos de saúde. Ele extrai dados importantes de fontes como resumos de alta para dar suporte à análise de cuidados de saúde.

🧠 A Análise de Texto para saúde executa quatro funções principais, todas com uma única chamada à API:

- Reconhecimento de entidade nomeada: O reconhecimento de entidade nomeada é usado para executar uma extração semântica de palavras e frases mencionadas no texto não estruturado associado a qualquer um dos tipos de entidade compatíveis, como diagnóstico, nome da medicação, sintoma/sinal ou idade.
- Extração de relação: A extração da relação é usada para identificar conexões significativas entre conceitos mencionados no texto associados a qualquer uma das relações com suporte, como a relação "hora da condição", que conecta um nome da condição a uma hora.
- Ligação de Entidades: A vinculação de entidade é usada para desambiguar as entidades extraídas associando-as a nomes e códigos preferenciais dos vocabulários biomédicos compatíveis com o Metadicionário de UMLS (Sistema Unificado de Linguagem Médica).
- Detecção de asserção: A detecção de declaração é usada para preservar o significado do conteúdo médico adicionando modificadores contextuais às entidades extraídas usando estas categorias:
  
      1. Certeza
      2. Condicionalidade
      3. Associação
      4. Temporalidade

Para usar a Análise de Texto para saúde, envie um texto não estruturado bruto para análise e identifique a saída da API no aplicativo. A análise é realizada no estado em que se encontra, sem nenhuma personalização adicional para o modelo usado em seus dados. Há duas maneiras de usar a Análise de Texto para a saúde:


|Ferramenta|Referência|
|----------|----------|
|Fábrica de IA dp Azure|[![doc](https://img.shields.io/badge/Acesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://ai.azure.com/?cid=learnDocs)|    |
|API REST ou biblioteca de clientes (SDK do Azure)|[![doc](https://img.shields.io/badge/Acesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://ai.azure.com/?cid=learnDocs)|
|Contêiner do Docker|[![doc](https://img.shields.io/badge/Acesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/sentiment-opinion-mining/how-to/use-containers)|     
