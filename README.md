# QuantizadorDeImagem
Neste projeto vamos comparar de maneira mais aprofundada duas estratégias
para quantizar imagens. Uma delas é a quantização uniforme e outra usa o
algoritmo de agrupamento K-Means. Além disso, vamos entender melhor o papel
que uma boa métrica de erro cumpre na hora de comparar soluções e determinar
sua qualidade.

## Questões abordadas:

### 1) Quantização uniforme
A) Plotar a imagem original, quantizada com valores minimos e valores médios e verificar as diferenças
B) Verificar o tamanho das imagens

### 2) Quantização por K-means
A) Quantizar usando kmeans com max_iter=10 e random_state=42
B) Comparando a imagem gerada para a quantização uniforme e kmeans com 64 cores

### 3) Calculo do erro
A) Calculo da inércia da imagem feita por kmeans
B) Calculo do MSE entre os pixels da imagem original e os da imagem quantizada

### 4) Verficar os resultados com a china.jpg e flower.jpg
A) Quantizar as duas imagens para {8, 27, 64, 125, 216} cores usando ambos os métodos de quantização (uniforme e K-Means) 
B) Compute e faça um plot da inércia dos resultados das quantizações do K-Means obtidas no item a)
C) Compute e faça um plot dos MSEs de ambas as estratégias.
D) Compute e faça um plot do tamanho e KBs das imagens quantizadas e compare com o tamanho em KBs da imagem original.
