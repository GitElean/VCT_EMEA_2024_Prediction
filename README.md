# VCT_EMEA_2024_Prediction

## English

### Introduction
Machine and deep learning have become fundamental pillars in problem-solving, and sports, including electronic sports, are no exception. This project aimed to create a predictive model capable of forecasting the regular season results of the VCT EMEA 2024 in the VALORANT Champions Tour. Data was collected from the Vlr.gg and thespike.gg statistics websites, which were used for model design. Initially, a random forest algorithm was employed to determine the most useful parameters for the model. Subsequently, the model was constructed using feedforward neural networks, as this architecture was sufficient for the classification task at hand. Once the model was defined, various optimization tests were conducted, including adjusting hyperparameters, implementing regularization, and experimenting with different activation functions such as ReLU, Leaky ReLU, SWISH, and GeLU. The most significant challenge faced by these neural networks was undoubtedly overfitting due to the limited data available; nevertheless, it was possible to create a predictive model with an acceptable level of accuracy and loss despite the overfitting issue.

#### Dataset Information
- **team**: Name of the team participating in the league.
- **wins**: Total matches won.
- **loss**: Total matches lost.
- **map_wins**: Number of maps won.
- **map_lost**: Number of maps lost.
- **round_win**: Number of rounds won.
- **round_loss**: Number of rounds lost.
- **round_differential**: Difference between rounds won and lost.
- **team_rating**: Overall team rating relative to the thespike.gg ranking.
- **standing**: Final position in the regular league.

#### Technology Used:
- **Python**: As the core engine for all programming and construction, from exploratory analysis to neural network construction.
- **SkLearn**: Used for data preprocessing, such as scaling or normalizing, as well as for model evaluation and the random forest algorithm.
- **TensorFlow**: Utilized Keras within TensorFlow to create custom activation functions, and for model compilation, training, and evaluation. Also used key functions like ADAM, L1, L2.
- **Matplotlib**: Employed for graphing, both in exploratory analysis and result presentation.
- **Numpy**: Utilized for mathematical functions such as pi or mean, essential in creating activation functions and testing.
- **Pandas**: Mainly used for handling data frames.
- **Jupyter Notebook**: The tool used for visualizations and code management.

## Español

### Introducción
El aprendizaje automático y profundo se ha vuelto un pilar fundamental en la resolución de problemas, y el caso de los deportes no se queda fuera, o este caso los deportes electrónicos. En este trabajo se buscó realizar un modelo predictivo que fuera capaz de darnos los resultados de la temporada regular de la VCT EMEA 2024 del champions Tour de VALORANT. Para esto se realizó una obtención de datos a través de las web de estadistícas Vlr.gg y thespike.gg, las cuales fueron usadas para el diseño del modelo. Seguidamente para explorar los parámetros más convenientes para el modelo se usó un algoritmo random forest para determinar cuales serían más útiles. Después de esto se pasó a la construcción del modelo a través de redes neuronales feedforward dado a ser una tarea de clasificación con esta arquitectura fue suficiente para dicha tarea. Una vez el modelo fue definido se pasó a las pruebas para la optimización de esta, dentro de los cambios realizados se exploró el cambio de hiperparametros, el uso de regularización, y el cambio de funciones de activación, entre ellas ReLu, Leaky ReLu, SWISH y GeLu. El mayor reto que enfrentó esta serie de redes neuronales fue sin ninguna duda el sobreajuste debido al bajo número de datos; aún así fue posible crear un modelo predictivo con un nivel aceptable de precisión y perdida a pesar del sobreajuste.

#### Información del dataset
- **team**: Nombre del equipo participante en la liga.
- **wins**: partidos totales ganados.
- **loss**: partidos totales perdidos.
- **map_wins**: número de mapas ganados.
- **map_lost**: número de mapas perdidos.
- **round_win**: número de rondas ganadas.
- **round_loss**: número de rondas perdidas.
- **round_differential**: diferencia entre rondas ganadas y perdidas.
- **team_rating**: rating global del equipo relativo al ranking de thespike.gg.
- **standing**: posición final de la liga regular.

#### Tecnología usada:
- **Python**: Como motor básico y central de toda la programación y construcción, desde el análisis exploratorio hasta la construcción de la red neuronal.
- **SkLearn**: Se usó para el preprocesamiento de datos, como escalar o normalizar, también para la evaluación del modelo y por supuesto en el random forest.
- **TensorFlow**: Con TensorFlow utilizamos Keras para crear funciones de activación personalizadas, para la propia compilación, entrenamiento y evaluación del modelo. Aparte de funciones clave como ADAM, L1, L2.
- **Matplotlib**: Se usó para las gráficas, tanto del análisis exploratorio como de los resultados.
- **Numpy**: Se hizo uso de algunas funciones matemáticas de numpy como pi o mean, para hacer funciones de activación y testeo.
- **Pandas**: Principalmente para manejar los data frames.
- **Jupyter Notebook**: Fue la herramienta utilizada para las visualizaciones y administración del código.
