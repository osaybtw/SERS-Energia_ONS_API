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
