# TCC Breno Abreu e Thomaz Pereira

Este é um repositório para os códigos utilizados para implementação dos métodos apresentados no Trabalho de Conclusão de Curso (TCC) de Breno Abreu e Thomaz Pereira intitulado "Detecção de Fraudes em Licitações Públicas Através da Identificação de Anomalias nos Valores Cobrados e da Análise de Redes Complexas Formadas por Interações de Compra".

### Dados Gerais

- **Título:** Detecção de Fraudes em Licitações Públicas Através da Identificação de Anomalias nos Valores Cobrados e da Análise de Redes Complexas Formadas por Interações de Compra
- **Universidade:** Universidade Tecnológica Federal do Paraná (UTFPR)
- **Campus:** Curitiba
- **Curso:** Bacharelado em Sistemas de Informação
- **Autores:** Breno Moura de Abreu; Thomaz Hugo Suzuki Pereira
- **Orientação:** Prof. Dr. Luiz Celso Gomes Jr.
- **Banca Avaliadora:** Prof. Dr. Luiz Celso Gomes Jr.; Prof. Dr. João Alberto Fabro; Profa. Dra. Leyza Baldo Dorini
- **Data da Defesa:** 05 de Dezembro de 2023
- **Contato:** breno2601@gmail.com; thomaz.szk@gmail.com

### Resumo

A detecção de anomalias em conjuntos de dados é de grande relevância em diversos cenários atuais, principalmente na área contábil onde anomalias podem ser consideradas indícios de fraude. Este tipo de análise pode ser usado para mitigar riscos e evitar perdas financeiras, sobretudo em órgãos públicos. Este trabalho tem como objetivo a detecção de anomalias em dados de notas fiscais de compras do setor público brasileiro de forma autônoma, para ajudar e acelerar o trabalho de auditores na área. Foram exploradas duas frentes distintas: (i) a detecção em dados estruturados utilizando o Local Outlier Factor (LOF), Isolation Forest (iForest) e Self-Organizing Maps (SOM); e (ii) a detecção em redes complexas utilizando Generative Adversarial Attributed Network Anomaly Detection (GAAN) e Contrastive self-supervised Learning framework for Anomaly detection on attributed networks (CoLA). Os resultados com o maior grau de anomalia foram analisados manualmente pelos próprios desenvolvedores e ao compará-los com registros similares foram categorizados de acordo com sua probabilidade de serem instâncias fraudulentas. No caso da detecção em dados estruturados (i), o iForest demonstrou ser o método mais promissor para a detecção de fraudes enquanto que o LOF apresentou resultados insatisfatórios; o SOM se mostrou mais eficaz na detecção de *outliers* isolados, tornando impossível identificar casos de fraudes. No caso da detecção de anomalias em redes complexas (ii), o modelo CoLA demonstrou um resultado mais favorável na identificação de nós irregulares, onde foi possível observar diferenças entre o nó apontado pelo modelo e nós semelhantes, sendo isso uma indicação que o nó é realmente uma instância anômala. Já o modelo GAAN identificou como nós anômalos instâncias bastante isoladas, ou seja, nós com poucas relações ligadas a ele (arestas) e poucos nós semelhantes, dificultando bastante a análise do resultado, não sendo possível identificar se de fato é uma instância possivelmente anômala ou uma instância normal.

### Abstract

Anomaly detection in datasets is of great relevance to multiple current scenarios, particularly in the accounting field where anomalies can be considered signs of fraud. This type of analysis can be used to mitigate risks and avoid financial losses, especially in the public sector. The goal of this project is to use anomaly detection methods in invoice data from the Brazilian public sector autonomously, in order to help and speed up the work of financial auditors. Two distinct fronts were explored: (i) anomaly detection in structured data using Local Outlier Factor (LOF), Isolation Forest (iForest) and Self-Organizing Maps (SOM); and (ii) anomaly detection in complex networks using Generative Adversarial Attributed Network Anomaly Detection (GAAN) and Contrastive self-supervised Learning framework for Anomaly detection on attributed networks (CoLA). The results with higher anomaly scores were analyzed manually by the developers and, after comparing them with similar entries, were categorized according to their probability of being fraudulent instances. For the detection in structured data (i), the iForest proved to be the most promising method for detecting frauds, while the LOF showed unsatisfactory results; the SOM method proved to be more effective in detecting isolated outliers, making it impossible to identify fraud cases. For the detection in complex networks (ii), the CoLA model showed better results in the identification of irregular nodes where it was possible to observe differences between a node pointed by the model and other similar nodes, indicating that the node is, in fact, an anomaly instance. The GAAN model identified greatly isolated anomaly nodes, in other words nodes with few connections and few similar nodes, making it difficult to analyze the results and to identify if the instance is an anomaly or not. 

### OBERVAÇÕES
A base de dados original não foi incluída neste repositório, apenas a base limpa que foi utilizada para o treinamento dos modelos. Se necessário, por favor contactar os desenvolvedores.

### Licensa
MIT
