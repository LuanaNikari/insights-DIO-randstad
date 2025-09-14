## **Vinculação de Entidades**


A vinculação de entidades conecta essas entidades identificadas a uma base de conhecimento estruturada, ou seja, não apenas reconhece, mas também desambigua e liga a um conceito único.


Como funciona o processo?

1. Identificação da entidade

   NER ou outra técnica detecta possíveis entidades no texto.

2. Geração de candidatos

   Busca em uma base de conhecimento (ex.: Wikipédia, DBpedia, Wikidata, Knowledge Graph do Google) por possíveis correspondentes.

3. Desambiguação

   Resolve ambiguidades. Exemplo:

   “Amazon” pode ser:

   [Amazon (empresa de e-commerce)]

   [Amazon (rio na América do Sul)]

   O algoritmo usa o contexto da frase para decidir.

4. Vinculação final

   Associa a entidade à entrada correta no repositório de conhecimento.


Para usar a vinculação de entidade, envie um texto não estruturado bruto para análise e identifique a saída da API em seu aplicativo. A análise é realizada no estado em que se encontra, sem nenhuma personalização adicional para o modelo usado em seus dados. Há duas maneiras de usar a vinculação de entidade:

|Ferramentas|Referências|
|-----------|-----------|
|Language Studio| [![doc](https://img.shields.io/badge/Acesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://language.cognitive.azure.com/tryout/linkedEntities)|    |
|API REST ou biblioteca de clientes (SDK do Azure)|[![doc](https://img.shields.io/badge/Acesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://ai.azure.com/?cid=learnDocs)|

