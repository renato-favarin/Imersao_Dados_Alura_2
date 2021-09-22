# Piauí: esforçado na educação, porém (ainda) pouco recompensado

Certa vez li uma matéria sobre investimento por aluno na educação pública . Era uma reportagem que mostrava uma aparente correlação entre o orçamento para a educação pública e o desempenho estudantil, segundo o Ideb (Índice de Desenvolvimento da Educação Básica) em diferentes estados brasileiros; porém, focando nos dez estados com os piores índices. Tal leitura foi há alguns anos. 

Eis os dois primeiros parágrafos daquela reportagem de 2011 [(UOL Educação)](https://educacao.uol.com.br/noticias/2011/02/22/seis-dos-dez-estados-com-pior-qualidade-de-educacao-investem-menos-por-aluno.htm):

<p align="center">
<img src="img/noticia_educacao.jpg" alt="Drawing" style="width: 600px;">
</p>

Desde a reportagem até o Enem 2019 passaram-se quase 10 anos.
 
Vamos verificar se o desempenho dos candidatos do Enem 2019 nos seis estados citados na notícia sugere algum avanço após esse período. A figura a seguir apresenta um diagrama de caixa, comparando o desempenho destes seis estados com o restante dos estados brasileiros, mas apenas dos candidatos que cursam ou cursaram o ensino médio em escola pública:

<p align="center">
<img src="img/notas_totais_escola_publica.png" alt="Drawing" style="width: 600px;"/>
</p>       

Conforme pode ser observado, todos os estados citados na reportagem apresentaram uma curva de desempenho inferior aos demais estados do Brasil. Um ponto de atenção, em especial, é o estado do Pará, onde quase metade dos *outliers* das maiores notas estão dentro do *whisker* superior do conjunto formado pelos demais estados. **Mas será que esses seis estados são justamente os que apresentaram o pior desempenho de candidatos oriundos do ensino público no Enem 2019?**

Para responder a esta questão, analisamos a figura seguinte, que traz a mediana dos dez menores desempenhos dos candidatos que cursam ou cursaram o ensino médio em escola pública. Como comparação, também traz a informação dos candidatos que cursam ou cursaram o ensino médio em escolas privadas dos respectivos estados:

<p align="center">
<img src="img/mediana_10_menores_desemp_esc_publica.png" alt="Drawing" style="width: 900px;"/>
</p>    

De acordo com a figura acima, **dentre os dez estados que apresentaram os piores desempenhos no Enem 2019 (escola pública), constam três (PA, AL e PI) dos seis estados** citados naquela reportagem de 2011.

No entanto, o que mais chama a atenção é a diferença dos resultados da prova entre candidatos da escola pública em relação aos da escola privada. Vamos investigar um pouco melhor isso a seguir. A próxima figura apresenta o mesmo diagrama de caixa abordado anteriormente; porém, somente com os candidatos do ensino privado:

<p align="center">
<img src="img/notas_totais_escola_privada.png" alt="Drawing" style="width: 600px;"/>
</p>

As diferenças das curvas dos desempenhos dos candidatos daqueles seis estados citados na notícia inicial, em comparação com o conjunto formado pelos demais estados do Brasil, não são tão significativas quanto foram para o ensino público, com exceção de Alagoas.

Nota-se, ainda, que o desempenho dos candidatos que cursam ou cursaram o ensino privado no Piauí ficou acima da mediana do conjunto de candidatos dos demais estados do Brasil; ou seja, **enquanto no ensino público o Estado do Piauí "puxa" a mediana do Brasil para baixo (conforme foi visto na Figura 1), no ensino privado ocorre o oposto**.

**Considerando todos os estados do Brasil, seria o Piauí aquele com a maior desigualdade de desempenho entre candidatos do ensino público e privado?** A figura a seguir apresenta as dez maiores diferenças da mediana do desempenho entre esses candidatos no Enem 2019:

<p align="center">
<img src="img/mediana_10_maiores_dif_esc_publ_privada.png" alt="Drawing" style="width: 750px;"/>
</p>

Após analisar a figura acima, **verifica-se que Piauí não foi o primeiro, mas o segundo estado com a maior desigualdade entre os desempenhos do Enem 2019 por tipo de escola.**

Neste momento, já temos as seguintes constatações sobre Piauí:

- Um dos seis estados que menos recebia investimento por aluno no Brasil em 2011;
- Apresentou baixo resultado no Ideb da rede estadual naquele ano;
- O seu ensino público no Enem 2019 figurou entre as últimas colocações do Brasil;
- O seu ensino privado, por sua vez, ficou acima da mediana do Brasil;
- Foi o segundo estado com maior disparidade de desempenho entre o ensino privado e público no Enem 2019.

A partir dessas reflexões surgem vários questionamentos:

- O que pode ser feito para melhorar o ensino público e atenuar a diferença no estado do Piauí?
- Qual a expectativa sobre o futuro? Um aumento ou diminuição da disparidade do desempenho entre os ensinos públicos e privados?
- Quais outros indicadores socioeconômicos podem ser correlacionados com tal diferença e, portanto, monitorados para futuras previsões, análises e ações?

Cada um destes questionamentos pode resultar em novas investigações. Para a presente análise, **vamos buscar um indicador socioecônomico chamado índice de Gini**. Antes, uma breve explicação a respeito dele:


> índice (ou coeficiente) de Gini: Medida de desigualdade relativa obtida a partir da Curva de Lorenz, que relaciona o percentual acumulado da população em ordem crescente de rendimentos (eixo x) e o percentual acumulado de rendimentos (eixo y). Quando os percentuais acumulados de população correspondem aos percentuais acumulados de rendimentos (10% da população com 10% dos rendimentos, por exemplo), tem se a linha de perfeita igualdade. A Curva de Lorenz representa a distribuição real de rendimentos de uma dada população tendo, em geral, formato convexo. Quanto mais afastada da linha de perfeita igualdade, mais desigual a distribuição. O índice de Gini é uma medida numérica que representa o afastamento de uma dada distribuição de renda (Curva de Lorenz) da linha de perfeita igualdade, variando de “0” (situação onde não há desigualdade) e “1” (desigualdade máxima, ou seja, toda a renda apropriada por um único indivíduo).<br> Fonte: [Síntese de indicadores sociais. Uma análise das condições de vida. IBGE, 2018.](https://biblioteca.ibge.gov.br/visualizacao/livros/liv101629.pdf)

A próxima figura traz os valores do índice de Gini desde o seu início (2012) até 2019, por estado. O tamanho de cada barra representa o somatório do índice de Gini em cada ano. Dessa maneira, é uma forma apropriada de representar, em um só gráfico, todo o histórico desse índice disponível no [portal do IBGE](https://www.ibge.gov.br/estatisticas/sociais/rendimento-despesa-e-consumo/17270-pnad-continua.html?edicao=27257&t=resultados):

<p align="center">
<img src="img/serie_indice_gini.png" alt="Drawing" style="width: 1710px; height: 400px"/>
</p>

Como pode ser observado, **o estado do Piauí é o segundo com a renda mais desigual no Brasil**.

Além do Piauí, outros três estados que estão entre os que tiveram maior desigualdade no desempenho no Enem 2019 também estão entre os dez que apresentaram as maiores desigualdades de renda: AM, CE e BA.

Vamos verificar, agora, os dez estados menos desiguais no desempenho no Enem 2019, destacando-se os estados que estão entre os dez menos desiguais na renda, conforme a figura anterior:

<p align="center">
<img src="img/mediana_10_menores_dif_esc_publ_privada.png" alt="Drawing" style="width: 750px"/>
</p>

Constata-se que cinco estados (AL, SC, PR, RO e RS) estão entre os que apresentaram as menores diferenças entre ensino público e privado no desempenho no Enem 2019 e que também figuram entre os dez estados com menor desigualdade na renda. Repare que isso não indica necessariamente que o desempenho do ensino público nestes estados foi bom; mas, apenas, foi menos desigual em relação ao ensino privado.

**Levanta-se uma hipótese: seria a falta de investimento por aluno na educação pública somada à alta desigualdade na renda a responsável pelas maiores diferenças de desempenho dos candidatos no Enem 2019 entre os ensinos público e privado?**

Para respondê-la são necessários mais dados; por exemplo, pode-se obter a série histórica de investimentos na educação pública por aluno na educação fundamental e estudar a correlação no desempenho do Enem alguns anos depois (quando o aluno estava terminando o ensino médio). Fica, portanto, a primeira sugestão de um trabalho futuro.

Também vale a ressalva que já existem muitos estudos nesta temática (abaixo uma lista de alguns deles); portanto, é muito importante valer-se de análises e conclusões publicadas para enriquecer a qualidade de novos estudos.

Exemplos de estudos no assunto:

- "Um estudo do investimento público em educação básica no Brasil e do desempenho dos alunos em avaliações nacionais por Unidade Federativa no período de 1998 a 2007" (2009), por Fernando Gasparotto Puccinelli e Valmor Slomski;
- "Investimento público em educação básica e o desempenho dos alunos em avaliações nacionais: um estudo nos municípios pertencentes à associação dos municípios da encosta superior do nordeste do Rio Grande do Sul - Amesne - RS" (2014), por Nelton Carlos Conte e Sheila Donin;
- "Gasto público em educação e desempenho escolar" (2015), por Joana Monteiro;
- "Relação entre investimento em educação e índices educacionais para municípios gaúchos no período de 2005 a 2015" (2018), por Gabriela Drevnovicz Silveira et al.

Voltando ao Piauí e considerando as análises feitas até o momento, temos consolidada uma preocupação em particular sobre a educação pública deste estado. Um dos questionamentos que fizemos anteriormente foi:

**"Qual a expectativa sobre o futuro? Um aumento ou diminuição da disparidade do desempenho entre os ensinos públicos e privados?"**

Sabe-se que uma das maneiras de obter melhores condições socioeconômicas é com a educação. E o acesso ao ensino superior público e gratuito, que é o principal interesse dos candidatos que realizam o Enem, é crucial nesse processo. A primeira etapa é a fundamentação de uma sólida formação infantil, fundamental e média. **Mas outra etapa, de curtíssima duração, mas de extrema importância, é o acesso aos locais da prova nos dias do exame.**

Um indicador que podemos recorrer para levantar possíveis problemas nos diferentes estados e regiões é a taxa de abstenção dos candidatos. Sabe-se, também, que a realidade do transporte é significativamente diferente entre aqueles candidatos que possuem carro ou moto em suas residências e aqueles que não os possuem.

Primeiramente, vamos verificar este indicador para os candidatos que não possuem transporte próprio em suas residências. A figura a seguir mostra a taxa de abstenção de candidatos das capitais e das demais regiões, por estado, mas apenas dos que não possuem moto ou carro:

<p align="center">
<img src="img/taxa_abstencao_sem_moto_carro.png" alt="Drawing" style="width: 1500px"/>
</p>

Constatamos que **Piauí foi o estado com a menor taxa de abstenção média do Enem 2019 dentre os candidatos sem transporte próprio em suas residências**.

O DF não apresenta a taxa de abstenção além da capital pois não há outros municípios.

Vale a pena destacar ainda que, **dentre os dez estados com menores taxas de abstenção de candidatos que não possuem moto ou carro, existem sete estados que estão entre os dez mais desiguais em renda. São eles: PI, SE, BA, PE, PB, CE e RN**. Neste momento, levanta-se **uma hipótese que, em tais estados, o acesso ao ensino superior público e gratuito é visto como o grande potencial de alavancar socioeconomicamente e, assim, atenuar a desigualdade na renda da população**. Mas os detalhes da razão desta observação também podem ser investigados com maiores detalhes posteriormente. Temos, então, a segunda sugestão de um trabalho futuro.

A próxima figura apresenta a mesma informação; porém, para os candidatos que possuem algum meio de transporte em suas residências:

<p align="center">
<img src="img/taxa_abstencao_com_moto_carro.png" alt="Drawing" style="width: 1500px"/>
</p>

Desta vez, Sergipe foi o estado que apresentou a menor taxa de abstenção do Enem 2019 dentre os candidatos que possuem algum transporte próprio em suas residências.

Mas, no geral, considerando todos os candidatos, Piauí destaca-se quanto a este indicador há algum tempo, conforme a manchete a seguir do [G1](https://g1.globo.com/pi/piaui/noticia/2019/11/04/piaui-tem-maior-taxa-de-presenca-no-primeiro-dia-de-enem-pelo-4o-ano-consecutivo.ghtml):

<p align="center">
<img src="img/noticia_taxa_presenca.jpg" alt="Drawing" style="width: 450px;">
</p> 

# Conclusões

Diante do exposto, parece haver enorme vontade dos candidatos piauienses continuarem seus estudos no ensino superior público e gratuito, mas que, provavelmente, em decorrência da falta de investimento na educação pública, há um grande abismo entre os desempenhos e, consequentemente, entre as oportunidades alcançadas pelos candidatos oriundos de escolas públicas em relação àqueles de escolas particulares.

Este abismo pode ficar ainda maior se for ignorado pelo Estado.

Entretanto, este cenário da educação pública do Piauí não está, aparentemente, sendo desconsiderado, visto que a realidade nesse estado parece estar em plena transformação positiva. O último Ideb evidenciou enormes avanços, conforme consta na [notícia](https://www.pi.gov.br/noticias/piaui-e-destaque-no-ideb-2019-e-avanca-em-todas-as-etapas-de-ensino/) a seguir:

<p align="center">
<img src="img/noticia_educacao_PI.jpg" alt="Drawing" style="width: 650px;">
</p> 

Tal avanço na educação do Piauí ainda não foi refletido no Enem, conforme mostrado e explicado ao longo deste estudo; mas talvez seja apenas uma questão de tempo. Por ora, [a comemoração por tal feito no último Ideb](https://brasil.elpais.com/brasil/2020-09-20/interior-do-piaui-celebra-avanco-no-ideb-como-se-fosse-a-final-do-brasileirao-mas-impacto-da-pandemia-preocupa.html) é mais do que justa: há de se reconhecer o esforço da população do Piauí que, mesmo diante de obstáculos no caminho, conseguiu um significativo crescimento em qualidade da educação pública estadual:

<p align="center">
<img src="img/noticia_educacao_PI_2.jpg" alt="Drawing" style="width: 650px;">
</p> 

## Conteúdo extra e sugestões de trabalhos futuros
Conforme pôde ser notado, há uma grande diferença nas taxas de abstenção entre aqueles que possuem transporte (moto ou carro) em suas residências em comparação com aqueles que não possuem. Também notam-se diferenças, às vezes bastante consideráveis, entre os candidatos residentes nas capitais e os candidatos residentes nas demais regiões do estado.

As duas figuras seguintes trazem as mesmas análises apresentadas anteriormente, destacando-se a diferença da taxa de abstenção entre os candidatos que residem nas capitais e aqueles que habitam as demais regiões dos respectivos estados. Esta diferença é representada pelos números acima das colunas. Números marrons indicam abstenção maior na capital e números verdes apontam que a maior abstenção ocorreu nas demais cidades:

<p align="center">
<img src="img/taxa_abstencao_sem_moto_carro_compl.png" alt="Drawing" style="width: 1700px;">
</p>

<p align="center">
<img src="img/taxa_abstencao_com_moto_carro_compl.png" alt="Drawing" style="width: 1700px;">
</p> 

Nota-se que, **para os candidatos que não possuem moto ou carro em suas residências, não há indicação clara de que os habitantes nas capitais tendem a se abster mais em relação àqueles que moram em outras cidades do estado**. No entanto, não podemos deixar de notar que as três maiores diferenças de abstenções intraestaduais ocorreram em TO (Palmas), BA (Salvador) e MG (Belo Horizonte) cujas capitais superaram, respectivamente, em 6,77%, 4,48% e 3,41% as abstenções das demais cidades desses estados.

Por outro lado, para os candidatos que possuem moto ou carro em suas residências, as maiores taxas de abstenções por estado ocorreram nas cidades das demais regiões quase em sua totalidade; curiosamente, o Piauí é uma das poucas exceções.

**Uma hipótese para explicar tais resultados é que para os candidatos que não possuem meios de transporte em suas residências, a dificuldade em acessar os locais da prova, que já é maior por si só, podem ser semelhantes para locomoções intramunicipal ou intraestadual**; por isso que, embora estes candidatos apresentem as maiores taxas de abstenções, elas são equilibradas quanto à região predominante nos diferentes estados. **Enquanto para os candidatos que possuem meios de transporte em suas residências, a dificuldade, embora menor em comparação ao primeiro grupo, é maior se o local da prova é em outro município**. Como informação adicional, apenas pouco mais de 30% dos municípios brasileiros aplicaram o Enem em 2019.

A terceira sugestão para futuros estudos é investigar melhor estes números; pode-se dividir cada estado em diversas outras regiões e entender melhor os locais onde as abstenções são maiores. A seguir, pode-se estudar a razão pela qual existem regiões onde a abstenção é maior e, então, propor soluções para diminuí-las.

Uma quarta sugestão de trabalho futuro surgiu após a leitura da última notícia presente neste estudo. **Os avanços na educação do Piauí, evidenciados pelo avanço no último Ideb, podem ficar ameaçados pelas suspensões das aulas devido à pandemia e consequentes dificuldades do ensino à distância**. Segundo a reportagem, a maioria dos alunos da rede pública do Piauí não têm acesso à internet.

Sugere-se, então, investigar um conjunto de indicadores que podem apontar os estados cuja educação ficará mais prejudicada devido à suspensão das aulas; um deles é o próprio acesso à internet pelos estudantes. Mas podem existir outros ou, então, pode-se pensar em novos indicadores e trabalhar para obtê-los. A seguir, propor junto aos governos planos de recuperação da educação pública, ajustados especificamente para cada estado, de acordo com os impactos previstos e revelados pelos indicadores previamente obtidos e trabalhados.
