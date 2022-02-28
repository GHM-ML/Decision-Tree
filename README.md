# FSI-class-projects
ML projects for "CIC0193 - Fundamentos de Sistemas Inteligentes" class
The projects were requested with specific instructions, as follows:
- CLASSIFICADORES ÁRVORE DE DECISÃO E FLORESTAS RANDÔMICAS:
    Técnicas de Aprendizagem de Máquinas como Árvores de Decisão e Florestas Randômicas têm
    atingido excelentes resultados na predição/classificação diagnóstica de várias doenças. Um banco
    de dados foi coletado na África do Sul sobre doenças cardíacas. São 462 amostras com 10 variáveis.
    A variável chd (coronary heart disease, yes=1, no=0) é a classificação y.

    O projeto visa aplicar algoritmos de árvores de decisão e Florestas Randômicas para predição de
    diabetes com base nesses dados. Sua solução deverá incluir:

    1. Faça uma análise estatística inicial dos dados, plotando as quantidades médias, desvios padrões
    de todas as variáveis dos dados; 
    2. Construa um modelo de árvore de decisão (ID3, C4.5 ou CART), separando aleatoriamente
    sempre 10% dos dados para teste, em validação cruzada (com 10 rodadas), e mostre o resultado
    final em termos de: curva ROC, curva AUC ROC, e matriz de confusão. 
    3. Construa um modelo de “floresta randômica”, com 100 árvores, usando todas as variáveis
    preditoras (i.e. m=9), separando aleatoriamente sempre 10% dos dados para teste, em validação
    cruzada (com 10 rodadas), e mostre o resultado final em termos de: curva ROC, curva AUC ROC, e
    matriz de confusão. 
    4. Construa um modelo de “floresta randômica”, com 100 árvores, usando a raiz quadrada das
    variaǘeis preditoras (i.e. m=3), separando aleatoriamente sempre 10% dos dados para teste, em
    validação cruzada (com 10 rodadas), e mostre o resultado final em termos de: curva ROC, curva
    AUC ROC, e matriz de confusão. 
    5. Mostre, para o caso do melhor resultado, quais as 2 mais importantes/relevantes variáveis
    preditoras. 
    6. Gere, ou nos comentários do código, ou em um texto à parte as saídas e explicações pedidas no
    projeto. 
