O objetivo deste estudo foi desenvolver um modelo para a predição de lesões dermatológicas pigmentadas. Utilizou-se uma base de dados contendo metadados do paciente (idade, sexo, localização da lesão) e imagens dermatoscópicas.

Inicialmente, foi ajustado um modelo de regressão logística utilizando apenas os metadados, com o intuito de obter um modelo interpretável. Contudo, o desempenho foi insatisfatório, com erros em todas as predições para algumas classes. Em seguida, foram incorporadas informações das imagens utilizando Análise de Componentes Principais (PCA) e Máquinas de Vetores de Suporte (SVM), o que resultou em melhores resultados, embora algumas classes ainda apresentassem dificuldades. Finalmente, foram desenvolvidos modelos com redes neurais, incluindo LeNet-5 e uma ResNet com ajuste fino, alcançando mais de 97% de acurácia e boa precisão em todas as classes.


Link para o colab notebook
https://colab.research.google.com/drive/1SFVG7M5JNY9a0FofWvAlX9gaN5lGHHYu?usp=sharing
