# Criação de Uma Base de Dados e Treinamento da Rede YOLO

## Detecção de Objetos com YOLOv5 no Google Colab

Este repositório contém um script em Python para detecção de objetos em imagens usando o modelo YOLOv5 pré-treinado no dataset COCO. O código foi desenvolvido para ser executado no Google Colab e permite detectar pessoas, carros e cachorros em uma imagem, com caixas delimitadoras coloridas e labels de confiança.

### Funcionalidades

- **Upload de Imagem**: Faça o upload de uma imagem diretamente no Google Colab.
- **Detecção de Objetos**: Detecta pessoas, carros e cachorros na imagem.
- **Caixas Delimitadoras Coloridas**:
  - Pessoas: Caixas verdes.
  - Carros: Caixas azuis.
  - Cachorros: Caixas vermelhas.
- **Labels de Confiança**: Exibe a confiança da detecção ao lado de cada objeto.
- **Exibição da Imagem Processada**: A imagem processada é exibida diretamente no Colab e salva como `imagem_processada.jpg`.

### Como Usar

1. **Acesse o Google Colab**:
   - Abra o Google Colab: [https://colab.research.google.com/](https://colab.research.google.com/).

2. **Copie e Cole o Código**:
   - Copie o código fornecido neste repositório e cole-o em uma nova célula no Colab.

3. **Execute o Código**:
   - Execute todas as células do código.
   - Quando solicitado, faça o upload de uma imagem do seu computador.

4. **Resultados**:
   - A imagem processada será exibida no Colab, com as detecções destacadas.
   - A imagem processada também será salva como `imagem_processada.jpg`.

### Requisitos

- Conexão com a internet (para instalar dependências e carregar o modelo YOLOv5).
- Uma imagem para teste (formato JPEG ou PNG).

### Exemplo de Saída

Aqui está um exemplo de como a imagem processada pode aparecer:

![Exemplo de Imagem Processada](imagem_processada.jpg)

- **Pessoas**: Caixas verdes.
- **Carros**: Caixas azuis.
- **Cachorros**: Caixas vermelhas.
