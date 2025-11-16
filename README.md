# Summit-UMC

O estudo utiliza o conjunto de dados Pima Indians Diabetes, amplamente conhecido em pesquisas sobre predição de diabetes, contendo atributos biomédicos como glicose, pressão arterial, IMC, espessura da pele e idade.
O objetivo principal é avaliar o impacto da estratégia de validação cruzada no desempenho do modelo SVM, comparando: KFold-10 (validação cruzada padrão)
RepeatedStratifiedKFold (10×3)Repetindo o processo 3 vezes e preservando o balanceamento das classes 
Além disso, o código inclui: Tratamento de valores ausentes (zeros transformados em NaN) Imputação com média
Padronização dos atributos (StandardScaler)
Busca de melhores hiperparâmetros com GridSearchCV
Comparação por acurácia, desvio padrão e matrizes de confusão


# Instruções de Execução (Google Colab)
Método 1 — Executar direto no Colab

  Abra o Google Colab:
  https://colab.research.google.com/

 
  Clique em:
  Arquivo → Fazer upload do notebook

  
  Envie o arquivo:
  modelo_svm_diabetes.ipynb (localizado na pasta /codigo)

 
  Execute todas as células com:
  Ambiente → Executar tudo


  O código já está configurado para:
  Baixar automaticamente o dataset do GitHub

  Realizar pré-processamento

  
  Fazer GridSearchCV

 
  Gerar gráficos das matrizes de confusão

 
  Exibir acurácias, desvios padrão e conclusão

  
  Nada precisa ser configurado manualmente.
