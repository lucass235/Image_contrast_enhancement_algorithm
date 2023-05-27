# Algoritmo de Aumento de Contraste de Imagem

Melhoria de contraste em imagens de nível de cinza utilizando o otimizador BMO (Barnacles Mating Optimizer) com equalizador de histograma.

## Descrição

- Link do repositório original: [Projetos](https://github.com/ahmed-shameem/Projects)

- Link do artigo: [Artigo](https://ieeexplore.ieee.org/document/9195884)

### Introdução

- O algoritmo iEBMO (Image Enhancement using Barnacles Mating Optimizer) é uma abordagem que visa melhorar o contraste de imagens digitais. Ele utiliza o algoritmo de otimização global BMO, inspirado no comportamento reprodutivo dos cirrípedes, para mapear os níveis de cinza da imagem original em um novo conjunto de valores de nível de cinza. O iEBMO converte a imagem em tons de cinza para uma imagem binária, aplica o BMO para otimizar os pixels pretos e brancos da imagem binária e, em seguida, converte novamente em tons de cinza para gerar a imagem final com maior contraste. Esse método é comparado experimentalmente com outras técnicas populares de melhoria do contraste.

### Uso do algoritmo BMO

- O artigo aborda o iEBMO como uma técnica eficiente e eficaz de melhoria do contraste de imagens. Ele descreve como o iEBMO utiliza o BMO para otimizar os valores dos pixels pretos e brancos da imagem binária, maximizando a diferença entre as intensidades dos pixels pretos e brancos e melhorando o contraste da imagem original.

- O artigo também apresenta resultados experimentais que comparam a técnica proposta com outras técnicas populares de melhoria do contraste, como a Equalização de Histograma. Os resultados mostram que o iEBMO supera essas técnicas em termos de qualidade visual, avaliada por métricas como PSNR, SSIM e VIF. Além disso, o artigo também avalia a robustez do iEBMO em diferentes conjuntos de dados, incluindo Kodak, MIT-Adobe FiveK e H-DIBCO 2016/2018. Os resultados mostram que o iEBMO é capaz de produzir melhorias significativas no contraste em todas essas bases de dados.

- Em resumo, o artigo apresenta uma descrição detalhada do iEBMO e demonstra sua eficácia na melhoria do contraste em imagens digitais através de experimentos comparativos com outras técnicas populares.

### PSNR

- PSNR (Peak Signal-to-Noise Ratio) é uma métrica que mede a relação sinal-ruído de uma imagem. É comumente usado para avaliar a qualidade de imagens comprimidas ou processadas, comparando a imagem original com a imagem resultante. Quanto maior o valor do PSNR, melhor é a qualidade da imagem.

### SSIM

- SSIM (Structural Similarity Index) é uma métrica que mede a semelhança estrutural entre duas imagens. Ele leva em consideração fatores como luminância, contraste e estrutura para avaliar a qualidade visual de uma imagem. O valor do SSIM varia entre 0 e 1, sendo que um valor mais próximo de 1 indica maior semelhança entre as imagens.

### VIF

- VIF (Visual Information Fidelity) é uma métrica que mede a fidelidade da informação visual em uma imagem. Ele leva em consideração fatores como sensibilidade do sistema visual humano (HVS), distorções na imagem e estatísticas naturais da cena para avaliar a qualidade visual de uma imagem. O valor do VIF varia entre 0 e 1, sendo que um valor mais próximo de 1 indica maior fidelidade da informação visual na imagem.
