## <img src="/Images/Icons/reuse.png" width="200" height="200" /> <img src="/Images/Icons/research.png" width="200" height="200" />

## 4. Investigação reprodutível e análise de dados

### O que é?

Reprodutibilidade significa que os dados da investigação e o código são disponibilizados de forma a que outros possam atingir os mesmos resultados que são declarados em resultados científicos (como as publicações).  Estreitamente relacionado está o conceito de replicabilidade, o ato de repetir uma metodologia científica para atingir conclusões semelhantes. Estes conceitos são elementos chave da investigação empírica.

Melhorar a reprodutibilidade leva a um maior rigor e qualidade dos resultados científicos e, portanto, a uma maior confiança na ciência. Tem havido uma crescente necessidade e vontade de expor os fluxos de trabalho de investigação desde o início de um projeto e recolha de dados até à interpretação e relato de resultados. Esses desenvolvimentos acarretam um conjunto de desafios, incluindo a criação de fluxos de trabalho de investigação integrados que podem ser adotados pelos colaboradores, mantendo altos padrões de integridade.

O conceito de reprodutibilidade é diretamente aplicado ao método científico, a pedra angular da Ciência, e particularmente aos 5 passos seguintes:

1. Formular a hipótese

2. Desenhar o estudo

3. Executar o estudo e recolher os dados

4. Analisar os dados

5. Relatar o estudo

Cada um destes passos deve ser relatado de forma clara, fornecendo documentação clara e aberta, tornando o estudo transparente e reprodutível.

![](/Images/02%20Open%20Science%20Basics/02_reproducible_research_data_analysis.png)

### Fundamentação

Fatores de caráter geral e dominante podem contribuir ainda mais para as causas da não-reprodutibilidade, mas também podem impulsionar a implementação de medidas específicas para lidar com essas causas. A cultura e o ambiente em que a investigação tem lugar são importantes fatores dominantes _top-down_. De uma perspetiva _bottom-up_, a educação e formação permanente dos investigadores pode aumentar a conscientização e disseminar boas práticas.

Embora a compreensão de todos os fatores que contribuem para a reprodutibilidade seja importante, também pode ser difícil decompor esses fatores em etapas que possam ser imediatamente adotadas por um programa de investigação existente e melhorar imediatamente a sua reprodutibilidade. Um dos primeiros passos a dar é avaliar a situação atual  e acompanhar a melhoria  à medida que são dados passos para aumentar ainda mais a reprodutibilidade. Alguns dos problemas comuns com a reprodutibilidade da investigação são mostrados na figura seguinte.

![](/Images/image_2.png)

Fonte: [Reproducibility and reliability of biomedical research: improving research practice](https://acmedsci.ac.uk/viewFile/56314e40aac61.pdf).

Goodman, Fanelli, & Ioannidis \(2016\) notam que na epidemiologia, biologia computacional, economia e testes clínicos, a reprodutibilidade é frequentemente definida como:

_the ability of a researcher to duplicate the results of a prior study using the same materials as were used by the original investigator. That is, a second researcher might use the same raw data to build the same analysis files and implement the same statistical analysis in an attempt to yield the same results._

Isto é distinto de replicabilidade:

_which refers to the ability of a researcher to duplicate the results of a prior study if the same procedures are followed but new data are collected._

Uma forma simples de pensar sobre isto pode ser que a reprodutibilidade é orientada aos métodos, enquanto a replicabilidade é orientada aos resultados. 

A reprodutibilidade pode ser avaliada a diferentes níveis: ao nível de um projeto individual  \(ex., um artigo, uma experiência, um método ou um conjunto de dados\), um investigador individual, um laboratório ou grupo de investigação, uma instituição, ou mesmo uma área de investigação. Critérios e pontos de avaliação ligeiramente diferentes podem aplicar-se a esses diferentes níveis. Por exemplo, uma instituição defende as práticas de reprodutibilidade se instituir políticas que recompensem os investigadores que realizem investigação reprodutível. Por outro lado, um campo de investigação pode ser considerado como tendo um nível mais elevado de reprodutibilidade se desenvolver recursos mantidos pela comunidade que promovam e permitam práticas de pesquisa reproduzíveis, como repositórios de dados ou normativas para partilha de dados. 

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Objectivos de aprendizagem

Existem três objetivos principais que têm que abordados aqui:

1. Compreender o importante impacto de criar investigação reprodutível. 

2. Compreender a configuração geral da investigação reprodutível \(incluindo o desenho de fluxos de trabalho, gestão de dados e relatório dinâmico\).

3. Estar consciente dos passos individuais no processo de reprodutibilidade, bem como os respetivos recursos que podem ser utilizados.

### Componentes-chave

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Conhecimento

Segue-se uma lista indicativa de ideias a reter sobre reprodutibilidade:

* O que é a "crise de reprodutibilidade" e as meta-análises de reprodutibilidade.

* Princípios de reprodutibilidade, integridade e ética na investigação.

* Quais são as opções e ambientes de computação que permitem um meio colaborativo e reprodutível.

* Fatores que afetam a reprodutibilidade da investigação.

* Documentação de análise de dados e fluxos de trabalho de investigação aberta.

* Ambientes de análise reprodutíveis \(virtualização\).

* Abordar os "Researcher Degrees of Freedom" \(Wicherts et al., 2016\).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Competências

Existem várias dicas práticas para a reprodutibilidade que devemos ter em conta quando definimos as competências específicas necessárias para a garantir.  As boas práticas em reprodutibilidade utilizam as práticas da Ciência Aberta no geral, mas a sua integração oferece benefícios ao investigador individual, quer escolha partilhar a sua investigação ou não. A razão pela qual integrar as boas práticas da reprodutibilidade beneficia o investigador individual é porque estas melhoram o planeamento, a organização e a documentação da investigação.  Em baixo descrevemos um exemplo de implementação de reprodutibilidade num fluxo de trabalho de investigação com referências a estas práticas no manual.

## <img src="/Images/Icons/task.png" width="150" height="150" />
##### **1. Planeie a reprodutibilidade antes de começar**

###### Crie um plano de estudo ou protocolo.

Comece a documentar no início do estudo escrevendo um plano de estudo ou protocolo que inclua o desenho e métodos do estudo proposto. Use um guia de relatório do [Equator Network](http://www.equator-network.org/) se aplicável. Registe as alterações ao plano de estudo ou protocolo usando um versão de controlo \(referência a Controlo de Versões\). Calcule o alcance ou tamanho da amostra necessária e relate este cálculo no seu protocolo, pois estudos com pouco alcance são propensos à irreprodutibilidade.

###### Escolha ferramentas e materiais reprodutíveis

Escolha anticorpos que funcionem usando um motor de pesquisa de anticorpos como [CiteAb](https://www.citeab.com/). Evite a irreprodutibilidade através de linhas celulares mal identificadas escolhendo as que estão autenticadas pela [International Cell Line Authentication Committee](http://iclac.org/). Sempre que possível, escolha ferramentas de software e hardware nas quais retenha a propriedade da sua investigação e que permitam a exportação da sua investigação para fora da plataforma para sua reutilização - veja [Software Aberto Usado na Investigação e Software de Código Aberto](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_PT/blob/master/02IntroducaoaCienciaAberta/03Software_Aberto_Usado_na%20Investigacao_e_Software_de_Codigo_Aberto.md).

###### Estabeleça um projeto reprodutível

Centralize e organize a gestão do seu projeto usando um plataforma online, um repositório central, ou pasta para todos os ficheiros da investigação. Pode usar o GitHub como local para armazenar todos os ficheiros do projeto ou gerir tudo usando um _notebook_ como [Benchling](https://benchling.com/), [Labguru](https://www.labguru.com/),ou [SciNote](https://scinote.net/). Dentro do projeto centralizado, siga as boas práticas separando os seus dados do código em pastas diferentes. Torne os seus dados não tratados como apenas de leitura e mantenha-os separados dos dados processados - veja  [Dados e Materiais de Investigacao Abertos](/02IntroducaoaCienciaAberta/02Dados_e_Materiais_de_Investigacao_Abertos.md).

Ao gravar e arquivar os seus ficheiros de investigação, use formatos e nomes de ficheiros informativos que permitam a reutilização. Os nomes dos ficheiros devem ser legíveis para máquinas e humanos. \(referência a Gestão de Dados\). Na sua análise e código de software use caminhos relativos. Evite formatos de ficheiros proprietários e use formatos de ficheiro abertos - veja [Licenciamento Aberto e Formato de Ficheiros](/02IntroducaoaCienciaAberta/06Licenciamento_Aberto_e_Formatos_de_Ficheiros.md).

## <img src="/Images/Icons/handson.png" width="150" height="150" />
##### **2. Mantenha um registo**

###### Registo

Faça um pré-registo de informação importante do desenho e análise do estudo para aumentar a transparência e combater o viés da publicação de resultados negativos. Ferramentas gratuitas que podem ajudar a fazer o primeiro registo incluem [AsPredicted](https://aspredicted.org/), [Open Science Framework](https://osf.io/), e [Registered Reports](https://cos.io/rr/). Estudos clínicos devem usar [Clinicaltrials.gov](https://clinicaltrials.gov/).

###### Controlo de versões

Registe as alterações aos seus ficheiros, especialmente o código de análise, usando um controlo de versões veja [Software Aberto Usado na Investigação e Software de Código Aberto](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_PT/blob/master/02IntroducaoaCienciaAberta/03Software_Aberto_Usado_na%20Investigacao_e_Software_de_Codigo_Aberto.md).

###### Documentação

Documente tudo o que foi feito, manualmente, num ficheiro README. Crie um dicionário de dados \(também conhecido como livro de código\)para descrever informação importante sobre os seus dados. Para uma introdução simples, use: [Karl Broman’s Data Organization module](http://kbroman.org/dataorg/pages/dictionary.html) e consulte [Dados e Materiais de Investigacao Abertos](/02IntroducaoaCienciaAberta/02Dados_e_Materiais_de_Investigacao_Abertos.md).

###### Programação documentada

Considere usar [Jupyter Notebooks](http://jupyter.org/), [KnitR](https://yihui.name/knitr/), [Sweave](https://support.rstudio.com/hc/en-us/articles/200552056-Using-Sweave-and-knitr), ou outras abordagens de programação documentada para integrar o seu código com a sua narrativa e documentação.

## <img src="/Images/Icons/open_licenses.png" width="150" height="150" />
##### **3. Partilhe e licencie a sua investigação**

###### Dados

Evite ficheiros suplementares, decida por um licença permissiva aceitável, e partilhe os seus dados usando um repositório. Siga as boas práticas descritas no capítulo [Dados e Materiais de Investigacao Abertos](/02IntroducaoaCienciaAberta/02Dados_e_Materiais_de_Investigacao_Abertos.md).

###### Materiais

Partilhe os seus materiais de forma a que possam ser reutilizados. Deposite os  reagentes em repositórios como [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/), e [ATCC](https://www.atcc.org/) para os tornar facilmente acessíveis a outros investigadores. Para mais informação, veja a subsecção Materiais Abertos do capítulo Dados e Materiais de Investigação Abertos.

###### Software, _notebooks_, e contentores

Licencie o seu código para informar como este pode ser \(re\)utilizado. Partilhe os _notebooks_ com serviços como [mybinder](http://mybinder.org) que permitam a visualização pública e execução de todo o _notebook_ em recursos partilhados. Partilhe os contentores ou _notebooks_ com serviços como [Rocker](https://arxiv.org/abs/1710.03675) ou [Code Ocean](https://codeocean.com/). Siga as boas práticas descritas em Software aberto usado em investigação e Software de código aberto.

## <img src="/Images/Icons/open_scholarship.png" width="150" height="150" />
##### **4. Reporte a sua investigação de forma transparente**

Reporte e publique os seus métodos e intervenções de forma explícita e transparente e completa para permitir sua replicação. As directrizes de [Equator Network](http://www.equator-network.org/), ferramentas como [Protocols.io](https://www.protocols.io/), ou processos como [Registered Reports](https://cos.io/rr/) podem ajudá-lo a reportar de forma reprodutível. Lembre-se de publicar os resultados na  sua plataforma pública de registo \(tal como [ClinicalTrials.gov](https://www.socialscienceregistry.org/) ou [SocialScienceRegistry](https://www.socialscienceregistry.org/)\) até um ano após terminar o seu estudo seja qual for a natureza ou direção dos seus resultados.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questões, obstáculos, e equívocos comuns

P: "Tudo está no artigo, qualquer pessoa pode reproduzir isto a partir dali!"

R: Este é um dos equívocos mais comuns. Mesmo uma descrição extremamente detalhada dos métodos e fluxos de trabalho usados para atingir o resultado final, na maioria dos casos não será suficiente para o reproduzir. Isto pode dever-se a vários aspetos, incluindo ambientes computacionais diferentes, versões de software diferentes, viés implícitos que não foram definidos de forma clara, etc.

P: "Não tenho tempo para aprender e estabelecer um fluxo de trabalho reprodutível"

R: Além de um número significativo de serviços online disponíveis livremente que podem ser combinados e facilitar a configuração de um fluxo de trabalho, gastar tempo e esforço a a fazê-lo aumenta não só a validade científica dos resultados finais, mas também minimizará o tempo necessário para a repetição ou extensão em estudos futuros.

P: "Terminologias que descrevam a reprodutibilidade são desafiantes."

R: Ver Barba \(2018\) para uma discussão sobre terminologia descrevendo reprodutibilidade e replicabilidade.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Resultados da aprendizagem

1. Compreender a necessidade da investigação reprodutível e o sua racionalidade.

2. Ser capaz de estabelecer um fluxo de trabalho reprodutível no contexto de uma tarefa exemplo.

3. Conhecer ferramentas que podem apoiar a investigação reprodutível.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Leitura adicional

* Button et al. (2013). Power failure: why small sample size undermines the reliability of neuroscience. [doi.org/10.1038/nrn3475](https://doi.org/10.1038/nrn3475)

* Karl Broman (n.y.). Data Organization. Choose good names for things. [kbroman.org](http://kbroman.org/dataorg/pages/names.html)



