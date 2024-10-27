# resumo-do-lab11
"Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO - Construindo Arquiteturas no Azure ".

Construindo Arquiteturas no Azure: Componentes de Arquitetura do Azure
A arquitetura do Azure é composta por diversos serviços e componentes que se integram para criar soluções eficientes e flexíveis. Aqui estão alguns dos principais componentes:

Regiões do Azure:

As regiões são localizações geográficas onde os datacenters do Azure estão localizados. Cada região é uma coleção de datacenters que fornece redundância e baixa latência. Ao escolher uma região, é importante considerar a proximidade dos usuários e a conformidade com as regulamentações locais.
Zonas de Disponibilidade:

São conjuntos de datacenters dentro de uma região. Cada zona de disponibilidade é isolada das outras, oferecendo proteção contra falhas de hardware e fornecendo alta disponibilidade. Isso é crucial para aplicações que exigem uptime contínuo.
Datacenters:

Estruturas físicas que abrigam servidores, armazenamento e outros recursos. Os datacenters do Azure são projetados para escalar e suportar a demanda de serviços de nuvem, garantindo eficiência energética e segurança.
Grupos de Recursos:

Uma coleção lógica de recursos do Azure que compartilham o mesmo ciclo de vida e são gerenciados juntos. Os grupos de recursos facilitam a organização, controle de acesso e gerenciamento de custos dos recursos do Azure.
Assinaturas:

Representam um acordo com a Microsoft que permite o uso dos serviços do Azure. As assinaturas ajudam a gerenciar o faturamento e o acesso aos serviços. Uma organização pode ter várias assinaturas para separar diferentes ambientes (como desenvolvimento, teste e produção).
Grupos de Gerenciamento:

Permitem que você organize e gerencie várias assinaturas de forma hierárquica. Isso é útil para aplicar políticas e controle de acesso em um conjunto de assinaturas, simplificando a governança em larga escala.
Rede Virtual (VNet):

Proporciona um ambiente de rede isolado onde você pode provisionar recursos do Azure. As VNets permitem a comunicação segura entre os recursos e podem se conectar a redes locais através de VPNs.
Serviços de Computação:

Incluem máquinas virtuais (VMs), contêineres e funções do Azure, que oferecem diferentes níveis de abstração para executar aplicativos e cargas de trabalho.
Armazenamento:

O Azure fornece várias opções de armazenamento, como blobs, filas, tabelas e discos, permitindo que você escolha a melhor solução com base em requisitos de desempenho, custo e tipo de dados.
Serviços de Aplicação:

Incluem serviços gerenciados para hospedar aplicações web, APIs, e aplicativos móveis. Exemplos são o Azure App Service e Azure Kubernetes Service (AKS).


Construir uma arquitetura no Azure envolve compreender e utilizar esses componentes de forma integrada para atender às necessidades de desempenho, segurança e escalabilidade. A escolha adequada de regiões, zonas de disponibilidade e recursos permite criar soluções robustas que suportam a continuidade dos negócios e a satisfação dos usuários. Ao projetar uma arquitetura no Azure, é crucial considerar fatores como redundância, recuperação de desastres e governança, para garantir que a solução atenda tanto aos requisitos técnicos quanto aos objetivos de negócio.
