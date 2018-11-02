##<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Software Aberto Usado na Investigação e Software de Código Aberto

### O que é?

O software aberto usado na investigação ou software de código aberto usado na investigação refere-se ao uso e desenvolvimento de software para análise, simulação, visualização, etc., onde o código fonte está disponível. Adicionalmente, de acordo com a [Definição de Código Aberto](https://opensource.org/osd), o software de código aberto deve ser distribuído na forma de código fonte e/ou de forma compilada (com o código aberto disponível no segundo caso), e deverá ser partilhado sob uma licença que permite modificação, derivações, e redistribuição.

### Fundamentação

A investigação atual depende de software e o trabalho realizado a partir dessa base - ou a sua reprodução -  necessita do acesso à totalidade do código fonte por detrás desse software \(Barnes, 2010; Morin et al., 2012; Ince et al., 2012; Prins et al. 2015; Lowndes et al., 2018\). Como refere Buckheit e Donoho, parafraseando Jon Claerbout, ‘‘An article about a computational result is advertising, not scholarship. The actual scholarship is the full software environment, code and data, that produced the result’’ \(Buckheit & Donoho, 1995\). O acesso aberto ao código fonte no software usado na investigação também ajuda a melhorar o impacto dessa  investigação \(Vandewalle, 2012\).

A partilha do software usado na investigação (quer seja de natureza computacional ou que dependa de uma análise/interpretação produzida por um software) é uma condição necessária, embora não suficiente, para a reprodutibilidade. Isto é devido à ambiguidade inevitável que surge quando tentamos descrever detalhadamente um software através de linguagem natural, por exemplo, num artigo \(Ince et al., 2012\). Além disso, muitos programas de software (se não mesmo todos) podem conter alguns erros não detetados inicialmente \(Soergel, 2015\), pelo que mesmo uma descrição “perfeita” do software não permitiria dar conta de todos os resultados. 

Adicionalmente à reprodutibilidade, a partilha livre de software permite aos programadores serem reconhecidos pelos seus esforços ao longo da sua carreira , quer através de citações diretas \(Smith et al., 2016\) quer através da publicação de meta-artigos de código em revistas como o [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) ou [Journal of Open Source Software](http://joss.theoj.org) \(Smith et al., 2018\). Neil Chue Hong mantém uma [lista de revistas de várias áreas específicas](https://www.software.ac.uk/which-journals-should-i-publish-my-software) que publicam artigos de software.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Objetivos de aprendizagem

1. Conhecer as características do software aberto; compreender os argumentos éticos, legais, económicos e de impacto na investigação, a favor e  contra o software aberto e compreender melhor os requisitos de qualidade do código aberto.

2. Aprender a usar o software aberto já existente e a atribuí-lo (citá-lo) apropriadamente.

3. Aprender a usar ferramentas e serviços habituais para  partilhar abertamente  os códigos de investigação.

4. Ser capaz de escolher a licença apropriada para o seu software, e compreender as diferenças entre licenças permissivas e não permissivas.

### Componentes-chave

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Conhecimento

Há diferentes tipos de plataformas que suportam a partilha aberta e a colaboração em software, investigação ou outros. Em primeiro lugar, pode usar a seguinte lista de verificação para avaliar o grau de abertura do software usado na investigação:

* O software está disponível para ser descarregado e instalado?

* O software pode ser facilmente instalado em diferentes plataformas?

* O software tem condições para a sua utilização?

* O código fonte está disponível para poder ser inspecionado?

* O historial completo do código fonte está disponível para ser inspecionado através de uma versão disponível publicamente?

* As dependências do software (software e hardware) estão descritas apropriadamente? Estas dependência exigem apenas um esforço mínimo razoável para serem obtidas e usadas?

Estas qualidades estão relacionadas e são construídas a partir da [Open Source Definition](https://opensource.org/osd).

O GitHub é uma ferramenta popular que permite o controlo de versões: gestão e revisão de mudanças numa peça de software em particular. Serviços como o GitHub, GitLab, Bitbucket, e outros, proporcionam um interface para a ferramenta bem como serviços de armazenamento remoto que podem ser usados para manter, partilhar e colaborar software usado em investigação. Esta plataforma está bastante divulgada e, apesar de ser necessário um processo de aprendizagem, já provou ser muito valiosa para estabelecer um fluxo de investigação reprodutível.  

Ter o software de investigação no GitHub é só a primeira parte; é igualmente importante ter um identificador oficial e permanente associado, tal como um DOI. Há várias formas de associar um DOI a um repositório GitHub. A forma mais fácil é usar o Zenodo (um repositório gratuito, aberto e genérico criado pelo OpenAIRE e pelo CERN) para realizar a atribuição, apesar de existirem outros repositórios para arquivar software e obter um DOI, tal como o Figshare. O [Zenodo integra-se com o GitHub](https://guides.github.com/activities/citable-code/) de forma a arquivar o software e providenciar um DOI quando os programadores lançarem formalmente uma versão no GitHub. 

Qualquer software partilhado publicamente não é verdadeiramente software de código aberto a não ser que seja acompanhado de uma licença adequada, uma vez que, por defeito, os direitos de autor do software (juntamente com qualquer outro tipo de trabalho criativo) pertencem aos seus criadores, o que significa que mais ninguém pode usar, copiar, distribuir ou modificar \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(Se realmente pretende partilhar o seu código sem qualquer tipo de restrições, pode [torná-lo de domínio público](https://choosealicense.com/licenses/#unlicense).\) Em alternativa, deverá escolher uma licença apropriada para o seu software baseado no que desejar que as outras pessoas façam com o seu código \(ou no que desejar impedir\); o website [choosealicense.org](https://choosealicense.com) é um recurso útil para saber as diferenças entre as várias licenças, apesar de não incluir [todas as licenças de código aberto disponíveis ou mais populares](https://opensource.org/licenses). Quando selecionar uma licença, coloque o texto - editado para incluir o nome do\(s\) autor\(es\) e o ano - no repositório de software como ficheiro de texto simples intitulado LICENSE. 

![](/Images/02 Open Science Basics/02_open_research_software_open_source.png)

Apesar de a partilha de software em qualquer formato ser melhor que não o partilhar, o seu software terá mais impacto e será mais facilmente usado por outros – e até mesmo por si no futuro!- se incluir documentação. Esta documentação pode incluir comentários úteis no código que expliquem o **porquê** de ter feito algo \(em vez de apenas o que foi feito, que por si já é evidente\), um ficheiro README que descreva o que o software faz e que dê informação útil \(ex.: como instalar, como citar, como executar, dependências importantes\), tutoriais/exemplos e/ou documentação API  \(que poderá ser automaticamente gerada através de comentários corretamente formatados no código\).

As barreiras mais comuns à reutilização e reprodutibilidade são a inexistência ou inacessibilidade de dependências, ou documentação insuficiente sobre o ambiente computacional. Uma hipótese para lidar com estas barreiras é partilhar o seu código juntamente com o ambiente computacional usando a tecnologia de contentores. Os contentores empacotam o código com as respetivas dependências e ambiente computacional, de forma a que outros possam mais facilmente executar a sua análise. O [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/), e o [Code Ocean](https://codeocean.com/) são exemplo de implementação de contentores na investigação. 

Quando usar um software – quer o tenha escrito ou outra pessoa o tenha feito e o tenha disponibilizado – a respetiva citação apropriada é importante para efeitos de reprodutibilidade \( discutido na [Secção 4](#heading=h.jy7n9xm9zn9o); em resumo, a versão usada poderá mudar os seus resultados ou a sua interpretação\) e como reconhecimento aos programadores do software \(Niemeyer 2016, Smith 2016\). A decisão de quando citar o software é sua como investigador, mas recomendamos uma citação sempre que o software tenha contribuído para os seus resultados, interpretação ou conclusões. A melhor forma de tornar o  _seu_ código facilmente citável é usar a integração GitHub-Zenodo descrita anteriormente e providenciar o DOI resultante num sítio óbvio tal como o README do software, incluindo talvez uma sugestão de  formato de referenciação. Sempre que referenciar um software deverá incluir no mínimo o\(s\) nome\(s\) do\(s\) autor\(es\),o título do software, o número da versão e o identificador/localizador único \(Smith 2016\). Se usar software de outra pessoa e este proporciona um DOI, poderá facilmente usá-lo para identificar e apontar para o software; se os autores não arquivaram o software, então deverá incluir o URL do local onde o software pode ser encontrado e o número da versão ou, por exemplo, um registo de mudanças no ficheiro \("commit hash"\).

Adicionalmente, há conceitos mais complicados que incluem testes automáticos e integração continua de software, empacotamento do software em formatos binários, e governação e gestão de projetos do código aberto com vários participantes \(ex.: códigos de conduta, guias para contribuição\). Alguns destes tópicos são descritos por Scopatz and Huff \(2015\). Wilson et al. \(2017\) também providenciam um guia prático de boas práticas de computação científica que inclui conselhos específicos para o desenvolvimento de software usado em investigação.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Hardware de Código Aberto

Os princípios de código aberto descritos anteriormente estendem-se ao hardware. Os investigadores usam muitas vezes instrumentos ou hardware proprietários na sua investigação e que não são gratuitamente acessíveis, reutilizáveis ou adaptáveis. O hardware científico inclui tudo desde ferramentas de sequenciamento e microscópios até equipamento especial para realização de testes e aceleradores de partículas. A comunidade Hardware de Ciência Aberta \(OScH em inglês\), por exemplo, está a incentivar para que o movimento de código aberto inclua instrumentos científicos, hardware e infraestruturas de investigação através do seu  [Global Open Science Hardware Roadmap](http://openhardware.science/global-open-science-hardware-roadmap/).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Competências

* Criar um repositório no GitHub e permitir a integração com o Zenodo. Use o software Mint como ferramenta analítica para a primeira versão do software.

* Escolher uma licença de software usando, por exemplo, [choosealicense](https://choosealicense.com) ou [Open Source Initiative](https://opensource.org/licenses).

* Criar documentação para um pacote de software, incluindo um ficheiro README, comentários e exemplos..

* Referenciar apropriadamente o software usado num artigo.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questões, obstáculos e equívocos comuns 

Q: “Não posso partilhar o meu software – está muito confuso / não tem uma boa documentação / não deixei bons comentários!”

R: Os criadores de software usado em investigação por todo o mundo identificam-se com este sentimento – as pessoas raramente sentem que o seu código está “pronto” para ser partilhado publicamente ou que está “terminado”. Contudo, como refere  Barnes \(2010\), “if your code is good enough to do the job, then it is good enough to release—and releasing it will help your research and your field.” Por outras palavras, se se sente suficientemente confortável com o seu software para publicar um estudo ou um relatório com os resultados, então o código está suficientemente desenvolvido para ser partilhado com os seus colegas \(por outro lado, se não se sente confortável em partilhar o seu código, então talvez precise de ser mais desenvolvido ou testado antes de ser usado numa publicação\). Adicionalmente, partilhar o seu código irá permitir que outros o melhorem e construam algo a partir dele, permitindo um impacto e inovação ainda maior \(e  citações para si!\).

Q: "E se alguém se apropria do código que eu partilhei e usa-o para fins nefastos, ou afirma que o escreveu?"

A: A seleção de uma licença apropriada para o seu software ajudá-lo-á a proteger-se de qualquer uso desse software por outras pessoas; por exemplo, a licença comum [MIT License](https://choosealicense.com/licenses/mit/) inclui limitações de responsabilidade e estabelece que não se proporciona nenhuma garantia. Se alguém tentar reclamar a autoria do seu software que disponibilizou, pode assinalar as marcas de tempo (_timestamps_) no seu repositório ou versões arquivadas como prova do seu trabalho anterior.


Q: Se eu partilhar o meu código num repositório online serei inundado(a) de pedidos de apoio ao utilizador.”

R: Apesar de os potenciais utilizadores poderem pedir-lhe ajuda, quer por email ou via repositório online, não tem qualquer obrigação de providenciar ajuda se escolher não o fazer ou se não puder. Uma licença apropriada pode até proporcionar-lhe proteção legal para isso \(ex.: cláusula de exclusão de garantia da [Licença MIT](https://choosealicense.com/licenses/mit/)\).

Equívoco comum: colocar simplesmente o código online torna-o software de código aberto. De facto, a não ser que seja acompanhado de uma licença que dê permissão para que outros o usem, copiem, modifiquem e/ou distribuam, então o\(s\) criador\(es\) retem\(êm\) os direitos de autor exclusivos. O software precisa de ser acompanhado de uma licença de código aberto para que seja considerado software de código aberto.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Resultados de aprendizagem

1. Ser capaz de partilhar software usando a licença mais apropriada \(ou seja, quer as ferramentas, quer a licença\).

2. Ser capaz de carregar, atribuir versões e registar uma linha de código através de um identificador permanente.

3. Ser capaz de citar software usado num artigo de investigação.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Leitura adicional

* [The Future of Research in Free/Open Source Software Development](http://www.ics.uci.edu/~wscacchi/Papers/New/FoSER-Scacchi-2010.pdf) \(Scacchi, 2010\).

* [The Scientific Method in Practice: Reproducibility in the Computational Sciences](http://datascienceassn.org/sites/default/files/The Scientific Method in Practice - Reproducibility in the Computational Sciences.pdf) \(Stodden, 2010\).

* [The case for open computer programs](https://www.nature.com/articles/nature10836) \(Ince et al., 2012\).

* [Shining Light into Black Boxes](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4203337/pdf/nihms588981.pdf) \(Morin et al., 2012\).

* [Code Sharing Is Associated with Research Impact in Image Processing](https://infoscience.epfl.ch/record/206184/files/Vandewalle12.pdf) \(Vandewalle, 2012\).

* [Current issues and research trends on open-source software communities](https://idus.us.es/xmlui/bitstream/handle/11441/32245/Current issues and research trends.pdf?sequence=1) \(Martinez-Torres and Diaz-Fernandez, 2013\).

* [Ten simple rules for reproducible computational research](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285) \(Sandve et al., 2013\).

* [Practices in source code sharing in astrophysics](https://arxiv.org/abs/1304.6780) \(Shamir et al., 2013\).

* [A systematic literature review on the barriers faced by newcomers to open source software projects](http://igor.pro.br/publica/papers/IST_SysReview_PrePrint.pdf) \(Steinmacher et al., 2014\).

* [Knowledge sharing in open source software communities: motivations and management](https://pdfs.semanticscholar.org/f2a2/c5129cf5656af7acc7ffaf84c9c9bafe72c5.pdf) \(Iskoujina and Roberts, 2015\).

* [An open source pharma roadmap](http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1002276) \(Balasegaram et al., 2017\).

* [Upon the Shoulders of Giants: Open-Source Hardware and Software in Analytical Chemistry](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.7b00485) \(Dryden et al., 2017\).

* [Four simple recommendations to encourage best practices in research software](https://f1000research.com/articles/6-876/v1) \(Jiménez et al., 2017\).

* [Perspectives on Reproducibility and Sustainability of Open-Source Scientific Software from Seven Years of the Dedalus Project](https://arxiv.org/abs/1801.08200) \(Oishi et al., 2018\).



