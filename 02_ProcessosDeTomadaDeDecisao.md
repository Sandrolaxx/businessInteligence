# Processos de Tomada de Decisão

## O que é Enterprise Resource Planning?

A sigla ERP significa “Planejamento de Recursos Empresariais”. Um ERP (Enterprise Resource Planning) é um sistema modular, integrado através de um banco de dados comum. Os módulos atendem praticamente todas as áreas e departamentos de uma empresa, de forma que um único evento que tenha dado origem à execução de um processo de um departamento, seja trabalhado pelas demais áreas que tenham alguma responsabilidade paralela ou sequencial sobre ele.

Por exemplo, quando um cliente faz uma compra, processos serão disparados e os dados serão acessados pelas demais áreas da empresa. Uma ordem será enviada para que o armazém separe o produto adquirido pelo cliente, o setor de logística será informado sobre a compra, receberá os dados de entrega e a liberação do armazém para retirada. O departamento de Contabilidade será informado para enviar uma fatura para o cliente. A redução do estoque no armazém, pode disparar um processo de fabricação ou apenas de compra, se a empresa for somente uma revendedora. Todos esses passos são monitorados pelo setor de qualidade e de atendimento ao cliente. As informações geradas podem e devem ser usadas para planejamentos futuros ou intervenções, em casos de desvios pontuais. 

Toda essa integração é possível porque o banco de dados recebe os dados de um módulo e os deixa disponíveis para todos os demais módulos do ERP. Além disso, um módulo pode díspar um processo em outro módulo e quando este outro acrescentar novos dados, eles também se tornarão imediatamente disponíveis para todos as demais áreas envolvidas, possibilitando que o ERP controle e forneça suporte a todos, ou quase todos, processos operacionais, produtivos, administrativos e comerciais da empresa.

!["Representação de um ERP"](/images/02_ProcessosTomadaDecisao/representacaoERP.png)
| - Representação de um ERP(Fonte: FIAP(2017))

O Planejamento de Recursos Empresariais ( ERP ) também é comumente definido como um pacote integrado de aplicativos de negócios. As ferramentas ERP são chamadas assim, pois compartilham um modelo comum de processo e de dados do negócio, automatizando e suportando processos operacionais de ponta a ponta, como os que se encontram nas áreas de produção e manufatura, finanças e contabilidade, RH, vendas etc.

---

## Um breve histórico sobre ERP

No final da década de 1950, a tecnologia se baseava em gigantescos mainframes, a automatização era cara e lenta, mas já demonstrava bons resultados nos primeiros sistemas de controle de estoque. Em meados da década de 1960, surgiu o conceito de sistemas MRP (Material Requirement Planning) ou Planejamento das Necessidades de Materiais, sistemas capazes de processar o planejamento e o replanejamento otimizado da produção calculando os materiais necessários e os momentos de obtê-los, reduzindo custos e atendendo a demanda dentro das restrições de prazos impostas pelos clientes, além de controlar estoque.

O MRP já empregava nesta época, além dos pedidos em carteira e previsão de vendas, como dados importantes para o planejamento. Ainda hoje, temos empresas de menor porte que são administradas com o apoio de softwares que se limitam às características do MRP, mas elas sofrem sem um suporte integrado mínimo, com as áreas de compras, produção geral, financeiro e marketing.

Tais necessidades geraram a evolução do MRP para o MRPII (Manufacturing Resource Planning). O MRPII ou Planejamento dos Recursos de Manufatura surgiu em meados da década de 1980 com o objetivo de processar, de forma integrada, todos os parâmetros que determinam o planejamento da produção, o planejamento dos requisitos (incluindo mão de obra e materiais) para produção, o calendário de produção, o planejamento de vendas, compras e financeiro.

Um MRPII de certa forma já poderia ser considerado um ERP, mas foi na década de 1990 que o termo Enterprise Resource Planning foi mais divulgado e se fortaleceu, sendo reconhecido como um “Pacote” de Gestão que se beneficiou dos avanços tecnológicos da época, como o aumento da conectividade em rede, o avanço dos microcomputadores e o emprego da arquitetura client-server e a queda dos custos, em relação ao uso de mainframes.

!["A relação entre MRP, MRPII e ERP"](/images/02_ProcessosTomadaDecisao/relacaoERPeMRP.png)
| - A relação entre MRP, MRPII e ERP(Fonte: FIAP(2017))

Em 2013, o Gartner definiu o ambiente pós-moderno ERP, definição sobre a qual falaremos a seguir.

---

## Características e Módulos Principais de um ERP: Características

O Gartner define um termo para o ERP atual como ERP pós-moderno e o classifica em duas categorias de estratégia, conforme abaixo:
>O ERP pós-moderno é uma estratégia de tecnologia que automatiza e liga capacidades empresariais administrativas e operacionais (como finanças, RH, compras, fabricação e distribuição) com níveis adequados de integração que equilibram os benefícios da integração entre fornecedores e a flexibilidade e agilidade do negócio. Esta definição destaca que existem duas categorias de estratégia ERP: administrativa e operacional.

Estratégia administrativa:
* Se concentra nos aspectos administrativos do ERP, principalmente financeiros, gerenciamento de capital humano e compras indiretas. Algumas indústrias não necessitam de recursos operacionais, tais como fabricação ou distribuição, de modo que elas devem concentrar a estratégia de emprego de um ERP nas funções administrativas são geralmente caracterizadas como indústrias centradas em serviços.

Estratégia operacional:
* As organizações que realizam fabricação, distribuição, varejo etc. (referidas como indústrias centradas em produtos) muito provavelmente estenderão sua estratégia de adoção de um ERP para além das funções administrativas, cobrindo áreas operacionais, como gerenciamento de pedidos, fabricação e cadeia de suprimentos, para maximizar a eficiência operacional. Além disso, organizações com recursos intensivos podem incluir operações e manutenção de ativos em sua estratégia ERP. Essas organizações podem obter benefícios da integração entre as capacidades administrativas e operacionais, por exemplo, onde as transações operacionais que têm impacto financeiro são refletidas e administradas diretamente nos módulos financeiros.

Podemos citar como características de um ERP:
* Um sistema integrado e parametrizável que opera em tempo real ou próximo.
* Possui banco de dados comum que oferece suporte e integração a todos os módulos.
* Oferta uma aparência (UX) consistente em todos os módulos.
* Suporta os processos e implementa controles operacionais e administrativos.
* Emprega a otimização de processos.
* Gera relatórios operacionais e administrativos.
* Possibilita a gestão integrada do negócio.
* Provê a capacidade de planejar a operação.

---

## Processos de Negócios

Um ERP suporta milhares de processos de negócios e de fabricante para fabricante, possui nomenclaturas diferentes para agrupá-los em módulos. Abaixo mostramos uma representação de como esses processos podem ser agrupados e citamos a seguir algumas das mais relevantes funcionalidades que um ERP processa para uma empresa que emprega a estratégia operacional.

!["ERP por módulos e funcionalidades"](/images/02_ProcessosTomadaDecisao/modulosERP.png)
| - ERP por módulos e funcionalidades(Fonte: FIAP(2017))

Compras:
* Movimentação de fornecedores.
* Controle de cotações.
* Geração de Pedidos de Compra.
* Melhor data de Compra.
* Quantidade Ideal.
* Análise e seleção de fornecedores (desempenho).
* Controle da carteira de Pedidos de Compra.

Vendas (faturamento):
* Informações sobre clientes.
* Análise de crédito.
* Controle da carteira de pedidos de venda.
* Previsões de vendas.
* Controle de pedidos de devolução.
* Geração de controles estatísticos de vendas.
* Informações sobre vendedores.

Estoque:
* Movimentação dos itens.
* Movimentação dos saldos (entradas e saídas).
* Giro do Estoque.
* Apuração do custo médio.
* Cálculo do lote econômico e ponto de pedido.
* Inventário.
* Classificação ABC.
* Rotinas para fechamento dos estoques.
* Disparo de solicitação de produção ou compra.

Financeiro:
* Planejamento e monitoramento financeiro.
* Movimentação das carteiras de títulos a pagar e receber.
* Conciliador de cartões.
* Acompanhamento e emissão das carteiras de títulos e valores.
* Simulação e emissão do fluxo de caixa.
* Emissão do razão e diário auxiliar (clientes e fornecedores).

Planejamento e Controle da Produção (PCP):
* Engenharia de produtos.
* Controle de fichas técnicas e roteiros de produção.
* Planejamento e monitoramento de insumos.
* Ordens de produção (através dos pedidos de vendas).
* Acompanhamento da produção.
* Controle dos números de série.
* Movimentação dos recursos de produção (mão de obra e ferramental).
* Movimentação dos roteiros de fabricação (operações por produto).
* Gestão do calendário de produção.
* Alocação da carga máquina por carteira de vendas.

Carga Máquina:
* Alocação das ordens de produção à capacidade das máquinas.
* Controle da capacidade nominal das máquinas.
* Visualização da carga máquina.
* Controle de manutenção das máquinas.

Chão de Fábrica:
* Apontamentos de produção.
* Utilização e ociosidade máquina.

Consultas e Relatórios:
* Produtividade.
* Eficiência.
* Atrasos.
* Qualidade e padrão.
* Horas paradas.
* Defeitos e refugos.
* Vida útil de máquinas e moldes.

Contabilidade:
* Geração do plano de contas.
* Geração dos históricos padrões.
* Geração dos centros de custos.
* Lançamentos e conciliações contábeis.
* Gestão de rateios.
* Emissão dos documentos legais: razão, diário, balanço, balancete, demonstrativo de lucros e perdas.

Ativo fixo:
* Classificação de aquisições.
* Controle dos bens patrimoniais.
* Movimentação dos bens.
* Cálculo e controle das depreciações.

Recursos humanos (folha de pagamento):
* Movimentação dos funcionários.
* Cálculo e geração da folha de pagamento.
* Cálculo de férias e 13º salário.
* Cálculo de indenizações trabalhistas.
* Controle dos encargos sociais (INSS, FGTS, outros).
* Controle das horas produtivas e improdutivas.

---

## Implementando um ERP: Melhores Práticas

A maioria dos sistemas ERP incorpora o conceito de melhores práticas. Isso significa que o software implementa a visão do fabricante sobre a maneira mais efetiva de executar cada processo de negócio. Portanto, é comum que os grandes fabricantes segmentem suas ofertas de ERP com soluções que possuem módulos específicos para as áreas de negócio em que seus clientes atuam, tais como: manufatura, varejo, serviços, agroindústria, construção, saúde, serviços financeiros, logística, bem como, pelo porte da empresa.

As boas práticas, então, são formadas não somente pela interpretação do fabricante sobre o processo, mas pela experiência que esse fabricante adquire com as solicitações de manutenções evolutivas e corretivas feitas pelos seus clientes e pelas restrições legais do local onde seu cliente opera.

A adoção das melhores práticas pelo cliente facilita, reduz custo, o prazo e o risco da implementação de um ERP e garante a conformidade com requisitos como Sarbanes-Oxley ou Basileia II.

---

## Implementando um ERP: Funcionalidade

Diz respeito às funcionalidades que um ERP possui, suas particularidades,
diferentes possibilidades de uso e áreas de negócio que melhor se adapta.

---

## Implementando um ERP: Módulos

São subconjuntos de um ERP que processam funções ou suportam departamentos ou áreas de uma empresa. Como módulo de RH, módulo contábil ou de PCP. Tais módulos podem ser adquiridos e implementados separadamente, como sistemas autônomos. Todavia, essa geralmente não é uma boa estratégia, embora a implantação de um ERP por etapa e módulos seja.

---

## Implementando um ERP: Parametrização

É o processo de adequação da funcionalidade de um sistema ERP a uma determinada regra ou valor utilizado por uma empresa cliente ou imposta por uma restrição legal, com a definição dos valores de parâmetros com interface de cadastro e base para armazenamento, previamente disponibilizados no próprio ERP. Um bom ERP possui centenas de parâmetros que permitem o ajuste do ERP fino às necessidades da empresa ou às restrições legais, evitando ao máximo customizações.

---

## Implementando um ERP: Customização

É o processo de modificação de um sistema ERP para adequá-lo ou personalizá-lo às situações empresariais específicas de um cliente. Deve ser cuidadosamente avaliada, sob risco de se adquirir um pacote e acabar-se tendo um sistema integrado. A customização em geral é muito cara, normalmente implica em um maior controle no recebimento de evoluções ou novas versões feitas pelo fabricante e nem sempre geram o resultado esperado.

---

## Implementando um ERP: Configuração

É o conjunto total de parâmetros do sistema após a sua definição, englobando o conjunto das opções de funcionamento das diferentes funções de um sistema ERP. Podemos citar como configurações adequações ao SO, ambiente de redes, desktops, smartphones, banco de dados, entre outros.

---

## Implementando um ERP: Adequações à Localização

Corresponde à adaptação de um ERP desenvolvido em um país para utilização em outros. Essa adequação se faz necessária para cumprimento às leis e procedimentos comerciais específicos locais. Parametrizações de moeda, idioma e regulações fiscais são exemplos de adequações à localização.

---

## Implementando um ERP: Atualização de versões (upgrade)

É o processo no qual o fabricante do software disponibiliza melhorias, novas funcionalidades, alinhamentos a novas restrições legais, além da correção de erros do sistema.

---

## Implementando um ERP: Vantagens com a implementação do ERP

O ERP pode melhorar a qualidade e eficiência do negócio ao manter os processos de negócios de uma empresa funcionando de maneira segura, integrada e monitorada. 

>O ERP oferece suporte ao gerenciamento ágil, fornecendo informações praticamente em tempo real, para a tomada de decisões. 

O ERP cria uma empresa mais ágil que se adapta melhor para a oportunidades e problemas. Isso também torna a empresa mais flexível e mais colaborativa, possibilitando que as áreas da organização funcionem com informações compartilhadas e de forma mais eficiente, buscando aumentar o negócio, tanto internamente como externamente. 

Um ERP implementado corretamente pode melhorar a segurança dos dados, controlando e garantindo por meio de armazenamento restrito, uso de autenticações, níveis de alçada e permissões que os principais dados da empresa não sejam comprometidos. 

Como um dos principais pilares de um ERP é uma base de dados comum, essas soluções oferecem maiores oportunidades de colaboração. Dados, documentos, formulários, áudio e vídeo podem ser armazenados e compartilhados e em alguns casos, através de mecanismos específicos de colaboração.

Podemos elencar como algumas vantagens do uso de um ERP:
* Otimização dos processos operacionais e administrativos.
* Redistribuição de funções.
* Redução do estoque e de custos.
* Integração e maior colaboração entre as áreas.
* Redução de retrabalhos.
* Monitoramento das operações do início ao fim.
* Geração de informações para tomada de decisões.
* Aumento da agilidade na tomada de decisões.
* Segurança dos dados.
* Solução flexível (novos módulos podem ser adquiridos).
* Aquisição de conhecimento sobre as “Boas Práticas” do segmento.

---

## Implementando um ERP: Desvantagens com a implementação do ERP

A adoção das Boas Práticas pode tolher a capacidade de diferenciação da empresa e causar perda na capacidade competitiva. Além disso, a reengenharia dos processos de negócios para se adequar ao ERP demandará esforços de levantamento, documentação e treinamentos, geralmente criando restrições por parte dos colaboradores e desviando o foco deles das atividades que desempenham.

Já a customização, como comentamos, pode ser muito problemática e custosa. Um ERP personalizado custa mais caro e, certamente, custará muito mais caro do que soluções sob medida, menos integradas e menos abrangentes.

Customizações invariavelmente aumentam as despesas de suporte, manutenção e atualização.

Podemos elencar como algumas desvantagens do uso de um ERP:
* Custos elevados (hardware, infraestrutura, licença de software, treinamento e consultoria).
* Alteração nos processos funcionais para adequação às boas práticas.
* Possível perda de capacidade criativa e vantagens competitivas.
* Impactos sobre os colaboradores.
* Impacto de customizações (quando necessárias).
* Projeto de implementação complexo.
* Problemas no cumprimento de prazos.

---

## SWOT como Ferramenta de Decisão

Análise SWOT ou Strengths (Forças), Weaknesses (Fraquezas), Opportunities (Oportunidades) e Threats (Ameaças) é uma ferramenta de análise bastante utilizada pelo mundo corporativo para planejamento estratégico por meio da obtenção de informações importantes que caracterizam o ambiente interno (Forças e Fraquezas) e o ambiente externo (Oportunidades e Ameaças). 

É um sistema simples e prático que auxilia uma empresa a adotar uma posição estratégica em um determinado ambiente. 

Em nosso caso, vamos aplicar a técnica para nos ajudar a analisar as opções de desenvolver uma solução especialista caseira ou adotar um ERP. Claro que esta é uma análise hipotética que pode e vai variar muito de acordo com as características da empresa e do segmento de negócio em questão. Nosso intuito então é apenas sintetizar através da técnica os dilemas de uma empresa no momento de decisão.

---

## Desenvolver uma solução caseira

|Ameaças |Oportunidades  | Pontos Fortes | Pontos Fracos |
---      |   ---         |           --- |           --- | 
|Superação tecnológica, Riscos na sustentação de novos negócios ou novos requisitos, Pouca visão sobre as práticas do mercado, Dependência de treinamentos específicos para colaboradores| Adequação plena às necessidades da empresa, Liberdade de criação e de diferenciação (possível vantagem competitiva) | Custos mais baixos, Software sob medida, customização plena | Dependência de equipe de desenvolvimento interna ou terceirizada, Risco de processos desalinhados com o mercado ou com imposições legais|

---

## Trocar solução caseira por pacote ERP

|Ameaças |Oportunidades  | Pontos Fortes | Pontos Fracos |
---      |   ---         |           --- |           --- | 
|Insucesso na implantação, Custos descontrolados, Prazos descumpridos| Melhoria de processos através de revisões com visões externas, Melhor  ntegração com Clientes e Fornecedores, Trabalho em ambiente remoto e na maioria dos pacotes, em ambiente mobile| Independência de time de desenvolvimento, Alinhamento com o mercado e restrições legais, BI integrado| Problemas de customização, Custos contínuos altos, Risco de perda de foco no que é crítico durante a implantação, Possível resistência a mudança de processos, Perda de criação e diferenciação|

---

## Critérios para seleção de um ERP

Neste tópico, deixaremos de lado os detalhes sobre custo, devido à quantidade gigantesca de cenários possíveis e de fornecedores do mercado. Vamos focar nos seguintes contextos.

Como comentamos, a implementação de um ERP geralmente requer mudanças nos processos operacionais e administrativos em vigor. A insuficiente compreensão sobre esta necessidade e o impacto de tais mudanças, antes da implementação inicial, é uma das principais razões para o insucesso do projeto de implantação.

Sendo assim, é fundamental que as corporações analisem minuciosamente seus processos antes de implementar um ERP, e os compare com os processos da solução ou das soluções ERP eleitas em fase de escolha, para uma avaliação do alinhamento e ajustes necessários nos processos. Por si só, este trabalho já é demasiado custoso e comumente envolve colaboradores importantes que já sofrem impactos em suas atividades do dia a dia, ainda na fase escolha da solução. 

É obvio que a busca se dá por um software que se adeque à empresa, mas se isto não for possível, a solução amplamente adotada pelo mercado é mudar os processos para que eles se alinhem as Boas Práticas do fornecedor.

Como possíveis desvantagens, já comentamos sobre perda da capacidade criativa e de diferenciações que podem gerar vantagens competitivas, por outro lado, é importante considerarmos e mensurarmos que perdas de certas áreas e capacidades, muitas vezes, são compensadas por ganhos em outras áreas ou aquisição de novas capacidades.

Podemos destacar como muito importantes os seguintes critérios para seleção de uma solução ERP:
* Capacidade de apoiar a empresa no alcance dos seus objetivos estratégicos.
* Orçamento e custos iniciais.
* ROI.
* Flexibilidade e adequação aos processos diferenciados já existentes e que geram valor ou competitividade reconhecidos.
* Tecnologia atualizada e escalabilidade.
* Trabalho remoto e mobile.
* Facilidade de uso.
* Qualidade da documentação.
* Capacidade de treinamento do fornecedor.
* Acesso a dados em tempo real.
* Facilidade de parametrização e configuração.
* Capacidade de migração de dados dos legados.
* Custos hora para customizações.
* Segurança da informação.
* Experiência do fornecedor e capacidade de suporte.
* Metodologia de implantação.
* Garantia.
* Custo total.

---

## Metodologia de Implantação

Com base no que já aprendemos, um ERP pode ser encarado como um sistema de informação para toda ou quase toda a empresa. Ele aporta um banco de dados comum, um sistema modular e uma interface com características semelhantes para a empresa.

Isso significa que praticamente a empresa inteira está ou vai embarcar no mesmo barco e como durante a operação tudo estará integrado, se uma parte vazar água, o todo pode ser impactado, não?

Em face a esses riscos, à enorme quantidade de requisitos, ao envolvimento de diversos colaboradores importantes para a corporação e à gigantesca quantidade de atividades necessárias, as implantações de um ERP são estruturadas e adquiridas pelo mercado como projetos e são consideradas por todos como projetos complexos.

Portanto, a empresa que implementar o ERP, sendo a fabricante do software ou uma consultoria integradora, deve apresentar uma metodologia sólida e consolidada de implantação, que defina detalhadamente o processo de implantação por fase ou etapa ou sprints, que contenha as principais atividades e os recursos necessários.

Os grandes fornecedores possuem metodologias próprias, geralmente compostas por metodologias de gestão, experiências, frameworks e boas práticas de mercado. A grande maioria adota para os processos de gestão o PMBOK e, mais recentemente, os frameworks ágeis estão sendo adotados, com especial destaque ao SCRUM.

Recentemente, umas das maiores empresas desse mercado – a SAP, evoluiu a sua metodologia e a renomeou, agora como SAP Activate, para que a SAP tivesse o SCRUM e as entregas em Sprints como opções à metodologia anterior ASAP 8, que tem como base o ciclo de vida de projeto em cascata.

A SAP disponibiliza o treinamento ACT200 para a metodologia de implantação SAP Activate, treinamento que cobre toda a implantação SAP e permite que os participantes aprendam a aplicar as técnicas ágeis em seus projetos, através de casos de uso de projetos e simulações.

!["SAP Activate"](/images/02_ProcessosTomadaDecisao/sapActivate.png)
| - SAP Activate(Fonte: SAP(2017))

Atualmente, as consultorias integradoras perderam um pouco de espaço, em
virtude do aumento de implementações de ERP como serviço, mais conhecidos como SAAS (Software as a Service). Em implementações com estas características, a responsabilidade fica por conta da fabricante da solução.

Em SAAS, segundo o Gartner, uma das empresas que tem obtido maior
sucesso é a Oracle.

!["SASS Oracle Gartner"](/images/02_ProcessosTomadaDecisao/sassGartner.png)
| - SASS Oracle Gartner(Fonte: Oracle(2017))

---

## Desafios da Implantação

Como observamos, implantar um ERP não é nada fácil. As empresas podem gastar milhões, despender milhares de horas de esforço e levar anos para implementar uma solução ERP. Claro que os números variam muito, dependendo do porte da empresa, do segmento em que atua, da solução ERP escolhida, das adaptações de processos necessárias e das customizações adicionadas ao escopo do projeto.

Uma vez que um sistema ERP é implementado, voltar atrás é considerado por vários especialistas como algo muito mais difícil do que implantá-lo. Todos são unanimes em afirmar que é muito caro desfazer as mudanças que a implantação gera para a empresa.

Não são poucos os exemplos de tentativas ou implantações sem sucesso. As empresas, além de gastarem milhões no projeto, tiveram custos mais complexos de se mensurar, oriundos da perda de foco no negócio durante a implantação, da piora no clima organizacional e, muitas vezes, da perda de profissionais importantes para o negócio que ficaram desgastados com o processo traumático.

**Falha no detalhamento dos processos na camada operacional:** Caso a empresa não conheça exatamente a rotina das pessoas que vão, de
fato, utilizar o sistema, fatalmente fará algo inútil ou complicado.

**Falta de envolvimento dos usuários operacionais:** Os usuários operacionais conhecem detalhes críticos, muitas vezes desconsiderados. Exemplos: Operadores de máquinas que digitam errado, por causa das luvas que utilizam.

**Falha no planejamento da infraestrutura:** Recursos necessários insuficientes quando o ERP é exigido em carga máxima.

**Falta de comprometimento dos patrocinadores do projeto:** Que leva ao aumento natural da resistência dos colaboradores a mudanças.

**Falha na gestão de mudanças:** Estratégias empresariais e cenários econômicos mudam todo o tempo. É importante saber e estar preparado para gerir mudanças.

**Grandes customizações:** São caras e implicam em controles especiais.

**Falhas de testes:** O mínimo de 20% do esforço total do projeto é um número reconhecido pelo mercado como necessário para os testes. Negligenciar essa fase ou realizá-los durante a fase operacional é certeza de problemas no projeto.

**Falta de treinamento:** Erro comum, geralmente decorrente de ações para redução do custo do projeto, cortando treinamentos, ou para manter os colaboradores focados na operação. O objetivo do teste em um projeto ERP não é descobrir se o produto funciona. O objetivo é garantir se o sistema atende às necessidades da empresa cliente.

**Falhas ao carregar os dados no ERP:** As cargas de dados em um ERP são processos muito complexos que envolvem a busca, a transformação (opcional) e a carga de cada bit de dados de um sistema legado, de arquivos ou de outras fontes de dados para o ERP. Não podemos nos esquecer de que a empresa tem um histórico, muitas vezes de décadas de operações. Essas informações são fundamentais e precisam ser importadas para o pacote adquirido.

São tantos detalhes, que se abre uma ampla possibilidade de algo dar errado. Desafios simples, como diferenças de tamanho, tipo ou conteúdo de campos podem gerar enormes esforços, para serem superados ou para serem ajustados, caso uma falha ocorra.

**Falha no “cutover”:** O desligamento de sistemas antigos, em face da entrada do novo ERP, deve estar muito bem definido e o processo planejado. Um plano de contingência deve ser estabelecido cuidadosamente desde o início do processo. A migração de dados e as funcionalidades absorvidas pelo ERP devem estar completamente testadas positivamente e os colaboradores treinados e aptos a utilizá-las.

**Falhas após o “go live”:** Depois da implantação, não é incomum se deparar com problemas de documentação, suporte e falta de entendimento das responsabilidades dos envolvidos. Garanta que isso não ocorra com um plano e um checklist.

---

## Panorama (Brasil)

Anualmente, a GVcia realiza uma pesquisa para o Fórum de Informações permanente sobre a Administração e Uso de Recursos de TI – Tecnologia de Informação nas Empresas com o objetivo de conhecer e estudar a situação das empresas e organizações brasileiras. A amostra da pesquisa teve 2.540 respostas válidas, dentro de mais de 8.000 empresas pesquisadas, e nos traz uma visão do panorama Brasil em relação às empresas fornecedoras de soluções ERP e o tamanho dos clientes.

!["Pesquisa FGV ERP"](/images/02_ProcessosTomadaDecisao/pesquisaFGV.png)
| - Pesquisa FGV ERP(Fonte: FGV(2017))

!["Pesquisa FGV ERP"](/images/02_ProcessosTomadaDecisao/pesquisa2FGV.png)
| - Pesquisa FGV ERP(Fonte: FGV(2017))

Podemos perceber que a Totvs e a SAP são as duas empresas mais bem posicionadas no mercado nacional, com a distinção clara de que a Totvs tem maior presença entre as pequenas e médias empresas e a SAP um forte posicionamento nas grandes empresas.

---

## CRM: O que é CRM?

Podemos dizer que o CRM (Customer Relationship Management) é um sistema integrado de gestão com foco no cliente, constituído por um conjunto de procedimentos, processos e estratégias, organizados e integrados em um modelo de gestão. 

O Gartner Group define: “CRM é uma estratégia de negócio voltada ao entendimento e antecipação das necessidades e potenciais de uma empresa.”

Strauss e Frost (2012), comentam que CRM (gestão de relacionamento com o cliente) é um termo muitas vezes mal interpretado pelas pessoas, pois passa uma ideia de que é apenas um produto de software ou uma tecnologia. CRM é muito mais, pode ser considerado como uma filosofia de negócio, um conjunto de processos e estratégias que tem o cliente como centro. A partir desse entendimento e conhecimento sobre o cliente e com o apoio de ferramentas, pode-se construir relacionamentos de longo prazo.

As empresas sabem que se o cliente não estiver satisfeito, algum concorrente o satisfará, além disso, segundo Kotler e Fox (1998), conquistar clientes novos custa entre 5 a 7 vezes mais caro do que manter os clientes que a empresa já possui.

---

## CRM: Software CRM

Bem, mas ter o conhecimento e manter os clientes satisfeitos nos moldes atuais é um grande desafio. Uma pequena empresa, que atua no seu bairro, provavelmente, possui um maior conhecimento sobre você. Não é tão difícil para o atendente ou para o dono da padaria saber que você prefere o pão mais assado ou café com leite do que café puro. Já para uma empresa de porte maior, que opera em escalas maiores, obter esse nível de relacionamento não é tão simples assim.

Entenda, é isso que as médias, grandes e gigantescas empresas pretendem fazer, e é aí que entra em cena os softwares que possibilitam a gestão do relacionamento neste nível, normalmente também denominados como CRM.

Os sistemas CRM capturam dados do cliente de todos os contatos, fontes internas e fontes externas possíveis, consolidam e processam as informações de acordo com regras funcionais orientadas pelas estratégias de relacionamento definidas e depois distribuem ou possibilitam o acesso aos resultados para os envolvidos.

Imagine fazer tudo isso sem um sistema. Só o primeiro passo, capturar dados de todos os contatos (independentemente do canal utilizado) já é um esforço gigantesco. Atualmente, um cliente pode se comunicar com uma empresa de diversas formas, por telefone, e-mail, chat, SMS, WhatsApp e redes sociais. Não?

Um projeto de software CRM, considerado como bem-sucedido, gera uma visão clara de cada cliente, que serve tanto para melhorar o resultado das vendas e do atendimento, quanto para fortalecer e estabelecer relacionamentos mais longos com ele.

Os maiores esforços devem se centrar em três tópicos:
* Automatizar a gestão de marketing.
* Automatizar a gestão comercial, de canais e de força de vendas.
* Automatizar a gestão de serviços aos clientes.

Nesse contexto, as seguintes características de um software CRM são
destacadas, por uma das principais empresas fornecedoras de CRM no mundo:
* Capacidade de rastrear ativamente e gerenciar as informações dos clientes.
* Capacidade de conectar toda a sua equipe em qualquer dispositivo.
* Consegue capturar informações de forma inteligente dos e-mails dos clientes.
* É capaz de simplificar tarefas repetitivas para que a empresa possa fazer um acompanhamento de leads mais efetivo.
* Deve fornecer recomendações e insights instantâneos.
* Deve ser capaz de expandir e se personalizar, conforme o crescimento da empresa.

Embora sejam processos eminentemente integrados, pode-se dividir logicamente o CRM em três aspectos fundamentais:
* **CRM Operacional:** visa à criação de canais de relacionamento com o cliente.
* **CRM Analítico:** visa obter uma visão consistente do cliente, usando os dados recolhidos pelo CRM operacional para obter conhecimento que permita otimizar e gerar negócios.
* **CRM Colaborativo:** foca na obtenção do valor do cliente por meio de colaboração inteligente, baseada em conhecimento.

Atualmente, considera-se um novo tipo de CRM ainda não muito bem documentado ou estabelecido, intitulado CRM Social que retrata o relacionamento com o cliente através das mídias sociais, incluindo dados disponibilizados pelos próprios clientes em seus perfis.

Um bom exemplo de CRM Social foi implantado há poucos anos pela Gatorade, o Gatorade Mission Control Center na sua sede em Chicago. Esse centro consiste em uma sala que fica no meio do departamento de marketing e funciona como uma sala de guerra para monitorar a marca em tempo real em toda a mídia social.

Segundo a sua diretora de marketing Carla Hassan, o objetivo do projeto é "elevar a Gatorade à maior marca de esportes do mundo e transformá-la em a maior marca participativa do mundo". Para esse fim, a empresa não apenas acompanha sua marca nas mídias sociais, mas dá aos fãs a possibilidade de acesso a atletas e cientistas.

Durante o Super Bowl, por exemplo, o Gatorade deixou os fãs interagirem com várias estrelas da NFL através do Ustream enquanto testaram o novo Gatorade G Series Pro. Legal, não?

---

## Fidelização

O grande objetivo do CRM, é fidelizar o cliente, mas esse é um termo um tanto difícil de definir. Muitas vezes tendemos a achar que o cliente fidelizado é aquele que sempre compra as mesmas coisas nos mesmos lugares ou ainda que o cliente fidelizado é aquele que ganha um cartão com seu nome e alguns descontos ou milhas.

A fidelização embora possa passar pelas situações descritas, com certeza vai bem além disso, isto é, deve buscar a satisfação total do cliente antevendo suas necessidades e desejos. Além disso, o CRM bem executado exige que o cliente seja tratado com respeito, sendo oferecido a ele produtos adequados aos seus desejos e às suas necessidades.

Ora, somente através do perfeito entendimento das necessidades e expectativas do cliente, obtidas junto a ele é que podem levar à satisfação do cliente e, por conseguinte, sua fidelização.

Nesse sentido, podemos aproveitar as experiências mais recentes da Gatorade e ver como buscar a fidelização em um mundo cada vez mais social. Vamos aos pontos mais relevantes:
* Se você quiser que os clientes passem seu tempo livre com você, então precisa saber o que eles importam.
* Saber os resultados dos jogos e aprofundar o conhecimento sobre esportes se tornou fundamental para a Gatorade.
* Saiba quem está influenciando o seu cliente. Quem é que seus clientes ouvem e seguem? Um endosso desses influenciadores encurtará um longo caminho na construção de sua marca.
* Surpreenda, gere prazer e faça amigos. Saber quem influencia seus clientes é apenas o começo, o importante é torná-los amigos. Conhecendo o que é importante para eles, você pode surpreendê-los, gerar prazer no relacionamento e fazer amigos.

Perceba que Mission Control como ferramenta de CRM não tem seus pilares centrados em vendas e resultados. No fundo, tem apenas um pilar centrado no cliente, conhecê-lo, entendê-lo, descobrir seus interesses, gerar bem-estar e evoluir o relacionamento que a Gatorade quer manter com eles. Claro que a empresa vive de lucros, mas não é difícil entender que o reconhecimento da marca e a melhoria de resultados são consequências naturais dessa nova abordagem. Portanto, a fidelização promove o crescimento da lucratividade ao longo do tempo, seja pela redução de custos ou por cross-selling e up-selling.

!["Crescimento da lucratividade com o tempo"](/images/02_ProcessosTomadaDecisao/lucratividadeXtempo.png)
| - Crescimento da lucratividade com o tempo(Fonte: FIAP(2017))

* Cross-selling: oferta a clientes existentes de outros produtos ou serviços complementares àqueles que o cliente já compra. Exemplo: Aceita um sundae para acompanhar o seu lanche?

* Up-selling: É quando a empresa expõe produtos ao cliente produtos ou serviços adicionais o ou mais caros do que o cliente já compra. Exemplo: Quer trocar suas batatas fritas por batatas grandes, por apenas 50 centavos?

---

## CRM X Marketing de Massa

É importante não confundirmos os objetivos dos dois, o marketing de massa busca a venda maciça, onde ocorre a produção, distribuição e a oferta de um mesmo produto, com padrão satisfatório para a maioria dos consumidores, utilizando-se do apoio de grandes campanhas de publicidade e de promoção.

Como vimos, o CRM busca atender as necessidades do cliente e isso passa pela segmentação do mercado, atendendo-se cada vez mais as preferências e desejos dos clientes, fato que demanda um marketing direcionado que é melhor realizado quando apoiado pelos resultados obtidos pelos softwares de CRM.

!["CRM X Marketing de massa"](/images/02_ProcessosTomadaDecisao/crmXmarketingDeMassa.png)
| - CRM X Marketing de massa(FIAP: FGV(2017))

---

## O cliente e o CRM

Em síntese, podemos dizer, com base no que já vimos, que o CRM é uma estratégia de gestão de negócios executada através de um conjunto de processos que suportam o relacionamento com o cliente, para fidelização, aumento da lucratividade e ganhos de vantagem competitiva, com indispensável apoio da tecnologia, como forma de automatizar os diversos processos de negócio.

Dessa forma, o CRM integra pessoas, processos e tecnologia para otimizar o gerenciamento de todos os relacionamentos, incluindo consumidores, parceiros de negócios e canais de distribuição. 

Quando falamos de segmentação de mercado e atendimento das reais necessidades do cliente, estamos caminhando para o tratamento individualizado de cada cliente, ação mais simples de ser realizada, quando sistemas CRM estão implementados.

No marketing “one to one”, cada cliente é analisado individualmente, usualmente aplica-se a técnica IDIP, que significa: Identificar, Diferenciar, Interagir e Personalizar.

!["IDIP"](/images/02_ProcessosTomadaDecisao/idip.png)
| - IDIP(Fonte: FIAP(2017))

Os clientes são identificados por seu valor e, através de sistemas CRM, a identificação pode estender-se para milhões de clientes. No entanto, o marketing “one to one” não implica necessariamente que cada necessidade ou desejo exclusivo de um cliente será tratada de maneira única pela empresa. Em grandes negócios, podemos dizer que cada cliente identificado será agrupado com clientes com características semelhantes, mas manterá uma colaboração direta na maneira como a empresa fornecedora do produto ou serviços se comportará com relação ao grupo ao qual ele pertence.

---

## Do processo à implantação de uma solução CRM

Dissemos que, em síntese, o CRM é uma estratégia de gestão de negócios executada por um conjunto de processos que suportam o relacionamento com o cliente, para fidelização, aumento da lucratividade e ganhos de vantagem competitiva, com indispensável apoio da tecnologia, como forma de automatizar os diversos processos de negócio.

Sendo assim, podemos destacar quatro passos fundamentais para a implantação de uma solução CRM.

1. **Definição e planejamento do modelo de relacionamento:** A definição de como o cliente será tratado, quais os eventos de relacionamentos que gerarão resposta, e em que tempo isso deverá ocorrer, e como o plano de comunicação deverá ser desenvolvido para construir o relacionamento e fazer a entrega de valor proposta pela estratégia competitiva da empresa. Esta etapa é importante pois a especificação e customização dos softwares de CRM e o redesenho dos processos dependem dessa definição, portanto, é indispensável o envolvimento da alta direção.

2. **Redesenho dos processos de atendimento ao cliente:** É o levantamento e a documentação dos processos do atendimento ao cliente, desde o pedido de uma visita, o atendimento telefônico, o processo de visita pelo vendedor ou através da venda pelo telemarketing, chegando ao fluxo do pedido dentro da empresa, até o momento da venda (emissão da nota fiscal) e da entrega do produto ou serviço ao cliente.

3. **Seleção da solução tecnológica:** A decisão pela solução de CRM passa pela seleção do software que melhor represente os processos da empresa e este determina qual é o melhor hardware e banco de dados para compor essa solução.

4. **Implantação da solução de CRM:** É a aplicação, em toda a empresa, do processo de revisar a forma de pensar o negócio. Técnicas, tecnologias e processos são agora implantados para materializar a estratégia de CRM, incluindo call centers receptivo e ativo, terminais ponto de venda,
canais virtuais, redes sociais e muito mais.

---

## Desafios de TI para implantação de uma solução CRM

Em termos de TI, um software CRM captura, processa, analisa e distribui dados, como vários outros sistemas fazem. Porém, o cliente é o centro do modelo de dados e todos os relatórios e consultas têm os contatos com o cliente, como dados de entrada. Sendo assim, os requisitos de integração geralmente são muito fortes. 

Tais requisitos definem integrações com diversos pontos de contato e fontes de dados, tais como: automação de vendas, gerência de vendas, call center, televendas, serviço de atendimento e suporte ao cliente, automação de marketing, ferramentas de informações gerenciais, sites e comércio eletrônico, apps de vendas, redes sociais, entre outros, possibilitando que a empresa trace estratégias de negócios voltadas para o entendimento e antecipação das necessidades dos atuais e potenciais clientes dela. 

Portanto, há um grande desafio a se vencer, desafio esse que depende diretamente da maturidade da empresa, em relação às soluções de TI que ela possui. Empresas que adotaram soluções ERP se valem da capacidade de conectividade e integrações que essas ferramentas possuem, para facilitar a adoção de uma solução CRM e, mesmo assim, não se pode considerar a integração como algo simples. Por sua vez, empresas que possuem diversas soluções sob medida, desenvolvidas internamente ou adquiridas de fornecedores diferentes, enfrentarão uma complexidade muito maior para implantar e integrar uma solução CRM. 

Uma visão genérica do cenário comentado, pode ser percebida na imagem abaixo.

!["BI, ERP e CRM"](/images/02_ProcessosTomadaDecisao/BIeERPeCRM.png)
| - BI, ERP e CRM(Fonte: FIAP(2017))

Não podemos deixar de citar que existem clientes que integram o CRM diretamente com as ferramentas de BI, normalmente de Data Mining, para identificar aspectos não triviais, que não podem passar despercebido pelo processamento das regras de relacionamento, na solução CRM.

## O Panorama Internacional (Gartner)

Em um relatório apresentado em junho de 2020, Magic Quadrant para CRM Customer Engagement Center, o Gartner examinou e apresentou o mercado global de serviços ao cliente e aplicativos de suporte.

!["Gartner CRM"](/images/02_ProcessosTomadaDecisao/gartnerCRM.png)
| - Gartner CRM(Fonte: Zendesk(2020))

---

## O Panorama Brasil (FGV)

A GVcia, em sua pesquisa para o Fórum de Informações um gráfico sobre CRM, mas em conjunto com soluções de BI. Deixando de fora diversas soluções que implementam somente os conceitos de CRM.

!["Pesquisa FGV – BI + CRM"](/images/02_ProcessosTomadaDecisao/fgvBIeCRM.png)
| - Pesquisa FGV – BI + CRM(Fonte: FGV((2019))

---

## Conclusão

O objetivo deste conteúdo foi abordar o básico e essencial sobre ERP e CRM, por se tratarem de soluções de software prontas. Este capítulo não possibilitou experiências de desenvolvimento, mas contatos com exemplos desses pacotes são possíveis e recomendados.

## Glorssário

## Desenvolver uma solução caseira

|Sigla |Descrição  | 
---      |   ---         |
|ERP | Enterprise Resource Planning é um sistema modular, integrado através de um banco de dados comum. Os módulos atendem praticamente a todas as áreas e departamentos de uma empresa, de forma que um único evento que tenha dado origem à execução de um processo de um departamento, seja trabalhado pelas demais áreas que tenham alguma responsabilidade paralela ou sequencial sobre ele. |
|MRP | Material Requirement Planning ou Planejamento das Necessidades de Materiais, sistemas capazes de processar o planejamento e o replanejamento otimizado da produção calculando os materiais necessários e os momentos de obtê- los, reduzindo custos e atendendo a demanda dentro das restrições de prazos impostas pelos clientes, além de controlar estoque.
|MRPII | Manufacturing Resource Planning II ou Planejamento dos Recursos de Manufatura surgiu em meados da década de 1980 com o objetivo de processar, de forma integrada, todos os parâmetros que determinam o planejamento da produção, o planejamento dos requisitos (incluindo mão de obra e materiais) para produção, o calendário de produção, o planejamento de vendas, compras e financeiro. 
|Gartner | Gartner é uma empresa de consultoria fundada em 1979 por Gideon Gartner. Desenvolve tecnologias relacionadas à introspecção necessária para seus clientes tomarem suas decisões todos os dias.
|UX | Experiência do usuário, do inglês user experience (UX), termo utilizado pela primeira vez por Donald Norman em meados de 1990 para se referir, segundo ele, a toda experiência do usuário, não somente à interface e à usabilidade.
|Classificação ABC | Classificação ABC ou Curva ABC. A curva de experiência ABC, também chamada de análise de Pareto ou regra 80/20, é um método de categorização de estoques, cujo objetivo é determinar quais são os produtos mais importantes de uma empresa.
|Emissão do Razão | O Razão é um livro fundamental ao processo contábil e exigido pela legislação brasileira para empresas cuja tributação do Imposto de Renda seja com base no Lucro Real. Em virtude de sua eficiência, ele é indispensável em qualquer tipo de empresa.
|Gestão de Rateios | Gestão sobre uma fração de custos, geralmente feita entre centro de custos de uma corporação.
|Sarbanes-Oxley | Sarbanes-Oxley (Sarbanes-Oxley Act, normalmente abreviada em SOX ou Sarbox) é uma lei dos Estados Unidos criada em 30 de julho de 2002 que prevê a criação, nas empresas, de mecanismos de auditoria e segurança confiáveis, definindo regras para a criação de comitês encarregados de supervisionar suas atividades e operações, formados em boa parte por membros independentes.
|Basileia II | O Acordo de Capital de Basileia II, também conhecido como Basileia II, foi um acordo assinado no âmbito do Comitê de Supervisão Bancária de Basileia em 2004 para substituir o acordo de Basileia I. O Basileia II fixa-se em três pilares e 29 princípios básicos sobre contabilidade e supervisão bancária.
|ROI | Retorno sobre investimento, também chamado taxa de retorno, taxa de lucro ou simplesmente retorno, é a relação entre a quantidade de dinheiro ganho como resultado de um investimento e a quantidade de dinheiro investido
|SCRUM | Scrum é um framework de trabalho que emprega diversas ferramentas para o desenvolvimento iterativo e incremental utilizado no gerenciamento de projetos diversos e no desenvolvimento de software ágil.
|Sprint | No Scrum, os projetos são divididos em etapas curtas, chamadas de Sprints. O Sprint representa um Time Box dentro do qual um conjunto de atividades deve ser executado.
|SAAS | Software como serviço, do inglês Software as a service (SaaS), é uma forma de distribuição e comercialização de software. No modelo SaaS o fornecedor do software se responsabiliza por toda a estrutura necessária à disponibilização do sistema (servidores, conectividade, cuidados com segurança da informação) e o cliente utiliza o software via internet, pagando um valor pelo serviço.
|PMBOK | (Project Management Body of Knowledge) é um guia das melhores práticas do gerenciamento de projetos.

---

## Rerefências

ALBERTÃO, Sebastião Edmar. ERP: sistemas de gestão empresarial: metodologia para avaliação, seleção e implantação. v. 166, São Paulo: Iglu, 2001.

BRETZKE, Miriam. Marketing de relacionamento e competição em tempo real com CRM (customer relatioship management). Atlas, 2000.

BROWN, Stanley A. CRM: Customer Relationship Management: uma ferramenta estratégica para o mundo e-business. Makron Books, 2001.

CAIÇARA JR, CÍCERO. Sistemas integrados de gestão–ERP: uma abordagem gerencial. Curitiba: Ibpex, 2008.

COLANGELO FILHO, Lucio. Implantação de sistemas ERP. São Paulo. Atlas, 2001. 

CONTAAZUL. Sistema ERP online para pequenas empresas. [s.d.]. Disponível em: <https://contaazul.com/funcionalidades/sistema-erp/>. Acesso em: 10 nov. 2017.

CORRÊA, Henrique L.; GIANESI, Irineu GN; CAON, Mauro. Planejamento, programação e controle da produção. v. 1, São Paulo: Atlas, 2001. 

DYCHE, Jill. The CRM handbook: A business guide to customer relationship management. Boston. Addison-Wesley Professional, 2002.

FGV. 28ª Pesquisa Anual do Uso de TI. 2017. Disponível em: <http://eaesp.fgvsp.br/ensinoeconhecimento/centros/cia/pesquisa>. Acesso em: 10 nov. 2017.

FROST, Raymond; STRAUSS, Judy. E-marketing. United States. Pearson Higher, 2012.

GARTNER. Market Guide for Core Financial Management Applications in Brazil. 15 mai. 2017. Disponível em: <https://www.gartner.com/doc/3714717/market-guide-core-financial-management>. Acesso em: 10 nov. 2017.

______. Postmodern ERP. [s.d.]. Disponível em: <https://blogs.gartner.com/it- glossary/postmodern-erp/>. Acesso em: 10 nov. 2017.

GATORADE. Gatorade Mission Control. 28 abr. 2013. Disponível em: <https://www.youtube.com/watch?v=cFN8ezZmBRE>. Acesso em: 10 nov. 2017.

GONÇALVES, Jarlei Nascimento. SAP Activate – with Agile, really works and save time?. 12 ago. 2017. Disponível em: <https://blogs.sap.com/2017/08/12/sap-activate-with-agile-really-works-and-save-time/>. Acesso em: 10 nov. 2017.

HABERKORN, Ernesto Mário. Gestão empresarial com ERP. São Paulo. Microsiga Software, 2003.

HABERKORN, Ernesto. Teoria do ERP. São Paulo. Makron Books, 1999.

______. Um bate-papo sobre a gestão empresarial com ERP. São Paulo. Editora Saraiva, 2007.

HEHN, Herman F. Peopleware: como trabalhar o fator humano nas implementações de sistemas integrados de informação (ERP). São Paulo: Gente, 1999.

KOTLER, Philip; ARMSTRONG, Gary. Fundamentos de marketing. Londres. Pearson Educación, 2003.

MEIRELLES, Fernando S. 28ª Pesquisa Anual do Uso de TI. 2017. Disponível em: <http://eaesp.fgvsp.br/sites/eaesp.fgvsp.br/files/pesti2017gvciappt.pdf>. Acesso em: 10 nov. 2017.

NORRIS, Grant; HURLEY, James R. E-business e ERP: transformando as organizações. Rio de Janeiro: Qualitymark, 2001. 

ORAC. Oracle ERP Cloud é nomeado líder do Quadrante Mágico do Gartner. 28 jun. 2017. Disponível em: <https://www.oracle.com/br/corporate/pressrelease/oracle-erp-cloud-leader-gartner-magic-quadrant-20170628.html>. Acesso em: 10 nov. 2017.

PEPPERS, Don; ROGERS, Martha. CRM Series–Marketing 1 to 1 – Um Guia Executivo Para Entender e Implantar Estratégias de Customer Relationship Management. São Paulo: Peppers and Rogers Group do Brasil, 2000. 

PORTALDEAUDITORIA. Introdução à Lei Sarbanes Oxley (SOX). [s.d.]. Disponível em: <https://portaldeauditoria.com.br/introducao-lei-sarbanes-oxley-sox/>. Acesso em: 10 nov. 2017.

SALESFORCE, BEM VINDO AO TRAILHEAD. [s.d.]. Disponível <https://trailhead.salesforce.com/pt-BR>. Acesso em: 10 nov. 2017. em: ______. 

Developer SalesForce. [s.d.]. Disponível <https://developer.salesforce.com/signup>. Acesso em: 10 nov. 2017.

______. O que é CRM?. [s.d.]. Disponível em: <https://www.salesforce.com/br/crm/>. Acesso em: 10 nov. 2017. 

SANTOS, Aldemar de Araújo. ERP e Sistemas de Informações Gerenciais. São Paulo: Atlas, 2013. 

SAP. SAP Activate. [s.d.]. Disponível em: <https://www.sap.com/services/s4hana-deployment.html>. Acesso em: 10 nov. 2017. 

SOCIALBAKERS. How to Build a Social Media Command Center in 2 Days. 19 ago. 2015. Disponível em: <https://www.youtube.com/watch?v=dvV2nSCc9Bg>. Acesso em: 10 nov. 2017. 

SOCIALDRIVER. Lições de mídia social de Gatorade Mission Control. 28 ago. 2013. Disponível em: <https://socialdriver.com/2013/08/28/social-media-lessons-from-gatorade-mission-control/>. Acesso em: 10 nov. 2017.

SOCONTABILIDADE. Livro razão. [s.d.]. Disponível em: <http://www.socontabilidade.com.br/conteudo/razao.php>. Acesso em: 10 nov. 2017. 

SOUZA, Cesar Alexandre de et al. Sistemas ERP no Brasil (Enterprise Resource Planning): teoria e casos. São Paulo: Atlas, 2003. 

VIEIRA, R. P. A influência do ERP na liderança. São Paulo: Gil Editorial, 2008. 

WEB.ARCHIVE.ORG, Questões críticas que afetam uma implementação de ERP. [s.d.]. Disponível em: <https://web.archive.org/web/20130103032912/http://carl.sandiego.edu/gba573/critical_issues_affecting_an_erp.htm>. Acesso em: 10 nov. 2017. 

WIKEPEDIA. Enterprise resource planning. [s.d.]. Disponível em: <https://en.wikipedia.org/wiki/Enterprise_resource_planning>. Acesso em: 10 nov. 2017. 

ZENDESK. Gartner’s 2020 Magic Quadrant for the CRM Customer Engagement Center. 2020. Disponível em: <https://www.zendesk.com/blog/gartner-magic-quadrant-crm/>. Acesso em: 05 jul. 2020. 

ZENONE, Luiz Cláudio et al. Customer Relationship Management (CRM) conceitos e estratégias: mudando a estratégia sem comprometer o negócio. São Paulo: Atlas, 2001. 

______. CRM-Customer Relationship Management: gestão do relacionamento com o cliente e a competitividade empresarial. São Paulo. Novatec, 2007.
