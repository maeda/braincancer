# Acompanhamento


## 01/10/2019: 

Fizemos o cadastro no site da Universidade da Pensilvânia (https://www.med.upenn.edu/sbia/brats2018/data.html)
para ter acesso ao dataset Multimodal Brain Tumor Segmentation (BraTS). Como a autorização é 
feita manualmente, estamos aguardando a confirmação por email.

O ponto interessante desse dataset é que o *ground truth* são imagens onde o tumor é
marcado na imagem, o que poderá ajudar durante o treinamento do modelo. Enquanto 
isso vamos criar a rede neural com os hiperparâmetros e topologia inicial [1].  


## 08/10/2019

Baixamos o dataset BRATS 2013 (https://www.smir.ch/BRATS/Start2013) e estamos tentando abrir as imagens para ver como o 
*ground truth* se parece. As imagens estão no formato mha (https://github.com/Kitware/MetaIO).

Estamos tentando visualizar as imagens e descobrir como fazer a marcação da região com câncer.

## Referências

[1]  PEREIRA, Sérgio et al. Brain tumor segmentation using convolutional neural networks in MRI images. IEEE transactions on medical imaging, v. 35, n. 5, p. 1240-1251, 2016.