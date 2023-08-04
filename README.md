<img src=https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/adc8c4c3-de56-488d-9b81-5f8d12925a7b alt= “” width="900" height="300">

# Projeto acadêmico:

## Pipeline para Detecção de Intrusão em Redes IoT utilizando Aprendizado de Máquina: Um Estudo de Caso

Esse trabalho foi desenvolvido ao longo da Residência em Segurança da Informação pela Universidade Federal do Ceará e em parceria com o Instituto SiDi.

<h1> <img height="40" width="40" src= "https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/bec6f402-38d5-4bcd-872a-b3193e504839" />  Contexto e Resumo do Projeto </h1>

O crescimento das redes IoT (Internet of Things) fez com que elas se tornassem alvo de ataques cibernéticos. Por isso, este projeto tem como objetivo propor um pipeline para analisar intrusão em traáego de redes IoT por meio de técnicas de Aprendizado de Máquina. Para validar o pipeline proposto, foi realizado um estudo de caso utilizando a base de dados IoT-23 e tres modelos de classificação:  ́Arvore de Decisão, Random Forest e CatBoost. Os resultados demonstraram a eficácia do modelo Random Forest, que obteve precisão de
98,8% e recall de 99,5%, e a contribuicão de atributos na classificacão por meio do SHAP.


<h1> <img height="40" width="40" src= "https://github.com/Projeto-UFC-SiDi/projeto-ufc-sidi/assets/89808695/389789b1-b3a7-4094-b7cf-f2525e50c47c" /> Conteúdo do Projeto </h1>

O conteúdo disponibilizado no GitHub consiste no código utilizado para a construção e validação do pipeline proposto, além das referências utilizadas para o estudo e desenvolvimento do presente projeto. Os dados brutos não puderam ser disponibilizados pelo seu tamanho exceder ao limite da plataforma, porém, pode ser obtido através do site [Stratosphere](https://www.stratosphereips.org/datasets-iot23), no qual é disponibilizado em duas versões, uma sendo de 21 GB e outra de 8,8 GB. Para o projeto, foi utilizado a versão menor que é composta por dados rotulados.
 
- code: é a pasta com os códigos utilizados no projeto. Dentro da pasta, tem-se os seguintes arquivos:
  -  Dataset.ipynb: código utilizado para extrair e coletar dados das capturas disponibilzadas, gerando um único arquivo .csv para as próximas etapas.
  -  CatBoost.ipynb: consiste no pré-processamento e implementação do algoritmo CatBoost para a base gerada. Nela também é possível verificar as métricas, a Matriz de Confusão e a interpretabilidade do modelo através do SHAP.
  -  Random Forest.ipynb: consiste no pré-processamento e implementação do algoritmo Random Forest com as métricas obtidas, Matriz de Confusão e SHAP.
  -  Árvore de Decisão.ipynb: segue o mesmo padrão dos anteriores, porém a implementação é para o algoritmo Árvore de Decisão.

- references: é a pasta que contém as referências que foram utilizadas para o estudo e execução do projeto apresentado.






