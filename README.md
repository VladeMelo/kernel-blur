<h1 align="center">Kernel for Blurring<h1>
  
![add0padding](https://github.com/VladeMelo/kernel-blur/assets/63476377/78dd8139-4cd3-4094-af43-2abc27a94f85)

## 1. Objetivo

Borrar uma imagem que possua 3 canais de cores (RGB)

## 2. Etapas

- Normalizar a Imagem
- Separar o canais Red, Green e Blue
- Aplicar o kernel Gaussian Blur em cada canal de cor, utilizando o padding Valid
  ![Figure2](https://github.com/VladeMelo/kernel-blur/assets/63476377/1b91043c-b39f-4f00-a728-eac4eb4d98da)
- Juntar o 3 canais de cores novamente com seus novos valores e ver a imagem resultante
