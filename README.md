# Film Junky Union - Aprendizado Automático de Textos

## Descrição do Projeto

A Film Junky Union, uma nova comunidade para entusiastas de filmes clássicos, está desenvolvendo um sistema para filtrar e categorizar resenhas de filmes. O objetivo é treinar um modelo para detectar automaticamente resenhas negativas. Usaremos um conjunto de dados de resenhas de filmes do IMDB com rotulagem de polaridade para criar um modelo para classificar resenhas como positivas e negativas. Ele precisará atingir um valor F1 de pelo menos 0,85.

## Instruções do Projeto
1.	Carregar os dados.
2.	Pré-processar os dados, se necessário.
3.	Conduzir uma AED e tirar conclusões sobre o desequilíbrio de classe.
4.	Pré-processar os dados para modelagem.
5.	Treinar pelo menos três modelos diferentes para o conjunto de dados de treinamento fornecido.
6.	Testar os modelos para o conjunto de dados de teste fornecido.
7.	Escrever algumas resenhas e classificá-las usando todos os modelos.
8.	Verificar as diferenças entre os resultados dos testes dos modelos nos dois pontos acima. 
9.	Apresentar descobertas.

## Descrição dos Dados
Os dados são armazenados no arquivo imdb_reviews.tsv. 
Os dados foram fornecidos por Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng e Christopher Potts. (2011). Vetores de aprendizado de palavras para análise de sentimentos. A 49ª Reunião Anual da Association for Computational Linguistics (ACL 2011).

Aqui está a descrição dos campos selecionados:
-	review: o texto da resenha
-	pos: o objetivo, '0' para negativo e '1' para positivo
-	ds_part: 'train'/'test' para a parte de treinamento/teste do conjunto de dados, respectivamente

