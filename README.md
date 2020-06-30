[![GitHub contributors](https://img.shields.io/github/contributors/AlexeiAS/AulasVC?color=green)](https://github.com/AlexeiAS/AulasVC/graphs/contributors)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Django?color=green)
[![GitHub forks](https://img.shields.io/github/forks/AlexeiAS/AulasVC?logoColor=green&style=social)](https://github.com/AlexeiAS/AulasVC/network/members)


## Resolução de exercícios de Visão Computacional .
### ->> by Alexei Alves de Souza

* Aula8 ->Processamento morfológico: operações em conjuntos e operações morfológicas básicas
* Aula9->Processamento morfológico: algoritmos morfológicos
* Aula10->Processamento morfológico em escala de cinza
* Aula11->Segmentação: Introdução e métodos básicos
* Aula12->Segmentação: Transformada de Hough - Fundamentos
* Aula13->Segmentação: Transformada de Hough - Aplicação
* Aula14->Segmentação: Gradientes (Adendo)
* Aula15->Segmentação: Watershed
* Aula16->Extração de Características: Forma, Dimensões e aspecto
* Aula17->Extração de Características: Texturas
* Aula18->Redução de dimensionalidade
* Aula19->Reconhecimento de Padrões: Introdução 
* Aula20->Classificadores Bayesianos
* Aula21->Agrupamentos
* Aula22->Redes Neurais Artificiais: Perceptron Simples 
* Aula23->Redes Neurais Artificiais: Perceptron Multicamadas
* Aula24->Validação
* Aula25->Rastreamento 
* Aula26->Redes Neurais Convolucionais
* Aula27->Detecção de Faces 
* Aula28->Detecção de Objetos
* Aula29->Arquitetura de Redes Neurais Convolucionais
* Aula30->Generative Adversarial Networks 

### Explanação das Aulas
#### Aula 8:
* Estudo das operações morfológicas (dilatação,erosão,abertura e fechamento)  e sua aplicação no
processamento de uma placa de carro.
#### Aula9:
* Estudo dos algoritimos morfológicos(extração de fronteiras, flood fill, componentes conectados,
hit or miss e esqueletonização).

#### Aula10:
* Utilização do GIMP (software de edição de imagens) para entendimento do gradiente morfológico. 
Estudo do processo de segmentação de textura para determinar regiões.

#### Aula11:
* Estudo do método de Otsu para limiarização e do método de Canny para segmentação pelas bordas.

#### Aula12:
* Implementação da transformada de Hough.

#### Aula13:
* Aplicação da transformada de Hough na detecção de uma pista de pouso para aviões.

#### Aula14:
* Aplicação do cálculo do gradiente pelo filtro de sobel para identificação de impressões digitais.

#### Aula15:
* Utilização do algoritimo de segmentação watershed (bacia hidrográfica)

#### Aula16:
* Utilização das funções de Canny,componentes conexas e cálculo da área de contorno para extração de características, 
aplicação na detecção de moedas pelo tamanho.

#### Aula17:
* Criação da Matriz de Diferença de Tons de Cinza a partir de uma imagem, e histogramas para extração de texturas.

#### Aula18:
* Estudos da técnica de Análise de Componentes Principais(PCA) para redução de dimensionalidade.

#### Aula19:
* Implementação do K-NN algoritimo básico de aprendizagem de máquina e aplicação na predição de gatos e cachorros.

#### Aula20:
* Utilização do Classificador Bayesiano para predição de gatos e cachorros.
*obs : Devido ,talvez,a versão do opencv utilizada, os módulos de inteligência artifical não estavam funcionando 
assim nesse e nas próximas aulas análogas(22,23) será utilizada a biblioteca sklearn do python.

#### Aula21:
* Estudo do algoritimo clássico de agrupamento k-médias(k-means)

#### Aula22:
* Estudo de redes neurais artificais -> Perceptron Simples, método de separação linear

#### Aula23:
* Perceptron Multicamadas , utilização de várias retas (hiperplanos) para divisão das classes.

#### Aula24:
* Estudo do método de Validação Cruzada para analisar precisão de modelos.

#### Aula25:
* Estudo do Algoritimo de Lucas-Kanade o qual utiliza fluxo óptico para rastreamento de pontos.

#### Aula26:
* obs: Como o exercício em questão se tratava de um tutorial do opencv porém em C++ e todas as aulas estão sendo 
utilizadas em python foi realizado um estudo inicial das Redes Neurais Convolucionais utilizando a lib pytorch do python.
*Introdução as RNC's , desenvolvendo um RCN simples para predição de dígitos no dataset MINIST.

#### Aula27:
* Detecção de faces utilizando o algoritimo de Viola Jones a partir de Haar Features.

#### Aula28:
*Compreensão teórica da obtenção de regiões dos algoritimos YOLO,faster RCNN  e SSD

#### Aula29:
* obs: Essa aula não foi executada devido a problemas de instalação do tensorflow , porém um tutorial semelhante é feito na aula 26 
com pytorch.

#### Aula30:
* Estudo sobre Generative Adversarial Networks(redes adversárias generativas) a qual tem o objetivo de aperfeiçoar parâmtros para 
reconhecimento de imagens partir de um gerador de imagens falsas.
