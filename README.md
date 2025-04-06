# Resumo inicial: Cloud DIO
## ☁️O que é a nuvem?
Nuvem é uma rede de servidores remotos extensa que disponibiliza recursos como armazenamento e infraestrutura pela internet.
## Quais são os modelos de nuvem?
- Nuvem pública: Serviços e recursos são oferecidos por uma empresa terceirizada;
- Nuvem privada: Serviços e recursos são hospedados na infraestrutura da própia empresa;
- Nuvem híbrida: Combina os 2 outros modelos de nuvem.
## Quais as principais vantagens da nuvem?
- Economia de recursos financeiros em determinados cenários;
- Escalabilidade;
- Elasticidade;
- Segurança;
- Confiabilidade;
- Governança;
- Disponibilidade.
## Diferentes serviços disponíveis:
- Iaas - Infraestrutura como serviço;
- Paas - Plataforma como serviço;
- Saas - Software como serviço.
## Responsabilidade compartilhada:
- On premise (local) - A responsabilidade é total do cliente;
- Iaas - Dos serviços disponíveis é a que o cliente tem mais poder;
- Paas - A infraestrutura é provida pelaa empresa, é recomendado para desenvolvimento de softwares e implementação de bando de dados;
- Saas - Contrata um software para uso;
## Questões de localização:
Para oferecer serviços com menor latência, as empresas fornecem servidores em diferentes lugares do mundo:
- Existem as regions que contém as zones;
- Quanto mais perto a zone, melhor será a eficiência.
## Principais empresas fornecedoras de serviços de nuvem:
- Microsoft Azure;
- Oracle;
- Amazon Web Services;
- Google Cloud Platform.
### Empresas definem contrato SLA com o cliente que define a obrigatoriedade da disponibilidade do serviço em porcentagem quanto ao tempo de uso.
## Microsoft Entra ID - Protocolos de autenticação
- Autenticação (os funcionários entram para acessar os recursos);
- Logon único (SSO);
- Gerenciamneto de aplicativos;
- Negócios para Negócios (B2B);
- Gerenciamento de dispositivos.
## Microsoft Entra Domain Services
Sincroniza os usuários do ambiente on-premise para a rede virutal, mas não vice-versa
### Benefícios:
- Beneficia dos serviços de domínio baseados em nuvem sem gerenciar os controladores de domínio;
- Execute aplicativos herdados (que não podem utilizar os padrões de autenticação modernos) na nuvem.
## Diferença entre autenticação e autorização:
### Autenticação:
- Identifica a pessoa ou serviço buscando acesso a um recurso
- Solicita credenciais de acesso legítimo
- Base para criar princípios de identidade e controle de acesso seguros
### Autorização:
- Determina o nível de acesso de uma pessoa ou serviço autenticado;
- Define quais dados eles podem acessar e o que podem fazer com eles.
## Autenticação multifator:
Fornece segurança adicional para as identidades, exigindo mais de um elemento para autenticação completa.
Segue: Algo que você sabe <-> Algo que você possui <-> Algo que você é
## Colaboração B2B do Microsoft Entra External ID
Utiliza a identidade já existente de um parceiro, fornecedor ou outro colaborador para fazer a autenticação.
## B2C do Identidades Externas do Azure AD (Business to Customer)
Consumidores do seu aplicativo publicado utilizam cadastro feito em outros serviços para autenticação.
## Acesso Condicional
- Associação de usuário ou grupo;
- Local do IP;
- Dispositivo;
- Aplicativo;
- Detecção de risco.
## Controle de acesso baseado em função (RBAC)
- Gerenciamento de acesso de granularidade fina;
- Divida as tarefas dentro da equipe e conceda somente a quantidade de acesso de que os usuários precisam para trabalhar;
- Habilite o acesso ao portal do Azure e o controle de acesso aos recursos.
## Confiança Zero
- Proteja os ativos onde eles estiverem com a Confiança Zero.
Oferece proteção completa:
- Segurança física > Identidade e acesso > Perímetro > Rede > Computação > Aplicativo > Dados.
- Abordagem em camadas para proteger sistemas;
- Fornece diversos níveis de proteção;
- Ataques contra uma camada são isolados das camadas subsequentes.
### Microsoft Defender for Cloud é um serviço de monitoramento que fornece proteção contra ameaças nos datacenters do Azure e locais. Também faz comunicação para ambiente da AWS e GCP, ajuda a transparecer a situação de segurança e sugere medidas e melhorias.
## Recursos de segurança do Azure:
- Fornece recomendações de segurança;
- Detecta e bloqueia malware;
- Analisa e identifica ataques potenciais;
- Controla os acessos just-intime para portas. 
