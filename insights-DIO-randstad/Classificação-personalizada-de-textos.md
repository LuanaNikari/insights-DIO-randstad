## 📉 **Classificação personalizada de texto**


A classificação personalizada de textos possibilita que usuários desenvolvam modelos de IA sob medida, capazes de categorizar documentos em classes específicas definidas previamente. Ao configurar um projeto desse tipo, os desenvolvedores podem rotular dados de forma iterativa, realizar o treinamento e a avaliação do modelo, além de promover ajustes para aprimorar seu desempenho antes de disponibilizá-lo para uso.

É importante destacar que a qualidade do conjunto de dados rotulados tem impacto direto na precisão e eficácia do modelo resultante. Para tornar o processo de criação e personalização mais acessível, o serviço disponibiliza um portal web interativo, acessível por meio do Language Studio.

Para iniciar rapidamente, basta seguir as instruções apresentadas no guia de início rápido.

🧠 A classificação de textos personalizada dá suporte a dois tipos de projetos:

- Classificação de rótulo único: é possível atribuir uma classe a cada documento no conjunto de dados. Por exemplo, um roteiro de filme só pode ser classificado como "Romance" ou "Comedy".
- Classificação de diversos rótulos: é possível atribuir diversas classes a cada documento no conjunto de dados. Por exemplo, um roteiro de filme pode ser classificado como "Comédia" ou "Romance" e "Comédia".

## 🧠***Ciclo de vida de desenvolvimento do projeto***


Siga estas etapas para aproveitar seu modelo ao máximo:

1. Defina o seu esquema: conheça seus dados e identifique as classes dentre as quais você deseja diferenciar para evitar ambiguidade.

2. Rotular os seus dados: a qualidade da rotulagem de dados é fundamental para determinar o desempenho do modelo. Os documentos que pertencem à mesma classe devem ter sempre a mesma classe. Se você tiver um documento que pode se enquadrar em duas classes diferentes, use projetos de classificação de diversos rótulos. Evite a ambiguidade de classes verificando se elas são claramente distintas entre si, especialmente em projetos de classificação de rótulo único.

3. Treinar o modelo: o modelo começa a aprender com os dados rotulados.

4. Exibir detalhes de desempenho do modelo: veja os detalhes de avaliação do modelo para determinar o desempenho dele diante de novos dados.

5. Implantar o modelo: a implantação de um modelo o disponibiliza para uso por meio da API de análise.

6. Classificar textos: use o modelo personalizado para tarefas de classificação de textos personalizada.
