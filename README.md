# ProjetoPIBIC

Projeto PIBIC Extração das características físico-químicas de peptídeos com base na sequência de aminoácidos

O objetivo do presente trabalho consiste em apresentar duas bases de peptídios, uma de peptídeos antimicrobianos e outro de  peptídeos não antimicrobianos que 
contenha a sequência peptídica, a atividade e características físico-químicas para posterior treinamento de uma rede neural profunda baseada em grafos.

Este repositório contém os arquivos AMP.csv e o noAMP.csv com as sequências de peptídeos. Cada linha do arquivo contém o ID, a sequência, atividade, tamanho, banco de dados e as features calculadas utilizando bibliotecas de código de bioninformática. As features foram calculadas utilizando o código que está no arquivo Descriptor.ipynb

Foi realizada e extração das sequencias peptídicas em bancos de dados publicos e divisão em dois grupos de acordo com a atividade biológica. O grupo positivo contém peptídeos com atividade antimicrobiana relatada na literatura e o grupo negativo contém as sequencias que não possuem atividade antimicrobiana. Uma filtrgem de dados foi realizada excluindo as sequencias que possuem aminoácidos não naturais e tambem foi excluido os peptideos maiores que 50 AA. Foram utilizadas o software CD-hit para agrupamento de sequências e filtragem dos peptideos com similaridade 0.95, além de bibliotecas como modlamp e biophton para análise da distribuição dos tamanhos das sequências e distribuição dos aminoácidos no dois grupos.

![image](https://github.com/gabrielalonde/ProjetoPIBIC/assets/138613530/df3eb055-4f2b-4825-8122-04984813714e)
![image](https://github.com/gabrielalonde/ProjetoPIBIC/assets/138613530/f0029f62-cbec-412c-bc3a-6b7a363bcf7c)




 
