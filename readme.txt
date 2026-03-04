1. Base de dados

Para o teste foi utilizada a base de dados "complaints_processed.csv", anexada no projeto git;


2. Dados testados

Inicialmente foram utilizados 50 mil registros e depois a base completa. Em escala de tempo aproximado, o processamento levou:

50 mil registros: cerca de 25 minutos
162.421 registros: cerca de 1 hora

Em caso de teste de quantidades diferentes, tirar o comentário do trecho abaixo no notebook e ajustar ao seu critério:

#df = df.sample(50000, random_state=42)

Obs.: além de variar o tempo de processamento, também pode haver variações na acurácia do modelo.