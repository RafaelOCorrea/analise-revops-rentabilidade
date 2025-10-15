# analise-revops-rentabilidade
Diagnóstico estatístico (Média x Mediana) que identificou R$900k em prejuízo oculto em custos logísticos de vendas globais.

## I. Resumo Executivo: O Mic Drop Estatístico
A análise de rentabilidade de quatro anos de dados globais revelou uma discrepância crítica que mascara a verdadeira saúde da empresa: a Margem de Lucro Típica (Mediana) é de 17,0%, o que indica uma operação fundamentalmente saudável. No entanto, a Margem de Lucro Média (Real) despenca para apenas 5% em todos os segmentos.

Essa queda de 12 pontos percentuais é causada por um pequeno número de transações de prejuízo catastrófico (outliers), que, somadas, totalizam um prejuízo acumulado de mais de $900.000.

O diagnóstico é inequívoco: a falha principal não é de precificação, mas de Logística e Custo de Envio para produtos volumosos. A recomendação central é estabelecer a margem de 17,0% como piso financeiro e rever a política de frete para as subcategorias de alto risco, como Mesas (Tables), e para os mercados cronicamente deficitários de EMEA e África.

## II. Contexto e Objetivo de Negócio
A gestão de uma empresa de e-commerce global exige precisão na análise de rentabilidade. Com um histórico de dados transacionais abrangendo diversos mercados e segmentos, o objetivo deste estudo foi diagnosticar a causa-raiz do prejuízo acumulado de mais de $900.000, que corrói significativamente a margem de lucro típica da empresa.

A análise foi guiada por três perguntas estratégicas:  
1.	Onde está o Risco Oculto? Usar estatísticas robustas (Mediana) para separar a margem de lucro real e consistente do ruído causado por outliers de alto custo.
2.	Quem são os Vilões? Identificar as categorias e subcategorias de produtos que, apesar de gerarem receita, são as principais responsáveis pela destruição da margem.
3.	Qual o Plano de Ação? Isolar o perfil de cliente e a sazonalidade de maior risco para otimizar a política de custos logísticos de forma cirúrgica.

## III. O Diagnóstico: Onde Está o Lucro e o Risco?
### Análise da Curva ABC (Volume de Lucro)
A análise preliminar, baseada no Lucro Total Acumulado, posiciona as três categorias de produtos como os principais motores de receita. O gráfico demonstra que Technology é a categoria mais importante em volume de lucro. Esta visão, no entanto, é superficial e pode gerar uma falsa sensação de segurança, pois o lucro total (a soma de ganhos e perdas) mascara as transações deficitárias que contaminam a margem.

<img width="1090" height="685" alt="Lucro Total por Categoria de Produto" src="https://github.com/user-attachments/assets/77849876-0412-4fb1-9d9d-62a2963050a7" />

### A Realidade Estatística: Margem Típica vs. Margem Real
Para entender a verdadeira eficiência da operação, utilizamos um diagnóstico estatístico que compara a Mediana (margem típica) com a Média (margem real). O gráfico de barras agrupadas a seguir é a prova da falha crítica no gerenciamento de custos:  
•	Em todos os segmentos, a Margem Mediana (Barra Azul) é de 17,0%, provando que 50% dos pedidos são altamente saudáveis.
•	No entanto, a Margem Média (Barra Laranja) despenca para aproximadamente 5%.
Essa queda brusca é a prova visual de que o problema não é a precificação de base, mas sim um pequeno número de transações de prejuízo catastrófico (outliers) que contamina a rentabilidade de toda a empresa.

<img width="1090" height="698" alt="Discrepancia Estatistica: Margem Mediana vs Média por seguimento" src="https://github.com/user-attachments/assets/95f24ddc-2a41-4081-a58f-4333cef8820a" />

## IV. Causa Raiz: O Custo de Ser Grande
Comprovada a discrepância estatística, o foco se move para identificar as transações pontuais que aniquilam a margem.

### Localizando o Prejuízo no Nível do Produto
O gráfico de Prejuízo Médio por Transação Deficitária revela os verdadeiros "vilões" do catálogo. O problema está concentrado em itens de alto volume ou difícil manuseio. As subcategorias tables, machines, appliances, bookcases e copiers lideram o ranking (5) de prejuízo por pedido. Um único pedido de Mesa, por exemplo, gera um prejuízo médio de $290,57.

<img width="1090" height="904" alt="Prejuizo Médio por Transação Deficitária" src="https://github.com/user-attachments/assets/0819ff31-ec2b-42d0-912f-da3c32418e28" />

### A Prova Logística e Geográfica
O que Mesas, Copiadoras e o alto prejuízo têm em comum? Logística e o Mercado de Destino. A análise do Custo Médio de Envio em Pedidos com Prejuízo confirma que o frete para um pedido problemático de Mesa é de $124,15.

Além disso, o problema de custos atinge de forma desigual os mercados globais: enquanto Canadá e EUA são saudáveis, os mercados de EMEA (−14%) e África (−15%) operam com prejuízo médio crônico. Essa perda indica que o custo de envio internacional é insustentável nessas regiões.

<img width="1090" height="779" alt="Custo Médio de Pedidos em Envios com Prejuízo" src="https://github.com/user-attachments/assets/e05f3716-dcd5-46a1-bf65-f177672999d9" />

<img width="1090" height="687" alt="Margem Média de Lucro por Mercado Global" src="https://github.com/user-attachments/assets/89833f41-4454-4a99-8af0-a5583658c4bc" />

<img width="1090" height="952" alt="Risco Financeiro: Prejuízo Total por Segmento de Cliente" src="https://github.com/user-attachments/assets/ae0fe038-8b99-44e3-a03e-3273ab828a30" />

<img width="1090" height="541" alt="Sazonalidade do Resultado (Lucro x Prejuízo) Mês a Mês" src="https://github.com/user-attachments/assets/7514e3b1-35c5-4748-806a-554b533dea22" />

## V. Risco, Sazonalidade e Cliente Vulnerável
O risco não é constante. Ele se concentra no segmento Consumer e em períodos específicos do ano.

### O Risco Concentrado e Sazonal

A análise do Prejuízo Total Acumulado por Segmento revela que, apesar de ser o maior em volume de Lucro, o segmento Consumer também concentra a maior fatia do prejuízo. O gráfico de Sazonalidade do Resultado (Lucro vs. Prejuízo) mostra que a exposição ao risco aumenta em períodos previsíveis: a linha de Prejuízo (vermelha) tem picos recorrentes no final de cada ano (novembro/dezembro), coincidindo com períodos de alta pressão promocional, como Black Friday e Natal, onde descontos agressivos se somam aos já elevados custos logísticos para gerar perdas.

## VI- Recomendações Estratégicas: Um Plano de Ação Cirúrgico
A falha na gestão de custos em operações de alto risco requer um plano de ataque imediato. A discrepância estatística (Margem Mediana de 17,0% vs. Média de 5%) exige que a empresa se blinde contra transações de alto prejuízo, atacando o problema em três frentes: produto, geografia e política financeira.

A. Blindagem Contra o Risco Logístico e de Produto
O primeiro passo é neutralizar os produtos que destroem a margem. Nossa análise recomenda criar um "Alerta Vermelho" para as subcategorias Tables (Mesas), Copiers (Copiadoras) e Bookcases (Estantes). O foco prioritário deve ser a eliminação do prejuízo médio de $290,57 por transação deficitária de Mesas. A política de frete deve ser revista imediatamente para esses itens volumosos, com duas opções: renegociar o frete com transportadoras ou implementar uma política de repasse do custo real de envio ao cliente.

B. Otimização Geográfica e Sazonal do Risco
O risco financeiro deve ser gerenciado de forma inteligente. Sugerimos a implementação de uma política de preços dinâmica e controle de descontos nos mercados de EMEA e África, que operam cronicamente no prejuízo (margem média ∼−15%). Essa restrição deve ser intensificada para o Segmento Consumer durante o Quarto Trimestre (Novembro/Dezembro). Nesses períodos, a empresa deve reavaliar a venda de produtos de "Alerta Vermelho" nesses mercados de risco, já que a combinação de alto custo logístico e desconto máximo gera perdas explosivas.

C. Estabelecimento de um Piso Financeiro Inegociável
Para garantir a rentabilidade futura, a Margem Mediana de 17,0% deve ser estabelecida como o novo piso de aceitação para a saúde financeira da empresa. Recomenda-se a implementação de uma regra de negócio automatizada no sistema de precificação que alerte ou bloqueie qualquer transação cuja margem projetada caia abaixo de 17,0%. Essa medida de controle garantirá que a empresa só aceite transações tipicamente rentáveis, blindando-a contra a repetição dos outliers que corroeram ~$900.000 em lucros.
