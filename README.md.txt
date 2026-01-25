RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 25 de Janeiro de 2026

Empresa: Abstergo Industries

Responsável: [Seu Nome Completo]

Introdução
Este relatório detalha a implementação estratégica de soluções em nuvem na Abstergo Industries, com foco em otimização operacional e financeira. O objetivo central foi selecionar e configurar três serviços da AWS que permitem uma redução imediata de custos, sem comprometer a segurança ou a performance da infraestrutura.

Descrição do Projeto
A estratégia foi dividida em três pilares essenciais: controle de acesso, proteção de recursos e monitoramento inteligente. Abaixo, detalho cada etapa:

Etapa 1: Gestão de Identidade e Economia Operacional
Ferramenta: AWS IAM (Identity and Access Management)

Foco: Controle de acesso granular e segurança de privilégio mínimo.

Caso de Uso: Implementação de políticas que garantem que usuários e serviços tenham apenas as permissões necessárias. Isso evita custos gerados por provisionamento acidental de recursos caros por usuários não autorizados e reduz o risco de incidentes de segurança que poderiam causar prejuízos financeiros.

Etapa 2: Proteção de Instâncias e Eficiência de Rede
Ferramenta: Security Groups

Foco: Firewall virtual para instâncias EC2.

Caso de Uso: Configuração de regras de entrada e saída para filtrar o tráfego das instâncias. Ao restringir o acesso apenas ao tráfego legítimo, reduzimos o processamento desnecessário e protegemos os dados, evitando gastos com transferência de dados (Data Transfer Out) mal-intencionada ou tráfego de botnets.

Etapa 3: Monitoramento e Visibilidade de Gastos
Ferramenta: AWS CloudWatch

Foco: Monitoramento de recursos e aplicações em tempo real.

Caso de Uso: Criação de alarmes e dashboards para monitorar o uso de CPU e memória. Com o CloudWatch, identificamos instâncias ociosas ou subutilizadas ("underutilized"), permitindo o desligamento ou o redimensionamento (rightsizing) desses recursos para cortar custos de faturamento imediato.

Conclusão
A implementação dessas ferramentas na Abstergo Industries traz como benefício direto uma infraestrutura mais enxuta e segura. Esperamos uma redução significativa no desperdício de recursos e uma maior previsibilidade financeira. A continuidade dessas práticas, aliada à exploração de novas tecnologias de automação, garantirá que a empresa mantenha sua competitividade tecnológica com o melhor custo-benefício possível.

Anexos
Manual de Boas Práticas AWS IAM

Configuração Padrão de Security Groups (Tier Web/DB)

Relatório de Métricas Iniciais do CloudWatch

Assinatura do Responsável pelo Projeto:

Vitor Gabriel