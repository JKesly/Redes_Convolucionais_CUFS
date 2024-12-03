# Redes_Convolucionais_CUFS

Objetivo do Projeto: Projeto apresentado como nota da unidade 10 do projeto Restic36. Tem como objetivo explorar os conhecimentos em Redes Neurais Convolucionais, aplicando modelos CNNs autorais no banco de dados CUHK Face Sketch Database (CUFS), gerando modelos capazes de distinguir entre imagens de pessoas do sexo masculino e feminino com precisão.

Instruções para Execução do Código: O banco de dados abordado se encontra em: https://www.kaggle.com/datasets/arbazkhan971/cuhk-face-sketch-database-cufs
Após baixá-lo, e salvá-lo no drive pessoal, deve-se dividir o arquivo "photos" em duas pastas diferentes (recomendado: male, female)
Assim, executando todas as células encontradas no código, na direção na qual aparecem (de cima para baixo), e, conjuntamente, importando as livrarias necessárias do Python, deve-se ser possível acessar os mesmos resultados descritos no documento em pdf.

Principais Conclusões e Considerações: O primeiro modelo gerado foi o mais bem sucedido, tendo uma acurácia de mais de 70% em classificar as imagnes.
Os dois outros modelos, embora tenham tido uma boa acurácia, também apresentaram alta perda ou ainda um custo computacional elevado.
As matrizes de confusão geradas revelam que todos os modelos acertam mais em identificar quando a foto não se trata de uma homem ou de uma mulher cirretamente, do que acertar com exatidão quando é realmente uma pessoa do sexo masculino ou feminino. 

Uma hipótese para isso é que a base de dados é pequena, dispondo de apenas 188 imagens - das quais 133 são homens e 55 são melhures, todos da mesma etnia.

Alunas: Clara Raquel Santos e Jemyma Kesly M. da Silva
