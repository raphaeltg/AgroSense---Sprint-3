# AgroSense---Sprint-3


Vídeo Youtube: https://youtu.be/K4WR5P36Wwg


Contexto:                                        
Esse dataset contém imagem dos seguintes alimentos:
fruits- banana, apple, pear, grapes, orange, kiwi, watermelon, pomegranate, pineapple, mango. vegetables- cucumber, carrot, capsicum, onion, potato, lemon, tomato, raddish, beetroot, cabbage, lettuce, spinach, soy bean, cauliflower, bell pepper, chilli pepper, turnip, corn, sweetcorn, sweet potato, paprika, jalepeño, ginger, garlic, peas, eggplant.


Conteúdo:                                 
Esse dataset contém 3 pastas:
train (100 imagens cada)
test (10 imagens cada)
validation (10 imagens cada)
cada pasta acima tem uma subpasta pra cada alimento


Inspiração:                                 
A ideia é gerar um aplicativo que reconhece qual o alimento da foto e dá sugestões de receitas e utilizações do mesmo.


Sobre o Notebook:
O notebook fornecido implementa funcionalidades relacionadas ao processamento e classificação de imagens utilizando técnicas de aprendizado de máquina. Inicialmente, são instaladas e importadas bibliotecas essenciais, como TensorFlow, Keras, OpenCV, NumPy e Pandas, que são fundamentais para manipulação de dados, construção de modelos e visualização de resultados. O código também utiliza ferramentas específicas para otimizar o desempenho do modelo, como o EarlyStopping, ModelCheckpoint e ReduceLROnPlateau, além de bibliotecas para silenciar avisos do TensorFlow e melhorar a legibilidade do ambiente.

A arquitetura de IA escolhida no projeto é a MobileNetV2, uma rede neural convolucional voltada para dispositivos com recursos computacionais limitados. Essa arquitetura é eficiente em termos de desempenho e velocidade, sendo adequada para tarefas de classificação de imagens. Ela foi escolhida devido à sua capacidade de balancear precisão e eficiência computacional, o que a torna ideal para projetos que exigem um modelo leve e rápido. A MobileNetV2 foi implementada através do uso da API tensorflow.keras.applications, que facilita a importação de arquiteturas pré-treinadas, permitindo a adaptação para o conjunto de dados específico utilizado no projeto. A implementação inclui o uso de camadas adicionais para personalizar a saída do modelo e otimizar seu desempenho para a tarefa em questão.
