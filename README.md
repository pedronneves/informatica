# informatica
Tarefas de Informática
## primeira tarefa: apresentação
#3.1=SOMASE('3'!$H$2:$H$5891;A2;'3'!$I$2:$I$5891)
#3.2=CONT.SE('3'!$G$2:'3'!$G$6000;A2)
#3.3
#3.4

## segunda tarefa: Demonstrativo de acidentes de transito nas estradas federais no Brasil.
#1. Destacar um gráfico das 5 maiores causas de acidentes de trânsito no país
# =CONT.SE(acidentes2024_todas_causas_tipo!K:K,A2)

#2. Nas estatísticas de acidentes quantas pessoas ficaram ilesas, sofreram ferimentos e morreram nas estradas do país? 
# =SOMASE(acidentes2024_todas_causas_tipo!$F:$F,'Vitimas Acidentes'!$A2,acidentes2024_todas_causas_tipo!AC:AC)
# =SOMASE(acidentes2024_todas_causas_tipo!$F:$F,'Vitimas Acidentes'!$A2,acidentes2024_todas_causas_tipo!AD:AD)
# =SOMASE(acidentes2024_todas_causas_tipo!$F:$F,'Vitimas Acidentes'!$A2,acidentes2024_todas_causas_tipo!AE:AE)
# =SOMASE(acidentes2024_todas_causas_tipo!$F:$F,'Vitimas Acidentes'!$A2,acidentes2024_todas_causas_tipo!AF:AF)

#3 Quantos Condutores com menores de 18 anos e maiores de 60 foram envolvidos nos acidentes no País? 
# =SOMASE(acidentes2024_todas_causas_tipo!$AA:$AA,"<18",acidentes2024_todas_causas_tipo!$AF:$AF) - obitos
# =SOMASE(acidentes2024_todas_causas_tipo!$AA:$AA,"<=18",acidentes2024_todas_causas_tipo!$AD:$AE) - feridos
=SOMASE(acidentes2024_todas_causas_tipo!$AA:$AA,"<18",acidentes2024_todas_causas_tipo!$AC:$AC) - ilesos

#4 Análise de acidentes diários nos 7 dias da semana 
# =SOMASE(acidentes2024_todas_causas_tipo!$D:$D,'Dia da Semana'!A2,acidentes2024_todas_causas_tipo!AC:AF)

#5 Quantas ocorrências aconteceram por ano do Veículo? 
# =CONT.SE(acidentes2024_todas_causas_tipo!X:X,'Ano do Veículo'!A2)
