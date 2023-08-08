![image](https://github.com/gabrielalonde/Antimicrobial-Peptide-Dataset-/assets/138613530/6b2696b1-eeab-41dd-9c7f-329ba3331998)

#Projeto PIBIC Extração das características físico-químicas de peptídeos antimicrobianos

O objetivo do presente trabalho consiste em apresentar duas bases de peptídios, uma de peptídeos antimicrobianos e outro de  peptídeos não antimicrobianos que 
contenha a sequência peptídica, a atividade e características físico-químicas para posterior treinamento de uma rede neural profunda baseada em grafos.

Este repositório contém os arquivos AMP.csv e o noAMP.csv com as sequências de peptídeos. Cada linha do arquivo contém o ID, a sequência, atividade, tamanho, banco de dados e as features calculadas utilizando bibliotecas de código de bioinformática. As features foram calculadas utilizando o código que está no arquivo Descriptor.ipynb

Foi realizada e extração das sequências peptídicas em bancos de dados publicos e divisão em dois grupos de acordo com a atividade biológica. O grupo positivo contém peptídeos com atividade antimicrobiana relatada na literatura e o grupo negativo contém as sequências que não possuem atividade antimicrobiana. Uma filtragem de dados foi realizada excluindo as sequências que possuem aminoácidos não naturais e tambem foi excluido os peptideos maiores que 50 AA. Foram utilizadas o software CD-hit para agrupamento e filtragem dos peptideos com similaridade 0.95, além de bibliotecas como modlamp e biophton para análise da distribuição dos tamanhos das sequências e distribuição dos aminoácidos no dois grupos.

![image](https://github.com/gabrielalonde/ProjetoPIBIC/assets/138613530/79e4fd4f-2a78-45a0-a06a-14387bfcc598)

![image](https://github.com/gabrielalonde/Antimicrobial-Peptide-Dataset-/assets/138613530/5c57198e-0e10-4047-b367-e3b6f91772f8)

![image](https://github.com/gabrielalonde/Antimicrobial-Peptide-Dataset-/assets/138613530/c5323853-f6de-4d1d-bc51-ca71ed3683ad)







 
