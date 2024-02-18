# Previsão Aluguéis de Bicicletas usando autoML

# Introdução
Este projeto visa criar um modelo de previsão utilizando técnicas de aprendizado de máquina para o setor de previsão de vendas e aluguéis de bicicletas. O objetivo é utilizar dados históricos para prever a demanda futura por bicicletas, o que pode ser crucial para otimizar o estoque e maximizar os lucros.

# Dados Utilizados
Os dados utilizados neste projeto foram obtidos de um banco de dados público disponível em https://aka.ms/bike-rentals. Esses dados incluem informações sobre o número de bicicletas alugadas em diferentes momentos, bem como dados meteorológicos e sazonais relevantes. Os dados foram pré-processados para limpeza e transformação, garantindo que estejam prontos para análise e modelagem.

# Modelo de Previsão
O modelo de previsão foi construído utilizando algoritmos de aprendizado de máquina, especialmente adaptados para lidar com séries temporais. Diferentes modelos foram testados e avaliados com base em métricas de desempenho, como erro médio absoluto (MAE) e erro quadrático médio (MSE). As análises gráficas também foram realizadas para comparar as previsões com os dados reais e garantir a precisão do modelo. Os resultados mostraram que o modelo é capaz de fazer previsões com boa precisão, alinhadas com a estratégia de aluguel para o lucro.

# Instruções para Interação com o Modelo
Os usuários podem interagir com o modelo de previsão por meio de pontos de extremidade configurados no Azure. Os pontos de extremidade são URLs fornecidas pelo Azure que permitem que os usuários enviem solicitações de previsão para o modelo e recebam as previsões correspondentes. Para utilizar o modelo, os usuários precisarão enviar os dados relevantes, como informações temporais e meteorológicas, para o ponto de extremidade e aguardar a resposta com a previsão.

# Outras Informações Relevantes
Além das previsões individuais, o modelo também pode ser integrado a sistemas de gerenciamento de estoque e planejamento de produção para fornecer insights valiosos sobre a demanda futura por bicicletas. Isso pode ajudar as empresas a otimizar seus recursos e maximizar seus lucros. Além disso, o código-fonte e a documentação completa do projeto estão disponíveis no repositório do GitHub, permitindo que os usuários entendam e modifiquem o modelo conforme necessário.

