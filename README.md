☁️ Microsoft Azure — Guia de Serviços de Computação
💻 Serviços de Computação no Azure

O Microsoft Azure oferece uma gama completa de serviços de computação que permitem a criação, gestão e escalabilidade de aplicativos e máquinas virtuais. Esses serviços ajudam empresas a rodar desde aplicações simples até ambientes corporativos completos com alta disponibilidade e segurança.
🖥️ Máquinas Virtuais (VMs)

As Máquinas Virtuais do Azure são instâncias de computação sob demanda. Elas permitem que você execute sistemas operacionais completos (Windows ou Linux) sem necessidade de adquirir hardware físico, suportando desde testes de software até ambientes de produção robustos.

Principais características:

    Escalabilidade horizontal.

    Diversos tamanhos e famílias (ex: B, D, E, F, N-series).

    Integração com discos gerenciados, redes virtuais e segurança.

⚡ Conjunto de Disponibilidade (Availability Set)

O Conjunto de Disponibilidade é um recurso que garante alta disponibilidade para as máquinas virtuais. Ele distribui VMs em:

    Domínios de Falha (Fault Domains): isola falhas físicas.

    Domínios de Atualização (Update Domains): distribui atualizações automáticas.

Isso minimiza o risco de downtime em casos de falhas físicas ou manutenções programadas, sendo essencial para workloads de missão crítica.
📈 Criação de Várias Máquinas

Para criar várias VMs de forma automática e gerenciada, o Azure oferece:

    Escalas de Máquinas Virtuais (VM Scale Sets): Permite a criação e gerenciamento centralizado de grupos de máquinas virtuais idênticas, que podem escalar automaticamente com base na demanda.

🗺️ Área de Controle Virtual

O Azure Virtual Network (VNet) é o serviço que fornece:

    Redes privadas isoladas.

    Comunicação segura entre recursos do Azure.

    Integração com VPNs, firewalls e sub-redes.

Com ele, você pode simular topologias de rede completas e conectar recursos como se estivessem em uma rede física, garantindo segurança e controle.
🐳 Conteinerização no Azure

O Azure oferece suporte nativo para containers através de:

    Azure Kubernetes Service (AKS) para orquestração.

    Azure Container Instances (ACI) para execução rápida sem infraestrutura de VM.

Isso permite desenvolver, testar e rodar aplicativos containerizados com escalabilidade e portabilidade.
⚙️ Azure Functions

Azure Functions é o serviço de computação serverless do Azure.
Você pode executar código sob demanda sem necessidade de gerenciar servidores.

Principais benefícios:

    Escala automática.

    Pagamento por execução.

    Ideal para automação, integração de sistemas e microserviços.

🌐 Serviços de Aplicativo do Azure

O Azure App Service é uma plataforma para hospedar aplicações Web, APIs RESTful e backends móveis com suporte a:

    .NET, Java, PHP, Python e Node.js.

    Integração contínua com Azure DevOps e GitHub.

    Autoescala e balanceamento de carga embutidos.

🔒 Azure VPN Gateway

O Azure VPN Gateway permite criar conexões seguras entre redes locais e a nuvem Azure via túneis IPsec/IKE.

Funciona para:

    Expandir datacenters locais.

    Conectar filiais.

    Garantir comunicação segura entre redes virtuais no Azure.
