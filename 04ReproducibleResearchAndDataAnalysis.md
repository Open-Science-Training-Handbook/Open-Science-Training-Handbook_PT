## <img src="/Images/Icons/reuse.png" width="200" height="200" /> <img src="/Images/Icons/research.png" width="200" height="200" />

## 4. Investigação reprodutível e análise de dados

### O que é?

Reprodutibilidade significa que os dados da investigação e o código são disponibilizados de forma a que outros possam atingir os mesmos resultados que são obtidos em resultados científicos.  Relacionado é o conceito de replicabilidade, o ato de repetir uma metodologia científica para atingir conclusões semelhantes. Estes conceitos são elementos chave da investigação empírica.

Melhorar a reprodutibilidade leva a um maior rigor e qualidade dos resultados científicos e, portanto, a uma maior confiança na ciência. Tem havido uma crescente necessidade e vontade de expor os fluxos de trabalho de investigação desde o início de um projeto e recolha de dados até à interpretação e relato de resultados. Esses desenvolvimentos acarretam um conjunto de desafios, incluindo a criação de fluxos de trabalho de investigação integrados que podem ser adotados pelos colaboradores, mantendo altos padrões de integridade.

O conceito de reprodutibilidade é directamente aplicado ao método científico, a pedra angular da Ciência, e particularmente aos 5 passos seguintes:

1. Formular a hipótese

2. Desenhar o estudo

3. Executar o estudo e recolher os dados

4. Analizar os dados

5. Relatar o estudo

Cada um destes passos deve ser relatado de forma clara, fornecendo documentação clara e aberta, tornando o estudo transparente e reproduzível.

![](/Images/02 Open Science Basics/02_reproducible_research_data_analysis.png)

### Fundamentação

Factores dominantes podem contribuir ainda mais para as causas da não-reprodutibilidade, mas também podem impulsionar a implementação de medidas específicas para lidar com essas causas. A cultura e o ambiente em que a investigação tem lugar são importantes factores dominantes ‘top-down’. The culture and environment in which research takes place is an important ‘top-down’ overarching factor. De uma perspectiva ‘bottom-up’, educação continuada e formação para investigadores pode aumentar a conscientização e disseminar boas práticas.

Embora a compreensão de todos os fatores que contribuem para a reprodutibilidade seja importante, também pode ser difícil decompor esses fatores em etapas que possam ser imediatamente adotadas por um programa de investigação existente e melhorar imediatamente a sua reprodutibilidade. Um dos primeiros passos a dar é avaliar o estado atual das coisas e acompanhar a melhoria enquanto são tomadas medidas para aumentar ainda mais a reprodutibilidade. Alguns dos problemas comuns com a reprodutibilidade da investigação são mostrados na figura abaixo.

![](/Images/image_2.png)

Fonte: [Reproducibility and reliability of biomedical research: improving research practice](https://acmedsci.ac.uk/viewFile/56314e40aac61.pdf).

Goodman, Fanelli, & Ioannidis \(2016\) notam que na epidemiologia, biologia computacional, economia e testes clínicos, a reprodutibilidade é frequentemente definida como:

_the ability of a researcher to duplicate the results of a prior study using the same materials as were used by the original investigator. That is, a second researcher might use the same raw data to build the same analysis files and implement the same statistical analysis in an attempt to yield the same results._

Isto é distinto de replicabilidade:

_which refers to the ability of a researcher to duplicate the results of a prior study if the same procedures are followed but new data are collected._

Uma forma simples the pensar sobre isto pode ser que a reprodutibilidade é orientada pelo método, enquanto a replicabilidade é orientada para os resultados 

A reprodutibilidade pode ser avaliada a diferentes níveis: ao nível de um projecto individual  \(ex., um artigo, uma experiência, um método ou um conjunto de dados\), um investigador individual, um laboratório ou grupo de investigação, uma instituição, ou mesmo uma área de investigação. Critérios e pontos de avaliação ligeiramente diferentes podem aplicar-se a esses diferentes níveis. Por exemplo, uma instituição defende as práticas de reprodutibilidade se instituir políticas que recompensem os investigadores que realizem investigação reproduzível. Por outro lado, um campo de investigação pode ser considerado como tendo um nível mais elevado de reprodutibilidade se desenvolver recursos mantidos pela comunidade que promovam e permitam práticas de pesquisa reproduzíveis, como repositórios de dados ou normativas para partilha de dados. 

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Objectivos de aprendizagem

Existem três objectivos principais que têm que abordados aqui:

1. Compreender o importante impacto de criar investigação reproduzível. 

2. Compreender a configuração geral da investigação reproduzível \(incluindo o desenho de fluxos de trabalho, gestão de dados e relatório dinâmico\).

3. Estar consciente dos passos individuais no processo de reprodutibilidade, bem como os respectivos recursos que podem ser utilizados.

### Componentes chave

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Conhecimento

Segue-se uma lista indicativa de ideias a reter sobre reprodutibilidade:

* Qual é a "crise de reprodutibilidade" e meta-análises de reprodutibilidade.

* Princípios de reprodutibilidade e integridade e ética na investigação.

* Quais são as opções de computação e ambientes que permitem um meio colaborativo e reproduzível.

* Factores que afectam a reprodutibilidade da investigação.

* Documentação de análise de dados e fluxos de trabalho de investigação aberta.

* Ambientes de análise reproduzíveis \(virtualização\).

* Abordando os "Researcher Degrees of Freedom" \(Wicherts et al., 2016\).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Competências

Existem várias dicas práticas para a reprodutibilidade que devemos ter em conta quando definimos as competências específicas necessárias para a garantir.  As boas práticas em reprodutibilidade utilizam práticas da Ciência Aberta no geral, mas a sua integração oferece benefícios ao investigador individual, quer escolha partilhar a sua investigação ou não. A razão pela qual integrar as boas práticas da reprodutibilidade beneficia o investigador individual é porque estas melhoram o planeamento, a organização e a documentação da investigação.  Em baixo descrevemos um exemplo de implementação de reprodutibilidade num fluxo de trabalho de investigação com referências a estas práticas no manual.

## <img src="/Images/Icons/task.png" width="150" height="150" />
##### **1. Planeie a reprodutibilidade antes de começar **

###### Crie um plano de estudo ou protocolo.

Comece a documentar no início do estudo escrevendo um plano de estudo ou protoco que inclua o desenho e métodos do estudo proposto. Use uma directriz de relatório do [Equator Network](http://www.equator-network.org/) se aplicável. Registe as alterações ao plano de estudo ou protocolo usando um versão de controlo \(reference to Version Control\). Calcule o alcance ou tamanho da amostra necessária e relate este cálculo no seu protocolo, pois estudos com pouco alcance são propensos à irreprodutibilidade.

###### Escolha ferramentas e materiais reprodutíveis

Escolha anticorpos que funcionem usando um motor depesquisa de anticorpos como [CiteAb](https://www.citeab.com/). Evite a irreprodutibilidade através de linhas de células mal identificadas escolhendo as que estão autenticadas pela [International Cell Line Authentication Committee](http://iclac.org/). Sempre que possível, escolha ferramentas de software e hardware que retenham a propriedade da sua investigação e que permitam a exportação da plataforma para reutilização \(see Open Research Software and Open Source\).

###### Estabeleça um projecto reproduzível

Centralize e organize a gestão do seu projecto usando um plataforma online, um repositório central, ou pasta para todos os ficheiros da investigação. Pode usar o GitHub como local para armazenar todos os ficheiros do projecto ou gerir tudo usando um caderno de laboratório electrónico como [Benchling](https://benchling.com/), [Labguru](https://www.labguru.com/),ou [SciNote](https://scinote.net/). Dentro do projecto centralizado, siga as boas práticas separando os seus dados do código em pastas diferentes. Torne os seus dados não tratados num versão apenas de leitura e mantenha-os separados dos dados processados \(reference to Data Management\).

Ao gravar e arquivar os seus ficheiros de investigação, use formatos e nomes de ficheiros informativos que permitam a reutilização. Os nomes dos ficheiros devem ser legíveis para máquinas e humanos. \(reference to Data Management\). Na sua análise e código de software use caminhos relativos. Evite formatos de ficheiros proprietários e use formatos de ficheiro abertos \(see 6 Open Licensing and File Formats\).

## <img src="/Images/Icons/handson.png" width="150" height="150" />
##### **2. Mantenha um registo**

###### Registo

Faça um pré-registo de informação importante do desenho e análise do estudo para aumentar a transparência e combater o viés da publicação de resultados negativos. Ferramentas gratuitas que podem ajudar a fazer o primeiro registo incluem [AsPredicted](https://aspredicted.org/), [Open Science Framework](https://osf.io/), e [Registered Reports](https://cos.io/rr/). Estudos clínicos devem usar [Clinicaltrials.gov](https://clinicaltrials.gov/).

###### Controlo de versões

Registe as alterações aos seus ficheiros, especialmente o código de análise, usando um controlo de versões \(see Open Research Software and Open Source\).

###### Documentação

Documente tudo o que foi feito, manualmente, num ficheiro README. Crie um dicionário de dados \(também conhecido como livro de código\)para descrever informação importante sobre os seus dados. Para uma introdução simples, use: [Karl Broman’s Data Organization module](http://kbroman.org/dataorg/pages/dictionary.html) e consulte Gestão de Dados.

###### Programação literária

Considere usar [Jupyter Notebooks](http://jupyter.org/), [KnitR](https://yihui.name/knitr/), [Sweave](https://support.rstudio.com/hc/en-us/articles/200552056-Using-Sweave-and-knitr), ou outras abordagens de programação literária para integrar o seu código com a sua narrativa e documentação.

## <img src="/Images/Icons/open_licenses.png" width="150" height="150" />
##### 3**. Partilhe e licencie a sua investigação**

###### Dados

Evite ficheiros suplementares, decida por um licença permissiva aceitável, e partilhe os seus dados usando um repositório. Siga as boas práticas descritas no capítulo Dados de Investigação Abertos e Materiais.

###### Materiais

Partilhe os seus materiais de forma a que possam ser reutilizados. Deposite os  reagentes em repositórios como [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/), e [ATCC](https://www.atcc.org/) para os tornar facilmente acessíveis a outros investigadores. Para mais informação, veja a subsecção Materiais Aberto de Dados de Investigação Abertos e Materiais.

###### Software, cadernos de notas, e containers

Licencie o seu código para informar como este pode ser \(re\)utilizado. Partilhe os cadernos de notas com serviços como [mybinder](http://mybinder.org) que permitam a visualização pública e execução de todo o caderno de notas em recursos partilhados. Partilhe os containers ou cadernos de notas com serviços como [Rocker](https://arxiv.org/abs/1710.03675) ou [Code Ocean](https://codeocean.com/). Siga as boas práticas descritas em Open Research Software and Open Source.

## <img src="/Images/Icons/open_scholarship.png" width="150" height="150" />
##### 4**. Relate a sua investigação de forma transparente**

Relate e publique os seus métodos e intervenções de forma explícita e transparente  e que permite a replicação. Directrizes de [Equator Network](http://www.equator-network.org/), ferramentas como [Protocols.io](https://www.protocols.io/), ou processos como [Registered Reports](https://cos.io/rr/) podem ajudá-lo a relatar de forma reproduzível. Lembre-se de publicar os resultados na  sua plataforma pública de registo \(tal como [ClinicalTrials.gov](https://www.socialscienceregistry.org/) ou [SocialScienceRegistry](https://www.socialscienceregistry.org/)\) até um ano após terminar o seu estudo seja qual for a natures ou direcção dos resultados.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questões, obstáculos, e equívocos comuns

P: "Tudo está no artigo, qualquer pessoa pode reproduzir isto a partir daquilo!"

R: Este é um dos equívocos mais comuns. Memos tendo uma descrição extremamente detalhada dos métodos e fluxos de trabalho usados para atingir o resultado final, na maioria dos casos não será suficiente para o reproduzir. Isto pode ver-se a vários aspectos, incluíndo ambientes computacionais diferentes, versões de software diferentes, viés implícitos que não foram definidos de forma clara, etc.

P: "Não tenho tempo para aprender e estabelecer um fluxo de trabalho reproduzível"

R: Além de um número significativo de serviços online disponíveis que podem ser combinados e facilitar a configuração de um fluxo de trabalho, gastar tempo e esforço a a fazê-lo aumenta não só a validade científica dos resultados finais, mas tambem minimiza o tempo de repetição ou extensão para estudos futuros.

P: "Terminologias que descrevam a reprodutibilidade são desafiantes."

R: Ver Barba \(2018\) para uma discussão sobre terminologia descrevendo reprodutibilidade e replicabilidade.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Resultados da aprendizagem

1. Compreender a necessidade da investigação reproduzível e o seu raciocínio.

2. Ser capaz de estabelecer um fluxo de trabalho reproduzível no contexto de uma tarefa exemplo.

3. Conhecer ferramentas que podem apoiar a investigação reproduzível.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Leitura adicional

* Calcular o seu poder: [Button et al. \(2013\) study of the relationship between reproducibility and power.](https://www.nature.com/articles/nrn3475)

* Nomeação informativa: [Karl Broman’s Data Organization module: Choose good names for things](http://kbroman.org/dataorg/pages/names.html)


