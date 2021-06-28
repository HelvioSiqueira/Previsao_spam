# Previsao_spam
Previsão de spam na caixa de emails

# Analise Exploratoria

O problema consiste em prever se o email enviado é um spam ou não a partir das palavras usadas para redigir tal email.
O dataset conta com 5172 linhas e 3002 colunas(com as palavras que poderiam aparecer no email), sendo a ultima
a informação se é um spam(1) ou não(0).

![alt text](https://github.com/HelvioSiqueira/Previsao_spam/blob/main/public/imagens/tamanho.png "Tamanho do dataset")

O dataset não contem dados nulos e está com os dados totalmente com o formato inteiro(int64).

![alt text](https://github.com/HelvioSiqueira/Previsao_spam/blob/main/public/imagens/nulos.png "Quantidade de nulos por coluna")

Os registros(emails) estão relativamente balanceados contendo uma maior quantidade de email não spam e pouco menos da
metade de emails spam, optei inicialmente por não balancear mais(com undersampling ou oversampling) os registros.

![alt text](https://github.com/HelvioSiqueira/Previsao_spam/blob/main/public/imagens/dados.png "Quantidade de nulos por coluna")

