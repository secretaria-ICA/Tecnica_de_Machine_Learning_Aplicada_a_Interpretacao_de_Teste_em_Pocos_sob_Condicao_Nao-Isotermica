# Técnica de Machine Learning Aplicada a Interpretação de Teste em Poços sob Condição Não-Isotérmica

#### Aluno: [Maurício da Silva Cunha Galvão](https://github.com/mgalvao6).
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

Em reservatórios de alta transmissibilidade, registros da pressão obtidos em sensores distantes dos canhoneados podem estar distorcidos por efeitos térmicos. Esses efeitos abrangem uma diversidade de fenômenos, como a expansão/contração e flambagem da coluna, além da variação da massa específica do fluido dentro do poço. Essas distorções nos dados podem levar à identificação de falsas heterogeneidades geológicas na interpretação, por isso é importante levá-las em consideração na análise de um teste de formação.

Este trabalho se propõe a corrigir dados de pressão impactados termicamente, utilizando uma técnica de Machine Learning conhecida como Support Vector Regression (SVR). Uma das razões para o sucesso dessa e de outras técnicas como o Support Vectors Machine (SVM) é o uso do processo de kernalização, que permite trabalhar em um espaço de maior dimensão sem que a função de mapeamento seja efetivamente conhecida. Isto, por sua vez, permite que o modelo em desenvolvimento seja treinado com um grau maior de liberdade ainda que os cálculos computacionais sejam realizados em uma dimensão menor. Em particular, a utilização deste tipo de técnica reduz a necessidade de modelagem do problema físico. Outra vantagem é que esse método é capaz de lidar com efeitos de superposição tanto nos dados de pressão, quanto nos dados de temperatura.

Um estudo de caso sintético foi elaborado utilizando o simulador térmico comercial STARS (CMG). No estudo, são simulados os dados de pressão e temperatura em diferentes profundidades ao longo do poço. A técnica foi capaz de recuperar o sinal do reservatório em todas as profundidades, eliminando as distorções na pressão.

Técnicas de Transformação Digital (TD) apresentam um grande potencial na intepretação de testes, integrando dados antes usados de forma qualitativa. Este trabalho apresenta com sucesso a aplicação de uma destas técnicas para o caso de reservatórios de alta transmissibilidade, como os encontrados no pré-sal da bacia de Santos.

Uma etapa subsequente ao trabalho desenvolvido deve avaliar o desempenho do código elaborado em condições de fluxo multifásico (água, gás e óleo), e na presença de heterogeneidades no reservatório. As heterogeneidades podem compreender a presença de barreiras ao fluxo, regiões de aumento de permeabilidade, atuação de aquífero, dentre outras.

---

Matrícula: 192.190.061

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
