# Analise Temporal Covid


Para esse estudo, analisei os dados do [Painel Covid - Ministério da Saúde](https://covid.saude.gov.br/) sobre a pandemia do novo coronavirus no Brasil, onde temos valores de casos diários e óbitos diários. Nele temos a granularidade de casos de três nivéis territoriais, País, Estado, Município. O objetivo desse estudo é utilizar de projeções/previsões de obitos na cidade e estado de São Paulo e no Brasil para compreender mais sobre a evolução da pandemia no país e o que podemos esperar do futuro se as condições continuarem iguais.


A primeira parte do projeto foi destinado para tratar os dados, reconhecer os padrões e fazer as alterações necessárias, neste caso foram criadas colunas de: 
 - Médias Móveis de óbitos e casos de 7, 10 e 14 dias;
 - Óbitos e Casos por 100mil habitantes;
 - Média móvel de casos e óbitos dos valores de casos e óbitos por 100mil habitantes.
 
Em segundo momento, foram plotados gráficos para estudar a situação da pandemia e sua evolução desde o seu ínicio.

O terceiro ponto do projeto foi a decomposição sazonal pra compreender os pormenores da serie temporal.

Por fim e o mais importante foi a utilização do Prophet para fazer uma previsão de óbitos nas regiões selecionadas de estudo e plotar em gráficos que mostram o que deve acontecer no futuro, caso as tendências continuem iguais e caso não existam medidas para tentar suprimir os casos e óbitos.
