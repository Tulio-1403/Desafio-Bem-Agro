# Desafio Bem Agro

Este trabalho visa a segmentação de imagens RGB para identificar regiões com vegetação. No repositório Git, você encontrará os códigos para treinamento e predição do modelo, utilizando a arquitetura U-Net, uma rede neural convolucional eficaz para tarefas de segmentação de imagens. Os dados utilizados para o treinamento estão disponíveis no arquivo zip.

Os principais componentes deste desafio incluem:

1.  Pré-processamento de Dados: Dividindo as imagens em blocos e binarizando-os com base no índice de verde excessivo (ExG) para distinguir vegetação.

2.  Treinamento do Modelo: Utilizando a arquitetura U-Net para treinar o modelo com as imagens pré-processadas.

3.  Predição e Validação: Aplicando o modelo treinado em novas imagens para identificar e segmentar áreas com vegetação, comparando visualmente os resultados.

Este repositório fornece uma solução para segmentação de vegetação em imagens RGB.

