Existem dois arquivos que podem ser renderizados para gerar o relatório:

- desafio1Pedro.Rmd
- desafio1Pedro.qmd

Ambos possuem o mesmo contéudo, porém geram relatórios que diferem quanto a formatação.
A versão oficial do trabalho é **desafio1PedroOficial.html**, mas também está disponível a versão em .pdf
**desafio1PedroOficial.pdf. Ambas geradas pelo código em .qmd.

A versão .pdf gerada pelo arquivo .Rmd está disponível como **desafio1Pedro.pdf**.


Caso não possua Quarto Markdown:
Você pode ir para o site oficial -> https://quarto.org/docs/download/
ou abrir o arquivo referente no RStudio que geralmente mostra uma mensagem avisando que você não possui o programa.


Tempo de Execução:
O tempo de execução para gerar o relatório pode chegar a até 15minutos devido ao processo de estimação
bayesiano.

Dependências:
A pasta 'models' contém o modelo bayesiano usado na estimação
Os arquivos baseprincipal.csv se refere a amostra de 2000 indivíduos retiradas de coverageX.txt usando a semente aleatória 10727865.
Já baseteste.csv e basetreino.csv refere-se ao conjunto de teste e treino, também amostrados com a semente 10727865


