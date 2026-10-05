# 📊 Relatório Executivo: Diagnóstico de Churn no ERP SaaS

##Ferramentas Utilizadas: Python, Pandas (para ETL e manipulação), Matplotlib/Seaborn (para Data Viz)

1. O Perfil de Maior Risco (Quem cancela?)
Identificamos que 100% da evasão está concentrada em Micro e Pequenas Empresas (MPEs), com destaque negativo para estruturas enxutas (até 5 funcionários) e sem quadro societário complexo (apenas um dono).

2. A Raiz do Problema (Por que cancelam?)

Baixa Adoção de Produto (Engajamento): Os gráficos de utilização de features mostram que a grande maioria dos clientes que cancelam fazia "Pouco Uso" dos módulos centrais do sistema (Financeiro, Vendas e Integração Bancária). O cliente não enxerga valor na ferramenta porque não chegou a implementá-la direito na sua rotina.

Falta de Retenção Contratual: O plano "Mês-a-mês" lidera esmagadoramente os cancelamentos. Sem o compromisso de um contrato longo, qualquer fricção no uso gera um cancelamento imediato.

Fricção de Pagamento (Churn Involuntário): Há um volume altíssimo de cancelamentos atrelados ao pagamento via "Boleto - pagamento único", indicando que muitos cancelamentos ocorrem por inadimplência acidental ou esquecimento da data de vencimento.

3. Plano de Ação Recomendado (Próximos Passos)

Campanha de Migração de Pagamento e Contrato: Criar incentivos financeiros (ex: 15% de desconto no primeiro ano) para clientes que migrarem do plano mensal no boleto para o plano anual no Cartão de Crédito. Isso ataca simultaneamente o churn involuntário e aumenta o tempo de vida do cliente (LTV).

Reestruturação do Onboarding: Como o problema é a falta de uso dos módulos, a equipe de Sucesso do Cliente (CS) precisa focar em treinar intensivamente as microempresas nos primeiros 30 dias, garantindo que elas cadastrem seus produtos e emitam as primeiras notas fiscais.

Downsell Estratégico: Desenvolver uma versão "Lite" (mais barata e com menos funções) exclusiva para empresas de até 5 funcionários, retendo esse cliente na base até que ele cresça.
