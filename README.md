# Online Shoppers - Desvendando a Intenção de Compra Online: Minha Jornada com Random Forest, SVM, XGBoost e MLP

Na era em constante expansão das compras online, compreender a intenção dos usuários tornou-se mais do que uma vantagem competitiva; é uma necessidade premente para otimizar a experiência do cliente e impulsionar as conversões. Neste estudo, empreendi uma análise aprofundada, aplicando técnicas de machine learning para prever se um visitante do site possui a intenção de realizar uma compra.

Explorando os Dados
O início deste projeto envolveu o carregamento de dados de um arquivo CSV coletado de um repositório da UCI. Uma análise superficial revelou as primeiras linhas do DataFrame, proporcionando-me uma visão crucial da estrutura dos dados que estaria explorando.

Preparação dos Dados
Na etapa de pré-processamento codifiquei variáveis categóricas, normalizei dados e dividi o conjunto em treino e teste. Apliquei o Label Encoder nas colunas categóricas (Month e VisitorType), transformando as variáveis nominais em numéricas. Normalização dos dados com o StandardScaler preparou o terreno para o treinamento dos modelos.

Quatro modelos foram escolhidos:  Random Forest, SVM, XGBoost e MLP. Cada um passou por um treinamento nos dados de treino, visando aprimoramento, antes de ser avaliado nos dados de teste.

Avaliação de Desempenho
As métricas de desempenho foram cruciais para a escolha do melhor modelo. A acurácia, a matriz de confusão e o relatório de classificação foram calculados minuciosamente para cada modelo. 

Resultados e Revelações
Random Forest: Alcançou uma acurácia respeitável de 88.51%, com precisão e recall notáveis para ambas as classes. A matriz de confusão destacou sua capacidade de distinguir entre compras finalizadas e não finalizadas.

SVM: Apresentou uma acurácia de 87.43%, merecendo destaque pela alta taxa de verdadeiros positivos, indicando uma habilidade distinta na identificação de compras finalizadas.

XGBoost: O modelo de maior destaque, com uma acurácia soberba de 89.27%. Revelou-se robusto, mantendo um equilíbrio entre precisão e recall.

MLP (Redes Neurais): Alcançou uma acurácia de 88.54%, destacando-se na identificação correta de não compras finalizadas.

Ao comparar as acurácias e outras métricas, o XGBoost foi o modelo mais adequado, com sua capacidade de decifrar relações complexas nos dados, resultando em uma maior precisão na previsão da intenção de compra.

Insights e Reflexões Finais

Importância das Páginas Visitadas: Páginas específicas, especialmente as relacionadas a produtos, exercem um impacto significativo na decisão de compra.

Tempo Gasto nas Páginas: A duração das interações nas páginas administrativas e informativas influenciam na intenção de compra.

Mês e Visitantes: Padrões sazonais foram desvendados, com alguns meses exibindo uma propensão maior à compra. Além disso, os visitantes retornantes mostraram-se mais propensos a finalizar uma compra.

Conclusão
Este estudo lança luz sobre a eficácia dos modelos de machine learning na previsão da intenção de compra em sites de compras online. O XGBoost sobressaiu-se como o modelo mais eficiente, proporcionando insights essenciais para estratégias de marketing direcionadas e aprimoramento da experiência do usuário. Essas descobertas não são apenas números; são peças valiosas do quebra-cabeça para o crescimento e sucesso de sites de compras online.

Referências: Pedregosa et al., "Scikit-learn: Machine Learning in Python," Journal of Machine Learning Research (2011).







