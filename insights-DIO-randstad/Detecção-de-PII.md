## **Detecção de PII**


O serviço de detecção de PII (Personally Identifiable Information) é uma API em nuvem projetada para identificar, classificar e, quando necessário, mascarar informações de identificação pessoal presentes em dados textuais. Ele se baseia em modelos de aprendizado de máquina e técnicas avançadas de Processamento de Linguagem Natural (PLN), permitindo a construção de aplicações inteligentes com capacidade de análise semântica contextual. 

Na plataforma Azure AI Language, o mecanismo de detecção de PII utiliza o Reconhecimento de Entidade Nomeada (NER – Named Entity Recognition) como núcleo de sua operação. Essa técnica é responsável por localizar e rotular entidades específicas em um texto, distinguindo-as em categorias pré-definidas de sensibilidade. 

📜 Essas categorias abrangem, entre outras: 

1. Identificadores pessoais → números de documentos (CPF, RG, passaporte). 

2. Informações de contato → telefones, endereços de e-mail, endereços físicos. 

3. Dados financeiros → números de cartões de crédito, contas bancárias. 

4. Outras entidades sensíveis → como endereços IP ou credenciais. 


📜 A classificação automática possibilita que sistemas apliquem estratégias de redação (masking), anonimização ou bloqueio de dados conforme as exigências regulatórias (ex.: LGPD, GDPR, HIPAA). Além disso, por empregar modelos probabilísticos e contextuais, a solução vai além de simples padrões baseados em expressões regulares, sendo capaz de reduzir falsos positivos e identificar PII em cenários linguísticos mais complexos. 

Há duas maneiras de usar a detecção de PII: 

|Ferramenta|Referência|
|----------|----------|
|Fábrica de IA dp Azure|[![doc](https://img.shields.io/badge/Acesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://ai.azure.com/?cid=learnDocs)|    |
|API REST ou biblioteca de clientes (SDK do Azure)|[![doc](https://img.shields.io/badge/Acesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://ai.azure.com/?cid=learnDocs)|


Crie um projeto na Fábrica no Portal da Fábrica de IA do Azure: [![doc](https://img.shields.io/badge/Acesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://ai.azure.com/?cid=learnDocs)


## **O Playground da Fábrica:**


O playground de idiomas consiste em quatro seções: 

- Faixa superior: você pode selecionar qualquer um dos serviços de idiomas disponíveis no momento aqui. 

- Painel direito: esse painel é onde você encontra as opções de Configuração para o serviço como: API e a versão do modelo, juntamente com recursos específicos para o serviço. 

- Painel central: é onde você insere seu texto para processamento. Depois que a operação for executada, agluns resultados serão mostrados aqui. 

- Painel central: é onde você insere seu texto para processamento. Depois que a operação for executada, alguns resultados serão mostrados aqui. 

- Painel direito: é onde os Detalhes da operação de execução são mostrados.
  

**Como configurar:**


```mermaid
   graph TD;
   A[Selecionar a versão da API]--> B[Selecionar a versão do modelo];
   B--> C[Selecionar tipos a serem incluídos];
   C--> D[Especificar política de redação];
   D--> E[Selecionar qual caractere é usado para redação. Disponível apenas com a política de redação CharacterMask];
   E--> F[Após a conclusão da operação, o tipo de entidade é exibido abaixo de cada entidade no painel central e a seção Detalhes contém os seguintes campos para cada entidade: a entidade detectada, o tipo de entidade detectada, o número de caracteres que a entidade foi detectada desde o início da linha, o cumprimento de caracteres da entidade, o grau de confiança do modelo na correção da identificação do tipo de entidade.];
   ```


**Configuração:**

```mermaid
   graph TD;
   A[Selecionar qual versão da API usar]--> B[Selecionar qual versão do modelo usar];
   B--> C[Selecionar o idioma de entrada];
   C--> D[Selecionar os tipos de informações que vocês deseja redigir];
   D--> E[Selecionar o método de redação];
   E--> F[Selecionar qual caractere é usado para redação. Disponível apenas com a política de redação CharacterMask.];
```
