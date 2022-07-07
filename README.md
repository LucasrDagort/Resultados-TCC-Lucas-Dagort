Neste repositório se encontram os resultados completos do meu TCC

O respositório possui dois arquivos principais:
  - O arquivo Resultados Validação Base de Treinamento se refere à validação do modelo PAR parametrizado utilizando uma curva de geração prevista retirada da base de treinamento. A curva escolhida corresponde ao período entre 02/01/2021 à 31/01/2021
  - O arquivo Resultados Validação Final se refere à validação utilizando uma curva de geração prevista de uma base externa do modelo. A curva escolhida corresponde ao período entre 02/01/2022 à 31/01/2022
  
  Em cada um dos arquivos de resultados possui a mesma estrutura:
    - Arquivo Gráficos: Possui os boxplots dos desvios gerados comparados aos desvios observados. Possui igualmente os gráficos os cenários de geração prevista ajustados
    - Arquivo Validação Correlação Espacial: Contém os valores da correlação espacial calculada entre os dados de desvios errados e a curva de geração prevista utilizada       para gerar os desvios. 
    - Validação métricas: Contém os valores de média, desvio padrão, mediana, assimetria entre outroas métrica calculadas a partir dos desvios gerados
    - Arquivo Validação PEPACF: possui as correlaçãoes temporais entre os desvos gerados e a curva de geração prevista utilizada para gerar os desvios.  
    - Excel Cenarios Desvios Após Truncamento: Desvios gerados após o pós-processamento
    - Excel Cenários Geracao Ajustada Após Truncamento : geração prevista ajustada pelos desvios truncados 
