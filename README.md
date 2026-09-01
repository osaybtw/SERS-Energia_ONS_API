# INTEGRANTES

Arthur de Oliveira Carvalho - RM: 573499

Gabriel Henrique S. de Melo Rodrigues - RM: 573093

Fernando Bonfim Hoefle - RM: 569920

Anna Cecília Guimarães M. Lima de Carvalho - RM: 570955

# INSTRUÇÕES:

-CRIE UM REPOSITÓRIO PÚBLICO NO GITHUB E CRIE UM README COM A DESCRIÇÃO DA ATIVIDADE, INCLUINDO AS FONTES DOS DADOS ANALISADOS.

-RESOLVA OS EXERCÍCIOS PROPOSTOS NAS AULAS 03 E 04 (OS ARQUIVOS ESTÃO NA PASTA COMPARTILHADA DA DISCIPLINA)

-INSIRA OS ARQUIVOS COM AS RESOLUÇÕES NO SEU REPOSITÓRIO.

-APENAS UM INTEGRANTE SUBMETE A TAREFA. ENVIE APENAS O LINK DO SEU REPOSITÓRIO (USE O BOTÃO ANEXAR --> LINK AQUI NA TAREFA).

-O GRUPO DEVERÁ APRESENTAR A TAREFA DESENVOLVIDA NA AULA 05 (01/09).

# Análise de Dados de Energia com API Pública

Este projeto foi desenvolvido para a disciplina de Soluções em Energias Renováveis e Sustentáveis, do curso de Ciência da Computação. O objetivo é analisar o comportamento da carga elétrica de uma região atendida pelo Sistema Interligado Nacional (SIN) utilizando dados públicos disponibilizados pelo Operador Nacional do Sistema Elétrico (ONS).

O sistema realiza uma consulta à API pública de Carga Verificada do ONS, utilizando dados referentes à região SP — São Paulo, no período de 01/08/2025 a 07/08/2025. A partir das informações obtidas, os dados são organizados e transformados em DataFrames para permitir sua análise e visualização.

Durante o desenvolvimento, são realizados diferentes procedimentos de análise dos dados. São identificadas a carga mínima, máxima e média, a mediana, a amplitude entre os valores extremos e a quantidade total de medições. Também são criados recortes específicos para identificar períodos de maior demanda elétrica.

Um dos critérios utilizados considera como alta demanda os registros cuja carga seja superior a 90% da carga máxima. Além disso, é utilizado um segundo critério, baseado nos registros com carga acima da média, permitindo comparar diferentes formas de identificar períodos de maior consumo.

Os resultados também são apresentados por meio de gráficos, possibilitando observar visualmente as variações da carga ao longo do período analisado e compreender a frequência dos diferentes níveis de demanda.

Ao final, os resultados calculados pela equipe são utilizados como base para a elaboração de um relatório técnico com apoio do Gemini. O texto produzido pela inteligência artificial é posteriormente comparado com os cálculos, DataFrames e gráficos, permitindo identificar interpretações que não são sustentadas pelos dados e realizar as correções necessárias.

Dessa forma, o projeto busca não apenas analisar dados de energia elétrica, mas também demonstrar a importância de organizar, interpretar e validar informações antes de utilizá-las para chegar a conclusões.

# Análise de Dados Energéticos e de Geração

Este projeto foi desenvolvido para a disciplina de Soluções em Energias Renováveis e Sustentáveis. O objetivo é analisar diferentes conjuntos de dados relacionados ao consumo e à geração de energia, utilizando ferramentas de análise e visualização de dados para identificar situações de maior demanda e observar condições associadas a esses períodos.

O projeto utiliza seis datasets diferentes, provenientes das plataformas UCI Machine Learning Repository e Kaggle, abrangendo dados de consumo de eletrodomésticos, consumo de uma indústria siderúrgica, consumo de energia de três zonas de Tétouan, geração de uma usina solar, produção de energia solar e eólica e consumo elétrico residencial.

Em cada análise, os dados são inicialmente explorados no Orange Data Mining, onde são selecionados os atributos relevantes, verificadas informações como valores ausentes e características das variáveis, e geradas amostras dos conjuntos originais. Em seguida, as amostras são exportadas e analisadas utilizando Python e Pandas.

A etapa em Python envolve a organização dos dados, apresentação de informações estatísticas e criação de filtros específicos. São calculados valores máximos, médias e limiares de demanda ou geração, geralmente utilizando uma porcentagem do valor máximo como critério para identificar períodos elevados. Também são criados DataFrames específicos para comparar diferentes condições presentes nesses períodos.

As análises abordam diferentes situações. No consumo de eletrodomésticos e no consumo residencial, são investigadas condições ambientais e elétricas associadas aos períodos de maior consumo. No dataset da indústria siderúrgica, são observados períodos de consumo elevado em conjunto com categorias de carga e fatores de potência. No consumo de Tétouan, são comparados os picos de três zonas distintas e suas condições ambientais. Já nos datasets de geração renovável, são analisados períodos de alta geração solar e eólica e a frequência de participação dos inversores durante momentos de alta geração.

Um dos princípios utilizados ao longo do projeto é que a inclusão de uma segunda condição torna o filtro mais específico. Dessa forma, os registros que apresentam simultaneamente consumo ou geração elevada e uma determinada condição ambiental ou operacional representam um subconjunto mais restrito dos dados. Essas relações são utilizadas para identificar padrões nos registros, sem considerar os resultados isolados como prova de falhas, desempenho superior ou causalidade.

Ao final, o projeto permite aplicar conceitos de análise exploratória de dados, estatística descritiva, filtragem de DataFrames e visualização, relacionando essas técnicas a situações práticas de monitoramento e gestão energética. Dessa forma, os dados são utilizados para transformar grandes conjuntos de registros em informações que podem auxiliar na compreensão do comportamento do consumo e da geração de energia.
