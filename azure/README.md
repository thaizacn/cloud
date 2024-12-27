![image](https://user-images.githubusercontent.com/77704621/236565464-1ace667e-2dba-4e4b-a3d7-2c447c9e227f.png)

# 🤍 Microsoft Azure Fundamentals

## 💫 O que é computação em nuvem?

É a entrega rápida de serviços computacionais. As a service.

- Escolher o que precisa, utilizar por 30 dias e pagar somente depois, por aquilo que você usou. Fazendo com que as empresas consigam expandir mais rápido.

## 👩‍💻 Três modelos:

**Nuvem pública:** Acesso a todos que tiverem cadastro para consumir os recursos da nuvem. Fornece recursos e serviços a várias organizações e usuários, sem distinção “da onde” vai ficar os produtos. Todos consumimos os produtos da mesma fonte.

**Nuvem privada:** A empresa cria um ambiente virtualizado para si, onde somente as pessoas da organização têm acesso. A nuvem é somente da empresa.

**Nuvem hibrida:** O melhor dos dois mundos. Mantemos os servidores físicos e também utilizamos a nuvem para aproveitar recursos computacionais. *Esse é o modelo mais utilizado.*

## 🌞 Considerações e benefícios da nuvem:

**Alta disponibilidade:** Tempo que o provedor garante que o serviço estará disponível. SLA, acordo de nível de serviço; e se por acaso o serviço ficar indisponível por mais tempo do que o previsto há reembolso.

**Tolerância a falhas:** Replicação de informações. Ainda que meu serviço ficar indisponível em uma “ponta” ele ainda funcionará, não deixando com que o cliente perceba essa indisponibilidade. O usuário não sente o problema.

**Escalabilidade:** Alterar recursos para atender uma demanda, ou seja, meu serviço será escalável. Aumento de recursos computacionais, como um disco, por uma necessidade. Continuando com o mesmo modelo, no máximo trocando uma “família da máquina”. Adequando o serviço para as novas necessidades.

**Elasticidade:** Conjuntos de máquinas, por exemplo, começamos com duas e conforme forem muito utilizados vamos aumentando, assim como quando forem menos utilizadas diminuímos. Assim como o elástico, podemos estender e voltar ao estado anterior.

**Alcance global:** Número grande de Data Centers e regiões. Tendo recursos em todos os continentes. 

**Capacidade de latência:** Link direto entre as regiões, tendo latência menor de comunicação entre as regiões.

**Agilidade:** Acessamos um portal onde já existem os recursos, compramos, personalizamos e em questão de segundos já temos acesso e saímos utilizando esse serviços

**Considerações sobre custo preditivo:** Despesas CapEx x OpEx

**Recuperação de desastre:** O ambiente precisa subir o ambiente em outra região, ou seja, replicar as máquinas a partir de alguma catástrofe que deixe tudo INDISPONÍVEL, nem mesmo o cliente consegue acessar. Nesse caso replicamos o servidor para outra região que tenha disponibilidade. 

**Segurança:** Os itens criados e configurados no modelo de nuvem possuem segurança de criptografia para garantir que ainda que algum dado seja capturado a criptografia não vale o esforço de “traduzir”.

## 🌀 Conceito de CapEx e OpEx:

Despesa de Capital (*CapEx*): Gasto inicial, você paga na frente. Você vai atrás do servidor, acerta valores, paga por ele, então recebe seu servidor, configura e libera o ambiente ao usuário fazendo as configurações finais.

Despesas operacionais(*OpEx*): Gasto pelo que foi usado. O pagamento é feito conforme o uso, 30 dias após a utilização do serviço.

## 👣 Serveless: (computação sem servidor)
É o modelo de computação em nuvem onde o provedor de serviços (Azure) é responsável por executar um pedeço de um código ou função, gerenciando todo o ambiente de execução. Nesse modelo pagamos somente pelo tempo de execução, a Azure escala automaticamente os serviços também. É ideal para cargas event-driven como processamento de eventos, APIs, IoT, etc..
- **Azure Functions**: Serviço para executar código sem a necessidade de infraestrutura dedicada, perfeito para aplicações event-driven.

## 🤓 Governança:

- **Microsoft Purview**: Proporciona uma visão abrangente e unificada dos dados de toda organização. Ajuda a mapear, classificar, rotular e gerenciar os ativos de dados, além de ajudar a cumprir regulamentos e padrões de conformidade (GDPR, HIPPA..)
- **Azure Policy**: Fornece governança e controle sobre os recursos. Ajuda a criar, atribuir e gerenciar politicas além de identificar, avaliar e mitigar riscos.
- **Bloqueio de Recursos**: Impede a exclusão ou modificação acidental de recursos críticos. Podem ser usados para atender políticas.
- **Assistente Azure**: Ferramenta de conversação integrada ao Portal Azure para ajudar o usuário a interagir com os serviços e recursos. Ela faz recomendações e orientações..
- **Integridade do Serviço do Azure**: Fornece informações sobre saúde e o status dos serviços. Realiza o monitoramento, notificação de acidentes, histórico de integridade, suporte para decisões etc.
- **Azure Resource Manager (ARM)**: Gerenciamento e orquestração de recursos no Azure.

## 🔐 Segurança e Compliance
- **Criptografia**: Todos os dados no Azure são protegidos por criptografia em repouso e em trânsito.
- **Azure Security Center**: Plataforma unificada para gerenciamento de segurança, oferecendo uma visão centralizada e alertas de segurança.
- **Compliance**: A Azure segue padrões e regulamentos globais como GDPR, ISO 27001, HIPAA, entre outros, garantindo segurança e conformidade dos dados.
- **Azure Sentinel**: Plataforma de SIEM (Security Information and Event Management) para monitoramento e resposta a incidentes de segurança.

## 👓 Gerenciamento de Identidade e Acesso
- **Azure Active Directory (AAD)**: Serviço de gerenciamento de identidade e autenticação que permite acesso controlado aos recursos do Azure.
- **Acesso Condicional**: Regras de acesso baseadas em condições, como localização ou estado de segurança do dispositivo.
- **Autenticação Multifator (MFA)**: Camada extra de segurança para proteger os recursos, exigindo mais de um método de verificação de identidade.

## 🔍 Ferramentas de Monitoramento
O Azure oferece diversas ferramentas para o monitoramento de recursos, aplicações e infraestrutura, permitindo uma gestão eficiente e a otimização de ambientes de TI na nuvem. Essas ferramentas são essenciais para garantir a alta disponibilidade, desempenho e segurança dos recursos no Azure.
- **Azure Monitor**: Monitoramento de desempenho e disponibilidade de recursos, incluindo logs e métricas.
- **Azure Application Insights**: Ferramenta para monitoramento de aplicações, oferecendo insights detalhados sobre o comportamento de usuários e desempenho.
- **Azure Log Analytics**: Análise de logs para identificar problemas, otimizar e monitorar a infraestrutura de TI.

## 🤔 Curiosidades Azure:

- A Azure oferece quatro modelos de suporte para seus clientes, e são esses: Básico(Gratuito), Desenvolvedor(U$29), Standard (U$100), Professional Direct (U$1000). O plano “professional direct” permite acesso a um engenheiro da Microsoft 24x7.
- Ao criar uma conta na Azure gratuita, o valor de crédito inicial é de U$200.
- O Brasil só tem uma zona de disponibilidade.
- Se você tem recursos distribuídos em diferentes regiões para uma mesma aplicação, isso pode causar lentidão e latência causando demora nos acessos.
- O functions possibilita rodar funções de código sem alocação direta de servidor, sendo transparente.
- Azure Insights tem o foco de monitoramento e alarmes e não para divisão de custos.
- Tags são elementos de metadados que você aplica aos recursos do Azure. Elas são pares de chave-valor que ajudam você a identificar recursos com base em configurações relevantes para sua organização.
- O Acesso Condicional é a ferramenta usada pelo Azure Active Directory para permitir (ou negar) o acesso a recursos com base em sinais de identidade. O acesso condicional é um método de MFA (autenticação multifator) mais refinado.

