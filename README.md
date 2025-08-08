# Projeto-para-reducao-de-dimensionalidade-em-imagens.

Nesse projeto foi ultilizado Python, Google Colab, bibliotecas (PIL, NumPy, Matplotlib)

Google Colab, o código:

- Permite fazer upload de uma imagem.

- Converte a imagem para escala de cinza.

- Depois a transforma em preto e branco (binária) com base em um limiar.

- Por fim, exibe as 3 versões da imagem: original, cinza e binária.

Converte uma imagem para escala de cinza e binarizada (preto e branco) em aplicações de machine learning (ML) e visão computacional, tarefa relacionada a reconhecimento de padrões, classificação de imagens, OCR, bases para pré-processamento, entre outros.

  🔹 Escala de Cinza (0–255)\
Motivo de uso:
  Reduz a complexidade dos dados, mantendo informações visuais importantes (bordas, formas, contrastes).

Aplicações:

- Classificação de imagens	Facilita redes neurais processarem imagens com menos dados (1 canal em vez de 3 RGB). 
- Redes neurais convolucionais (CNNs)	Imagens em tons de cinza podem acelerar o treinamento, especialmente quando cores não são relevantes.
- Detecção de bordas (Canny, Sobel)	Baseiam-se no contraste (diferença de intensidade), não na cor.
- OCR (Reconhecimento de Texto)	A cor não importa; o contraste entre letra e fundo sim.

🔸 Imagem Binarizada (0 ou 255)\
Motivo de uso:
  Elimina ruídos e destaca apenas o que é "importante", útil para decisões simples (ex: objeto presente ou não).

Aplicações:

- OCR (leitura de documentos)	Binarização isola texto do fundo.
- Pré-processamento para segmentação	Facilita identificar regiões de interesse (ex: células, letras, placas).
- Visão computacional industrial	Inspeção de peças com falhas (preto = falha, branco = ok).
- Reconhecimento de escrita	Binariza a escrita à mão para detectar traços.

