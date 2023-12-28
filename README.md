<img src=https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/cf1762d0-ce2e-4dc0-9b5d-dcc68ab37899 alt= “” width="900" height="300">

# Projeto acadêmico:

## Pipeline para Detecção de Intrusão em Redes IoT utilizando Aprendizado de Máquina: Um Estudo de Caso

Esse trabalho foi desenvolvido ao longo da Residência em Segurança da Informação pela Universidade Federal do Ceará e em parceria com o Instituto SiDi.

<h1> <img height="40" width="40" src= "https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/9a23acf4-a4cf-406a-811c-50cd14d78b1a" />  Contexto e Resumo do Projeto </h1>

O crescimento das redes IoT (Internet of Things) fez com que elas se tornassem alvo de ataques cibernéticos. Por isso, este projeto tem como objetivo propor um pipeline para analisar intrusão em traáego de redes IoT por meio de técnicas de Aprendizado de Máquina. Para validar o pipeline proposto, foi realizado um estudo de caso utilizando a base de dados IoT-23 e tres modelos de classificação:  ́Arvore de Decisão, Random Forest e CatBoost. Os resultados demonstraram a eficácia do modelo Random Forest, que obteve precisão de
98,8% e recall de 99,5%, e a contribuicão de atributos na classificacão por meio do SHAP.


<h1> <img height="40" width="40" src= "https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/2b1ecaa4-bc9f-4b6e-8618-b22665a755aa" /> Conteúdo do Projeto </h1>

O conteúdo disponibilizado no GitHub consiste no código utilizado para a construção e validação do pipeline proposto, além das referências utilizadas para o estudo e desenvolvimento do presente projeto. Os dados brutos não puderam ser disponibilizados pelo seu tamanho exceder ao limite da plataforma, porém, pode ser obtido através do site [Stratosphere](https://www.stratosphereips.org/datasets-iot23), no qual é disponibilizado em duas versões, uma sendo de 21 GB e outra de 8,8 GB. Para o projeto, foi utilizado a versão menor que é composta por dados rotulados.
 
- code: é a pasta com os códigos utilizados no projeto. Dentro da pasta, tem-se os seguintes arquivos:
  -  Dataset.ipynb: código utilizado para extrair e coletar dados das capturas disponibilzadas, gerando um único arquivo .csv para as próximas etapas.
  -  CatBoost.ipynb: consiste no pré-processamento e implementação do algoritmo CatBoost para a base gerada. Nela também é possível verificar as métricas, a Matriz de Confusão e a interpretabilidade do modelo através do SHAP.
  -  Random Forest.ipynb: consiste no pré-processamento e implementação do algoritmo Random Forest com as métricas obtidas, Matriz de Confusão e SHAP.
  -  Árvore de Decisão.ipynb: segue o mesmo padrão dos anteriores, porém a implementação é para o algoritmo Árvore de Decisão.

- references: é a pasta que contém as referências que foram utilizadas para o estudo e execução do projeto apresentado.

- requirements.txt: arquivo que contém os requisitos necessários para rodar os códigos do projeto.

<h1> <img height="40" width="40" src= "https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/6f64d29c-8e45-452e-9721-5e2907da6d4c" /> Bibliotecas </h1>

- Pandas
- Numpy
- Warnings
- Sklearn
- Seaborn
- Matplotlib
- SHAP
- CatBoost
- Imblearn (Imbalanced-learn)

<h1> <img height="40" width="40" src= "https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/f681bf09-f8dd-461c-9216-ab741851a6b3" /> Setup </h1>

Para executar o projeto, basta:
1. Baixar o repositório;
2. Criar um ambiente virtual;
3. Instalar as bibliotecas contidas no arquivo requirements.txt, através do seguinte comando: 
```
pip install -r requirements.txt
```

<h1> <img height="40" width="40" src= "https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/e47ad0e4-3537-4b9c-ba8e-431c370028bb" /> Equipe do Projeto </h1>
 
|  **Lucelia Lima**  |   **Nathália Martins**   |  **Lorena Medeiros**  |
| ---------------- | ---------------------- | ------------------- |
| <a href="https://www.linkedin.com/in/lucelialima" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>  | <a href="https://www.linkedin.com/in/nathaliamartinss" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> |


