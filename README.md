# 2---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML

# Reconhecimento Facial e transformação de imagens em Dados no Azure ML

Passo a passo do desafio de projeto "Reconhecimento Facial e transformação de imagens em Dados no Azure ML" da DIO.

Links importantes:

- [Detected faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)  
- [Read text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)  
- [Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)  

## Passo 1: Criando recurso do Face API no Azure AI Services para detecção de faces humanas

Primeiro foi preciso criar um recurso de Face API dentro do Azure AI Services.

![Img](./img/img1.gif)

Após o recurso ter sido criado, foi acessado o [Portal de Visão do Azure](https://portal.vision.cognitive.azure.com/gallery/featured). Na página inicial, foi acessada a aba "Face" e clicado em "Detect faces in an images".

Na próxima página, em "Try it out", foi preciso informar o recurso criado anteriormente no Portal do Azure para testar. Não escolhendo o recurso, não consegui obter a resposta do teste.

![Img](./img/img2.gif)

Então subi uma foto minha e consegui obter o resultado do teste.

![Img](./img/img3.gif)

## Passo 2: Criando recurso do Computer Vision no Azure AI Services para detecção de texto em imagens

Primeiro foi preciso criar um recurso de Computer Vision dentro do Azure AI Services.

![Img](./img/img4.gif)

Após o recurso ter sido criado, foi acessado o [Portal de Visão do Azure](https://portal.vision.cognitive.azure.com/gallery/featured). Na página inicial, acessei a aba "Optical character recognition" e cliquei em "Extract text from images".

Na próxima página, em "Try it out", precisei informar o recurso criado de antemão no Portal do Azure para testar. Então tive que subir uma capa de um livro e consegui obter todas as palavras nela.

![Img](./img/img5.gif)

Este foi o resultado:

![Img](./outputs/OCR/Captura%20de%20tela%202024-02-10%20172337.png)

## Passo 3: Adicionando legendas em imagens

Para isso, foi usado o mesmo recurso de Computer Vision criado para o Passo 2. Na aba "Featured", cliquei em "Add captions to images". O recurso já estava marcado, então pude testar diretamente.

![Img](./img/img6.gif)

Resultado:

![Img](./outputs/Legendas/Captura%20de%20tela%202024-02-10%20174548.png)

## Passo 4: Excluir recursos após utilizá-los

Nesse passo, simplesmente exclui o recurso de Computer Vision para evitar cobranças surpresas.

![Img](./img/img7.gif)
