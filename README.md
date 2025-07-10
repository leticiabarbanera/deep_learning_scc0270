# redes_neurais_SCC0270

INTRODUÇÃO

Este repositório se refere a entrega final da disciplina. A atividade tinha como objetivo desenvolver e treinar uma rede neural capaz de classificar radiografias de tórax entre imagens não doentes e imagens de pacientes diagnosticados com COVID-19. O conjunto de dados utilizado está publicamente disponível em: https://github.com/ieee8023/covid-chestxray-dataset.  

Trata-se de um problema de classificação binária: com COVID-19 (label 0), 342 imagens; saudável (label 1): 193 imagens.
O dataset apresenta um leve desbalanceamento entre as classes (cerca de 65% - 35%), o que é importante destacar para os próximos passos.

Esse repositório está organizado da seguinte forma: cada arquivo tem, em seu nome, as redes que foram treinadas ali, na mesma ordem em que estão no código. Cada uma está organizada dentro de um tópico, ou índice, dentro do notebook, de maneira a facilitar sua localização. 
Os preâmbulos dos arquivos são os mesmos para os notebooks (importação dos dados + funções gerais, como treino e validação). 
Os arquivos podem ser consultados em qualquer ordem, mas sugerimos seguir a ordem cronológica com que trabalhamos, descrita a seguir. Para facilitar essa consulta em particular, descrevemos no final desse README.md a sequência de arquivos a serem consultados e quais redes devem ser consultadas em cada, Buscamos organizar da melhor forma para facilitar a compreensão.

 SEQUÊNCIA CRONOLÓGICA DOS ARQUIVOS
 ENTREGA I - FOCO EM IMAGENS
 1) consultar cnnsimples em cnnsimples_resnet18_resnet34_shufflenet_efficientnet.ipynb
 2) consultar familiadensenet_familiaresnet.ipynb (arquivo todo)
 3) consultar transferlearning_chexnet_torchxrayvision (arquivo todo)
 4) consultar resnet 18 e resnet 34 em cnnsimples_resnet18_resnet34_shufflenet_efficientnet.ipynb e resnet em customcnn_resnet_squeezenet_mobilenet.ipynb
 5) consultar shufflenet e efficientnet em cnnsimples_resnet18_resnet34_shufflenet_efficientnet.ipynb
 6) consultar shufflenet_googlenet.ipynb (arquivo todo)
 7) consultar squeezenet e mobilenet em customcnn_resnet_squeezenet_mobilenet.ipynb
 8) consultar mobilenet.ipynb (arquivo todo)

ENTREGA II - FOCO EM TEXTO
1) consultar processing_texts.ipynb

ENTREGA FINAL - REDE MULTIMODAL
1) multimodal.ipynb

*observação: os principais artigos consultados estão referenciados nos notebooks, com os respectivos links para acesso
