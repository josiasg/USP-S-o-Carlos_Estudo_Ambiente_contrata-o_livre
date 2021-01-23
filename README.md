# USP-Sao-Carlos_Estudo_Ambiente_contrataco_livre

Estudo de viabilidade de migração para o mercado livre de energia da Universidade de São Paulo – Campus São Carlos


IT304S - Contratação de Energia para Grandes Consumidores

Aluno: Getúlio Bernardes Cruz, R.A: 229012
Aluno: Josias Goncalves, RA: 228987
Aluno: Leslie Bastidas Cristobal, RA: 192817
Aluno: Marcos André Figueiredo valentim, RA: 233456
Professor: Dr. Luiz Carlos Pereira da Silva
Professor: MSc. Lia Farias

Esse repositório faz parte do projeto de estudo de migração do mercado cativo ao livre com base na UFCA. Além do repositório, o relatório completo pode ser encontrado no formato PDF no link https://drive.google.com/file/d/1JkrBhZuN5NFp3CdZ3O2Z6Hk2lqpT2g6Q/view?usp=sharing.

├── README.md          <- apresentação do projeto
│
├── data
│   ├── external       <- dados de terceiros
│   ├── interim        <- dados intermediários, e.g., resultado de transformação
│   ├── processed      <- dados finais usados para a modelagem
│   └── raw            <- dados originais sem modificações
│
├── notebooks          <- Jupyter notebooks ou equivalentes
│
├── src                <- fonte em linguagem de programação ou sistema (e.g., Orange)
│   └── README.md      <- instruções básicas de instalação/execução
│
└── assets             <- mídias usadas no projeto

data

Os dados utilizados no projeto foram repassados na disciplina de IT304S - Contratação de Energia para Grandes Consumidores contendo faturas de energia dda Universidade de São Paulo (USP)- Campus São Carlos. Todos os dados foram digitalizados no Excel e colocados na pasta da disciplina compartilhada no Google Drive no grupo 11, e posteriomente, foram adicionados no GitHub.

assets

Relatório Completo: https://drive.google.com/drive/u/1/folders/17rUhcJfJOEaZ22TzrJZw3hSSBoBg8A0L
Relatório de Pré-Análise: https://docs.google.com/document/d/1lp4p8SItCFEyUTl88i-3vQsC51VOuw8S/edit
Vídeo de apresentação do Projeto: https://youtu.be/Dw9jeHqWOx4

Projeto <Estudo de migração para o mercado livre de energia com base na USP Campus São Carlos>
Project <Migration study for the free energy market based at USP Campus São Carlos>

Descrição Resumida do Projeto

O setor elétrico brasileiro tem passado nos últimos anos por diversas mudanças, muito em razão do crescimento no número de fontes renováveis de energia. Atualmente, o setor se divide em dois segmentos, denominados Ambiente de Contratação Regulada e Ambiente de Contratação Livre. O Ambiente de Contratação Regulada representa a maior parte (70%) da energia comercializada no país, e inclui os consumidores de baixa tensão de energia, que são as residências, comércio em geral e empresas com consumo inferior a 500 kW, além dos clientes de alta tensão que não fizeram a migração para o mercado livre.
O ambiente de contratação livre apresenta uma série de  benefícios, pois é possível negociar o próprio contrato de energia com a entidade geradora. A entidade, ao migrar para o mercado livre, cria um ambiente competitivo, pois reduz os custos fixos com energia, gerando novos produtos e serviços, descentralizando as decisões e limitando poder de intervenção estatal.
Para se ter êxito na migração, é necessário analisar e avaliar minuciosamente os contratos a serem celebrados, bem como os fundamentos técnicos e perfil de consumo para migração, pois um contrato divergente da necessidade do cliente pode trazer prejuízos por longos anos. 
Desta forma, nesse trabalho o objetivo foi analisar a viabilidade da migração para o mercado livre da Universidade de São Paulo (USP) – Campus São carlos com uso de ferramentas analíticas que foram apresentadas na disciplina IT304S.

Abstract in English

The Brazilian electricity sector has undergone several changes in recent years, largely due to the growth in the number of renewable energy sources. Currently, the sector is divided into two segments, called the Regulated Contracting Environment and the Free Contracting Environment. The Regulated Contracting Environment represents the majority (70%) of the energy sold in the country, and includes low voltage consumers, which are homes, businesses in general and companies with consumption below 500 kW, in addition to customers of high voltage that did not migrate to the free market.
The free contracting environment presents a series of benefits, since it is possible to negotiate the energy contract itself with the generating entity. The entity, when migrating to the free market, creates a competitive environment, as it reduces fixed energy costs, generating new products and services, decentralizing decisions and limiting state intervention power.
In order to be successful in the migration, it is necessary to thoroughly analyze and evaluate the contracts to be signed, as well as the technical fundamentals and consumption profile for migration, as a contract that differs from the customer's needs can bring losses for long years.
Thus, in this work, the objective was to analyze the feasibility of migrating to the free market at the University of São Paulo (USP) - Campus São Carlos using analytical tools that were presented in the IT304S discipline.

Equipe

Aluno: Getúlio Bernardes Cruz, R.A: 229012
Aluno: Josias Goncalves, RA: 228987
Aluno: Leslie Bastidas Cristobal, RA: 192817
Aluno: Marcos André Figueiredo valentim, RA: 233456

Vídeo do Projeto

https://youtu.be/Dw9jeHqWOx4

Introdução e Motivação

O setor elétrico brasileiro tem passado nos últimos anos por diversas mudanças, muito em razão do crescimento no número de fontes renováveis de energia. Atualmente, o setor se divide em dois segmentos, denominados Ambiente de Contratação Regulada e Ambiente de Contratação Livre. O Ambiente de Contratação Regulada representa a maior parte (70%) da energia comercializada no país, e inclui os consumidores de baixa tensão de energia, que são as residências, comércio em geral e empresas com consumo inferior a 500 kW, além dos clientes de alta tensão que não fizeram a migração para o mercado livre.
O ambiente de contratação livre apresenta uma série de  benefícios, pois é possível negociar o próprio contrato de energia com a entidade geradora. A entidade, ao migrar para o mercado livre, cria um ambiente competitivo, pois reduz os custos fixos com energia, gerando novos produtos e serviços, descentralizando as decisões e limitando poder de intervenção estatal.
Para se ter êxito na migração, é necessário analisar e avaliar minuciosamente os contratos a serem celebrados, bem como os fundamentos técnicos e perfil de consumo para migração, pois um contrato divergente da necessidade do cliente pode trazer prejuízos por longos anos. 
Desta forma, nesse trabalho o objetivo foi analisar a viabilidade da migração para o mercado livre da Universidade de São Paulo (USP) – Campus São carlos com uso de ferramentas analíticas que foram apresentadas na disciplina IT304S.


Perguntas de Pesquisa

Vale a pena migrar para o Mercado Livre? 
Como consumidor livre ou especial? 
Qual é a economia estimada? 
Qual é o preço da energia a partir de quando compensa a migração? 
Qual a recomendação para uma contratação?

Recursos e Métodos

A base de dados utilizada foram as faturas de energia das USP São carlos, repassadas na disciplina de IT304S - Contratação de Energia para Grandes Consumidores, digitalizadas no Excel e também em PDF e disponibilizado no Google Drive do curso.

Ferramentas

Uso do Excel para compilar os dados. 
Uso do Word para redigir os relatórios e pareceres.

Metodologia

O primeiro passo para estudo de migração ao mercado livre foi realizado no primeiro relatório da disciplina IT304S - Contratação de Energia para Grandes Consumidores, em que foi analisado as contas da USP, observando aspectos como uso da demanda e valores de reativos. Foram observados o comportamento dos dados e, Pode-se dizer a metodologia utilizou-se de pesquisas qualitativas e quantitativas.
Nesse relatório, é apontado a viabilidade de migração do mercado cativo ao mercado livre da USP. Assim, a primeira parte do presente relatório tratou de estudar o mercado livre, verificando as possibilidades de migração para uma universidade pública como a USP, baseado no perfil traçado anteriormente no primeiro relatório.
Foi realizada análise de perfil de consumo de energia ao longo dos últimos 4 anos com uma análise simples das faturas para modelar o tipo de consumidor, flexibilidade e a demanda a ser contratada. Depois com ajuda de projeções  sobre o custo da energia elétrica nos próximos anos projetamos a redução de custos possíveis de ser feita a migração.

Detalhamento do Projeto

Os detalhes completos do projeto podem ser obtidos através do link disponibilizado na seção assets.

Descrição da Universidade escolhida

A implantação da USP em São Carlos começa no ano de 1948, com a criação da Escola de Engenharia de São Carlos (EESC). Efetivamente, as atividades tiveram início cinco anos depois, com a primeira aula proferida no dia 18 de abril de 1953, no prédio que hoje abriga o Centro de Divulgação Científica e Cultural (CDCC), no centro da cidade.
Não demorou muito e a sede da Escola ficou pequena. Assim, em 1956, a unidade foi transferida para uma área bem maior, onde se constituiu o campus universitário. No novo espaço, as atividades da Escola de Engenharia vão se multiplicando e, como resultado de um transbordamento, o Campus passa a contar com outras unidades de ensino.
	Com o crescimento de sua estrutura ao longo dos anos, o campus universitário também ficou limitado. Em virtude disso, em 2001, teve início o processo de expansão para uma segunda área. Popularmente chamado de Campus 2 e com mais de 100 hectares, o local foi oficialmente inaugurado em 4 de novembro de 2005, ano em que passou a incorporar as atividades acadêmicas da Universidade na cidade.	A USP possui atualmente cerca de 8,5 Mil alunos matriculados nos cursos de graduação e pós graduação
Figura 1 - Universidade de São Paulo (USP) - Campus São Carlos
  
  
Fonte: Portal da USP

Abaixo, a quantidade de alunos prevista para os proximos anos. O crescimento se deve em razao da abertura de novos cursos ofertados no campus.
Figura 2 - Evolução da quantidade de alunos no campus
 
Fonte: Anuario estatístico da USP

Mercado Livre
Definições e Regras

No Mercado Livre de Energia, você escolhe o seu fornecedor de energia elétrica e tem liberdade para negociar preços, quantidades, fontes de energia, condições comerciais para economizar mais e ter previsibilidade de custos. Contamos com uma equipe de especialistas pronta para ajudar você a migrar para este modelo com segurança e eficiência.
Segundo a Associação Brasileira dos Comercializadores de Energia (ABRACEEL), o Mercado Livre de energia elétrica, ou Ambiente de Contratação Livre (ACL), é um ambiente no qual os consumidores podem escolher seus fornecedores de energia. Nesse ambiente de contratação, os consumidores e fornecedores negociam entre si as condições de contratação de energia.
Embora a nomenclatura “livre” possua a conotação de liberdade, nem todos as uni- dades consumidoras possuam a permissão para adentrar neste ambiente de contratação energética. Mediante a este fato, tem-se a principal diferença em relação ao seu antago- nista, o Ambiente de Contratação regulado (ACR).
No ACL, os clientes devem se enquadrar em um das duas possibilidades:
1.	Demanda contratada, ou MUSD (Montante de Uso do Sistema de Distribuição) no intervalo de 500kW a 2MW e atendimento em média ou alta tensão. Este tipo  de cliente é denominado de "Cliente Especial", possuindo certas limitações ao mercado livre, bem como a restrição à contratação de energia incetivada (PCHs, eólica, solar e biomassa);
2.	Demanda contratada superior a 2MW, com atendimento a qualquer nível de tensão. Para esta qualificação de unidade consumidora, o cliente é denominado de "Con- sumidor Livre", não possuindo restrições à fonte de energia contratada e também ao que tange a tensão de alimentação.
Mediante a estes fatores condicionais para participação do mercado livre, a Universi- dade de São Paulo – Campus São Carlos possui demanda contratada de 1.250 kW, está apta a participar deste ambiente livre de contratação energética como um cliente especial.
O Ambiente de Contratação Livre permite que a unidade consumidora possua um grau maior de liberdade para selecionar o seu fornecedor energético em relação aos clientes cativos, os quais estão engessados às tarifas impostas pelas concessionárias locais, o que reflete em uma maior previsibilidade de gastos financeiros com o consumo energético. Todavia, como todo procedimento que envolve a redução de custos na esfera de consumo energético, faz-se necessário aplicar técnicas envolvendo as análises de eficiência energética, buscando essencialmente a carga instalada.
Neste contexto, estudos a respeito dos setores, sobretudo,  de eficientização no uso da energia, como projetos de iluminação, refrigeração, sistemas motrizes eficientes devem ser realizados afim de reduzir os potenciais gastos excedentes de energia, viabilizando atividades de substituição de lâmpadas, sistemas de ar condicionado de maior eficiência energética. Faz-se necessário, inclusive, realizar uma análise do consumo excessivo de potência reativa, especialmente advinda de motores, o qual pode resultar em multas que incidam diretamente na viabilidade da transição do mercado cativo para o ambiente de contratação livre. 
Realizadas estas análises associadas a uma contratação de demanda energética capaz de suprir todas as necessidades das unidades consumidoras, faz-se necessário analisar se ainda há possibilidade de desenvolver projetos de geração distribuída enquadradas no âmbito de minigeração, onde demandas contratadas de até 5MW possam adentrar ao modelo de negócio.
Neste âmbito, faz-se necessário apresentar os órgãos competentes e responsáveis por regular o setor elétrico e, sobretudo, o mercado livre. A hierarquia do sistema elétrico é apresentada na figura 3, desenvolvida pelo professor Pedro Dante em seus slides de apresentação da disciplina de IT304 no segundo semestre do ano de 2020.
 

Figura 3 - Hierarquia dos órgãos de regulação do setor energético
 Fonte: IT304S – Aula 04

Conforme a hierarquia supracitada, existem diversos órgãos que regulamentam o setor energético brasileiro, entretanto, o escopo deste projeto exige um cuidado maior a respeito de dois destes órgãos, a Câmara de Comercialização de Energia Elétrica (CCEE), além do Operador Nacional do Sistema Elétrico (ONS).
A CCEE atua sobre o mercado brasileiro de energia elétrica, viabilizando um ambi- ente de negociação competitivo e seguro. Este órgão promove também discussões para desenvolver solução para o setor elétrico nacional. No âmbito operacional, a CCEE é res- ponsável por contabilizar as operações de compra e venda de energia elétrica, apurando mensalmente as diferenças entre os montantes contratados e os montantes gerados ou consumidos pelos agentes do mercado.
A CCEE também é responsável por determinar os débitos e créditos destes agentes, baseando-se nas diferenças apuradas, realizando a liquidação financeira das operações. Para valorar tais diferenças, o órgão calcula o Preço de Liquidação de Diferenças.

faz algo trivial, tal qual a adesão ao mercado cativo. Devido a esta conjuntura, o cliente deve estar plenamente seguro de que está fazendo uma decisão correta. Vale ressalta que, uma vez realizada a migração ao ACL, o cliente só poderá retornar ao mercado cativo mediante a um aviso prévio de 5 anos à distribuidora local.
Pelo fato de existir uma quantidade maior de possíveis distribuidores de energia neste modelo de negócio, o ambiente de contratação livre possui um valor por MWh mais atrativo do que o ambiente cativo. Aliado a este fator, o fato da unidade consumidora não ser contratualmente abastecida pela distribuidora implica na não suscetibilidade às variações das bandeiras tarifárias, responsáveis por criar flutuações nas tarifas energéticas. A consequência desta volatilidade pode ser traduzida em uma quantidade superior de outliers em uma previsão de consumo, trazendo incertezas para grandes consumidores.

Etapas para migração para o mercado livre
Após decidir migrar a unidade ao Mercado Livre, o consumidor deverá informar à distribuidora a intenção de não renovação do contrato de Compra de energia elétrica com antecedência mínima de 180 dias com relação ao fim da vigência contratual. Para tanto, deverá submeter Carta denúncia no Formulário de solicitação de Migração ao ACL, informando data de migração e CNPJ da unidade a migrar (Matriz e Filial, se existir) acompanhado por procuração, se necessário.
É interessante que o cliente já tenha fornecedor de energia contratado para a comercialização de energia elétrica no momento da denúncia.
Para os casos em que o consumidor não tenha a demanda mínima exigida para migrar, e optar por realizar aumento de demanda, este processo deverá estar concluído até a data de migração. Atrasos no processo de aumento de demanda podem implicar em não validação da migração pela distribuidora, impactando em atraso no processo.
O consumidor deverá, após resposta formal da distribuidora (carta resposta), encaminhar todos os documentos necessários para a efetivação do processo, que serão enviados pela distribuidora junto com a carta resposta, a saber:
1.	Termo de Pactuação; 
2.	Contrato de Uso do Sistema de Distribuição (CUSD) no Mercado Livre;
3.	Distrato do Contrato de Compra de Energia Regulada (CCER);
4.	Comprovante de pagamento do boleto de adequação e da multa por rescisão, se cabível;
5.	O não recebimento das vias físicas assinadas em um prazo máximo de 30 dias implicará em cancelamento do processo.
O consumidor deverá enviar o diagrama unifilar em formato .DWG (versão até 2008) da unidade consumidora. Caso a unidade esteja alocada no interior de um shopping, faz-se necessário o envio também do unifilar do shopping indicando cada loja âncora.
Com as alterações promovidas em 2017 pela Resolução Normativa nº 759 - REN 759, que revisou as regras do sistema de medição, as migrações de unidades com medições no secundário do transformador foram viabilizadas. Desta forma, para as unidades com medição no lado de baixa tensão do transformador, além do diagrama unifilar, deverá ser enviado também:
1.	Ensaios do Transformador em conformidade com a NBR 5356, contendo obrigatoriamente:
a.	Resistência dos enrolamentos;
b.	Relação de transformação;
c.	Impedância de curto-circuito e perdas em carga;
d.	Corrente de excitação e perdas em vazio;
e.	 Resistência de isolamento.
Conforme art. 18 da resolução ANEEL nº 281 de 01 de outubro de 1999, em se tratando de unidade consumidora, a concessionária de distribuição local é responsável pela instalação do presente sistema de medição de faturamento, cabendo ao consumidor a responsabilidade financeira quanto aos serviços executados. Não obstante, o ressarcimento integral pela instalação do sistema de medição, conforme art. 8º da resolução ANEEL nº 264, de 13 de agosto de 1998, os equipamentos constituintes do sistema de medição de faturamento são de propriedade da concessionária de distribuição local, a qual se responsabilizará pela sua manutenção e operação. O prazo para adequação do SMF é de até 120 (cento e vinte) dias, contados a partir da quitação do boleto.
O consumidor é responsável pela subestação da unidade, ao qual deverá estar regular com a distribuidora. Adequações na subestação são de responsabilidade do cliente, as quais deverão ser realizadas em tempo hábil para permitir a adequação do sistema de medição e não impactar em atrasos na migração. Também, deverá ser considerado a Norma técnica vigente em caso de modificações na subestação.

Figura 4 - Fluxograma do processo de migração para o mercado livre
 Fonte: CCEE
Legenda:
Azul: responsabilidade do consumidor
Vermelho: responsabilidade da concessionária
Amarelo: responsabilidade da CCEE 

Parecer Jurídico
Uma das questões para migração ao mercado livre de qualquer órgão público, como as universidades públicas é a jurídica. A dúvida geralmente é sobre a possibilidade em fazer a migração, já que é um serviço público. Uma discussão jurídica para uma autarquia estatal é realizada em [5].
As universidades são autarquias estatais, que exigem os princípios da administração pública, conforme o art. 37 da Constituição Federal [5; 10]. Ou seja, existem regras e diretrizes a serem seguidas e estas devem ser observadas para evitar sanções aos gestores. Um dos fatores que levantam a dúvida sobre a possibilidade da migração e criam obstáculos é o fato do mercado livre envolver entes privados e de livre negociação. Na literatura alguns obstáculos podem ser levantados para autarquia estatal como por exemplo: processo licitatório; abertura de conta pela autarquia em instituição financeira bancária privada e; necessidade do ente público em conceder garantias aos fornecedores de energia elétrica e à Câmara de Comercialização de Energia Elétrica (CCEE) [5].
Para a questão licitatória, os autores em [5], destacaram que a Lei de Licitações, Lei nº8.666/1993, em seu artigo 24, inciso XXII, resolve essa questão ao relatar que dispensa o processo licitatório “na contratação de fornecimento ou suprimento de energia elétrica [...]” [11].
A questão do banco pode ser resolvida pelo simples fato de que outros bancos não realizam tal atividade, sendo necessário e a única opção abrir a conta no Bradesco para conseguir realizar a migração para o mercado livre [5].
Quanto a garantia aos fornecedores, também não se observa problemas, pois a mo- dalidade de garantia é diferente da modalidade estabelecida na Lei de Responsabilidade Fiscal que impediria a migração [5]. Logo, no aspecto jurídico, é possível a migração de energia para o mercado livre de uma universidade, desde que seja obedecido os critérios da CCEE e a migração tenha fundamento técnico.
Realizar o trâmite de migração de mercado regulado (ACR) para mercado Livre (ACL) traz muitos benefícios, alguns deles refletidos na economia do consumidor, ao longo desta seção apresentaremos os mais importantes tais como a redução nos custos, a liberdade de negociação e a previsão.

Redução dos custos

No Brasil atualmente existem mais de 386 comercializadoras de energia elétrica e 8475 consumidores livres até o final de novembro, o que faz com que o preço da energia elétrica seja muito menor do que no mercado cativo. Além disso, os participantes na conformação do preço tais como a tarifa fio, podem ser reduzidos o que permite às comercializadoras e geradoras oferecer um preço mais competitivo para os consumidores livres. Na Figura 1 observamos a projeção de economia total dos consumidores livres feita pela ABRACEEL. Já na Figura 2 observamos a economia obtida por ano e a economia acumulada da Empresa Estatal Sabesp desde sua migração ao ACL.
Figura 5 - Projeção de economia total dos consumidores livres
 
Fonte: Site da ABRACEEL

Figura 6 - Economia por ano e acumulada da Sabesp
  
Fonte: Apresentação da Sabesp no Congresso Brasileiro de Eficiência Energética 2019

Previsão de custos

Outra vantagem do ACL é a compra de energia a um preço de longo prazo e assim não estar mais ligado às variações do mercado de curto prazo ou PLD. Pois só no último ano, o preço da energia no ACL teve uma variação em torno de 1.7% em comparação à variação do PLD em torno de 22%. Na figura 3 observamos a variação do PLD ao longo de 2019.
Figura 7 - Variação do PLD x Variação do preço no ACL ao longo do 2019
 
Fonte: Relatório Anual da ABRACEEL

Livre negociação

Um das principais vantagens do ACL é a possibilidade da negociação mediante um contrato onde podem ser definidas além do custo da energia, o montante de energia, a demanda requerida, a sazonalidade e flexibilidade, a modulação e a duração do contrato. Existem inúmeros tipos de contratos, mas na Figura 4 mostramos o contrato bilateral mais utilizado que permite a sazonalidade e estabelece um porcentagem de flexibilidade determinado entre o consumidor e a comercializadora. Também na Figura 5 mostramos o contrato derivativo tipo colar onde o consumidor é exposto ao mercado de curto prazo pagando um custo um pouco mais elevado que o PLD com a condição de ter um preço mínimo e um preço máximo. 

Figura 8 - Contrato Bilateral Sazonalizado
 
Fonte: Site Mercado de Energia Livre/Contratos
 
Figura 9 - Contrato derivativo tipo Colar
 
Fonte: Dissertação de Mestrado Gustavo Arfux


 
Análise de viabilidade

O gráfico abaixo representa o histograma de demanda registrada da USP São Carlos. Percebe-se variações máximas de 31% acima da demanda contratada (penalização por ultrapassagem de demanda) e mínima de 26,2% abaixo do contrato da universidade (1.638 kW e 922 kW, respectivamente).
	O ano de 2020 foi atípico, em razão da pandemia do COVID-19 e fechamento da unidade para aulas presenciais, o uso da demanda foi muito abaixo do patamar histórico do cliente. Em valores reais da demanda, publicados pela Resolução Aneel número 2.670 de 07 de abril de 2020 para a CPFL Paulista, a perda financeira acumulada no periodo da pandemia em relação à demanda é de R$ 66,3 Mil (diferença entre a demanda lida e o contrato).

Figura 10 - Histórico de demanda lida
 
Fonte: IT304S: faturas do cliente

Para a simulação da viabilidade, foi considerada a projeção do PLD disponibilizada pela CCEE. Com base nessas informações, foi calculada a diferença em R$ Mil entre o mercado regulado (ACR) e mercado livre (ACL).
Foi considerada a tarifa vigente homologada pela Aneel para a distribuidora CPFL Paulista (Resolução Homologatória nº 2.670).

Figura 11 - Projeção do PLD
 Fonte: CCEE


No gráfico abaixo, a curva azul representa os valores em R$ Mil do cliente no ambiente regulado enquanto a curva laranja representa os valores em R$ Mil do cliente em mercado ACL. Os ganhos somente com diferença tarifária no consumo de energia representam cerca de R$ 265 Mil/ano com a migração para o mercado livre (considera como referência de cálculo o ano de 2019, para expurgar fatores exógenos).


Figura 12 - Análise financeira ACR x ACL
 
Fonte: IT304S: faturas do cliente
 
Considerações Finais

O presente trabalho teve como objetivo avaliar a possível migração do mercado cativo (atual) para o mercado livre (proposto) da Universidade de São Paulo (USP) Campus São Carlos. Os estudos e análises possibilitaram o entendimento quanto ao perfil de consumo do cliente, os ciclos sazonais que esse tipo de cliente possui,  pontos que devem ser considerados  no  processo de migração ao mercado livre. Notou-se o quanto é importante possuir opções quanto à gestão da energia, como mercado livre, eficientização da planra,  pois isso possibilita melhor contratação e comercialização de energia entre a entidade geradora e consumidores, porporcionando reduções de custos e possuir governança quanto ao uso da energia elétrica. 
Além disso, foi necessário aprofundar os conhecimentos em ferramentas novas disponíveis que foram úteis e assertivas para entendimento, análises  para integrantes do grupo, como GitHub, etc. demanda otimizada, o valor de economia é reduzido, pois a fatura no cativo utilizada na comparação também é reduzida. Logo, ajustar a demanda seria interessante para uma fatura menor no cativo ou livre. 

Referências

Mercado Livre de energia. ABRACEEL. Disponível em: 
<https://abraceel.com.br/mercado-livre/>.
Formação de preços do PLD. CCEE. Disponível em: <https://www.ccee.org.br/portal/faces/pages_publico/o-que-fazemos/como_ccee_atua/precos/metodologia_de_precos?_afrLoop=128636582645312&_adf.ctrl-state=iqf15puvi_2#!%40%40%3F_afrLoop%3D128636582645312%26_adf.ctrl-state%3Diqf15puvi_6>.
Migração para Mercado Livre de energia. EDP. Disponível em: <https://www.edp.com.br/distribuicao-es/saiba-mais/informativos/migracao-mercado-livre-energia>.
J. K. F. de Lima, “Um estudo sobre a instabilidade causada no ambiente de livre contratação de energia elétrica devido a erros no processo de formação do preço de liquidação das diferenças,” 2019, universidade Federal do Ceará, Trabalho de conclusão de curso em Engenharia Elétrica, Fortaleza, Brasil.
Abraceel,	“Benefícios,	riscos	e		desafios	na		transi- ção	para		um	mercado		livre,”		2021.	[Online].	Available: https://www.aneel.gov.br/documents/656877/17755237/Reginaldo+Medeiros.pdf/ 529c0dc1-4537-2e7c-8d75-273ebfc37fa3
F. M. Lourençato, S. C. Campos, A. M. A. de Castro, J. R. de Castro Barbosa do Amaral, N. F. Rossi,  A. P.  Araki,  F. R. F. S. de Paula,  A. P.  Filho,  L. de Fa- ria Rodrigues, and M. S. F. do Amaral Fregonesi, “Estudo de caso da migração de compra de energia elétrica do mercado cativo para o mercado de energia livre por uma autarquia,” Revista Qualidade HC, pp. 1–13, 2018.
R. E. M. da Costa, “Análise e simulação da migração de uma empresa do mercado cativo para o mercado livre de energia elétrica,” 2019, universidade Federal De Uber- lândia, Trabalho de conclusão de curso em Engenharia Elétrica, Uberlândia, Brasil.
K. R. do Nascimento, “Migração para o mercado livre de energia e alteração de tarifa horária: estudo de caso em uma indústria,” 2018, universidade Federal do Rio de Janeiro, Trabalho de conclusão de curso em Engenharia, Rio de Janeiro, Brasil.
B. A. A. Acurio, D. E. C. Barragán, E. Y. Sakô, J. L. de Souza Silva,
M.  A.  L.  Ferreira,  and  B.  F.  Albuquerque,  “Github  do   estudo   de   migração para o mercado livre da ufca,” 2021. [Online]. Available: https://github.com/byronacunia/UFCA_estudo_mercado_livre
I. Gabriel, M. Fernandes, and S. G. Sanches, “Planejamento estratégico: análise swot,”  
“Lei   n º  8.666,	de 21  de  junho  de  1993,”	2021. [Online]. Available: http://www.planalto.gov.br/ccivil_03/LEIS/L8666cons.htm
[12]R. E. M. da Costa, “Sistemas de medição para faturamento e o mercado de energia elétrica: uma visão crítica do referencial regulatório,” 2009, universidade de São Paulo, Mestre em Engenharia Elétrica, São Paulo, Brasil.
