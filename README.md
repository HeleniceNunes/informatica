# informatica
* Quantos alunos existem de cada país, considerando todas as escolas?
## =SOMASE(amostra!H:H,perg1!A3,amostra!I:I)
* Quantas nacionalidades de alunos existem em cada escola?
## =CONT.SE(amostra!G:G,perg2!A3)
* Quantas nacionalidades de alunos existem em cada município?
## =CONT.SE(D:D,A3)
Qual nacionalidade está com maior número de alunos presentes no estado de São Paulo?
## =SOMASE(amostra!H:H,perg1!A3,amostra!I:I)
Mapeamento de causa de acidentes de Trânsito no País.

* 1)Destacar um gráfico das 5 maiores causas de acidentes de trânsito no país.
## =CONT.SE(acidentes2024_todas_causas_tipo!K:K,A2)
* 2) Nas estatísticas de acidentes quantas pessoas ficaram ilesas, sofreram ferimentos e morreram nas estradas do país?
## =SOMASE(acidentes2024_todas_causas_tipo!$F:$F,'Vitimas Acidentes'!$A2,acidentes2024_todas_causas_tipo!AF:AF)
* 3) Quantos Condutores com menores de 18 anos e maiores de 40 foram envolvidos nos acidentes no País?
## =SOMASE(acidentes2024_todas_causas_tipo!$AA:$AA,">40",acidentes2024_todas_causas_tipo!$AF:$AF)
* 4) Análise de tipos de acidentes com vítimas.
## =SOMASE(acidentes2024_todas_causas_tipo!$M:$M,'Tipo de Acidente'!A2,acidentes2024_todas_causas_tipo!AC:AF)
* 5) Quantas ocorrências aconteceram por ano de Fabricação do Veículo?
## =CONT.SE(acidentes2024_todas_causas_tipo!X:X,'Ano do Veículo'!A2)
