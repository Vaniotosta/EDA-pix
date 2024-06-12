# Análise Exploratória  de Usuários de Chaves PIX
# Problema de Negócio

O PIX é um sistema de pagamentos instantâneos desenvolvido pelo Banco Central do Brasil, Ele revolucionou a forma como pessoas e empresas realizam transações financeiras, permitindo transferências e pagamentos em tempo real, 24 horas por dia, sete dias por semana, de maneira rápida, segura e praticamente gratuita.

Com a adoção massiva do PIX, uma grande quantidade de dados sobre chaves registradas foi gerada. Essas chaves são elementos essenciais do sistema, podendo ser CPF, CNPJ, número de telefone, e-mail ou uma chave aleatória, que identificam a conta do usuário. A análise desses dados oferece uma visão valiosa sobre o uso do PIX e ajuda a responder a várias perguntas de negócio cruciais para instituições financeiras, reguladores e analistas de mercado.

Nesta análise, exploramos as seguintes questões de negócio relacionadas ao registro de chaves PIX:

Quantas chaves PIX são registradas por cada instituição?

Objetivo: Identificar quais instituições financeiras possuem o maior número de chaves registradas. Isso ajuda a entender a penetração e a popularidade do PIX entre diferentes bancos e instituições de pagamento.
Qual é a distribuição de chaves PIX por tipo de chave (TipoChave)?

Objetivo: Analisar quais tipos de chave (CPF, CNPJ, telefone, e-mail, chave aleatória) são mais populares entre os usuários. Essa informação pode ser usada para direcionar estratégias de marketing e melhorar a experiência do usuário.
Quantidade total de chaves cadastrada por instituição?

Objetivo: Avaliar o desempenho de cada instituição financeira na adoção do PIX, destacando aquelas que lideram em termos de quantidade total de chaves cadastradas.
Quais são os picos e quedas no registro de chaves PIX por dia?

Objetivo: Identificar padrões sazonais e eventuais eventos que influenciam o registro de chaves. Esta análise pode revelar o impacto de campanhas de marketing, mudanças regulatórias ou outros fatores externos.
Top 50 em cadastramento de chaves por natureza (NaturezaUsuario)

Objetivo: Examinar quais são as principais instituições em termos de número de chaves cadastradas, segmentadas por natureza do usuário (pessoa física ou jurídica). Isso fornece insights sobre a base de clientes e a estratégia de diferentes instituições.
Ao investigar essas questões, podemos obter uma compreensão mais profunda do comportamento dos usuários e da eficiência das instituições no ecossistema do PIX. Os resultados dessas análises são fundamentais para apoiar decisões estratégicas, otimizar operações e melhorar a satisfação do cliente.

# CONCLUSÕES
- Periodo analisado de 1 ano e 4 meses temos com tipos de chaves cadastrados: e-mail 25.411553%, Aleatória 25.201097% e Celular 24.823692%, essas preferências pode ser atrelado a questão da segurança das informações pessoais, haja visto que maioria dos cadastros são de pessoas fisicas com 95% das chaves cadastradas.  

- Aqui já percebe-se que a NU_PAGAMENTOS,CAIXA ECONOMICA E PICPAY, destaca-se em quantidade de chaves cadastrada isso pode ser devido a sua popularidade ou até mesmo campanha de marketing, mas tem que ser verificados

- O primeiro semestre são os periodos com maior chaves cadastradas, isso requer uma investigação pois pode ser por influência economica, existe aumento no mês 1 ao 5  e queda a partir de junho, existe uma sazonalidade de queda a partir de junho.

-  Os cadastros ocorreram sempre no final do mês a partir do dia 28 e  houve um pico de aumento de chaves cadastradas que se prolongou a partir do dia 29 , isso pode ser resultado de datas de pagamentos de proventos


-  
# Trabalhos futuros
- Estudo Longitudinal da Adoção: Realizar um estudo longitudinal para observar como a adoção do PIX evolui ao longo do tempo. Isso pode incluir análises detalhadas de como diferentes grupos demográficos (por idade, região, etc.) estão adotando o PIX.

- Engajamento do Usuário: Analisar o engajamento dos usuários com o PIX, como frequência de uso, valores médios transacionados, e tipos de transações mais comuns. Isso pode ajudar a identificar padrões de comportamento e oportunidades para aumentar o engajamento.

- Impacto nas Micro e Pequenas Empresas: Estudar como o PIX está impactando micro e pequenas empresas em termos de facilidade de recebimento de pagamentos, fluxo de caixa e custos operacionais.

- Análise de Fraudes e Segurança: Realizar uma análise detalhada dos incidentes de fraude e segurança relacionados ao PIX. Isso pode ajudar a identificar vulnerabilidades e desenvolver estratégias para mitigar riscos.
-  
