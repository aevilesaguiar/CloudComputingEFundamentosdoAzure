# Descrever os principais componentes da arquitetura do Azure

## Objetivos de aprendizagem
Depois de concluir este módulo, você poderá descrever os benefícios e o uso destes serviços:

-Assinaturas e grupos de gerenciamento do Azure.
-Grupos de recursos, recursos do Azure e Azure Resource Manager.
-Regiões, pares de regiões e zonas de disponibilidade do Azure.

## Regiões do Azure, zonas de disponibilidade e pares de regiões

Na unidade anterior, você aprendeu sobre os recursos e os grupos de recursos do Azure. Os recursos são criados em regiões, que são diferentes localizações geográficas no mundo inteiro que contêm datacenters do Azure.

## O que é uma zona de disponibilidade?

Zonas de disponibilidade são datacenters separados fisicamente dentro de uma região do Azure. Cada zona de disponibilidade é composta de um ou mais datacenters equipados com energia, resfriamento e rede independentes. Uma zona de disponibilidade é configurada para ser um limite de isolamento. Se uma zona ficar inativa, as outras continuarão funcionando. Zonas de disponibilidade são conectadas por meio de redes de fibra óptica privadas de alta velocidade.

As zonas de disponibilidade são destinadas, principalmente, a VMs, discos gerenciados, balanceadores de carga e bancos de dados SQL. Os serviços do Azure que dão suporte às zonas de disponibilidade enquadram-se em três categorias:

- Serviços em zonas: você fixa o recurso a uma zona específica (por exemplo, VMs, discos gerenciados, endereços IP).
-  Serviços com redundância de zona: a plataforma replica automaticamente entre zonas (por exemplo, armazenamento com redundância de zona, Banco de Dados SQL).
- Serviços não regionais: os serviços estão sempre disponíveis em geografias do Azure e são resilientes a interrupções em toda a zona, bem como a interrupções em toda a região.

# Recursos do Azure e Azure Resource Manager

- Recurso: um item gerenciável disponibilizado por meio do Azure. VMs (máquinas virtuais), contas de armazenamento, aplicativos Web, bancos de dados e redes virtuais são exemplos de recursos.
- Grupo de recursos: um contêiner que armazena os recursos relacionados de uma solução do Azure. O grupo de recursos inclui os recursos que você deseja gerenciar como um grupo. Você decide quais recursos pertencem a um grupo de recursos com base no que faz mais sentido para sua organização.

# Azure Resource Manager

O Azure Resource Manager é p serviço de implantação e gerenciamento do Azure. Ele fornece uma camada de gerenciamento que lhe permite criar, atualizar e excluir recursos em sua conta do Azure. Você usa recursos de gerenciamento como controle de acesso, bloqueios e marcas para proteger e organizar seus recursos após a implantação.

Quando um usuário envia uma solicitação de ferramentas, APIs ou SDKs do Azure, o Resource Manager recebe a solicitação. Ele autentica e autoriza a solicitação. O Resource Manager envia a solicitação para o serviço do Azure, que executa a ação solicitada. Como todas as solicitações são manipuladas por meio da mesma API, você verá funcionalidades e resultados uniformes em todas as diferentes ferramentas.


https://docs.microsoft.com/pt-br/learn/modules/azure-architecture-fundamentals/management-groups-subscriptions

https://portal.azure.com/?Microsoft_Azure_Education_correlationId=5e93c9500fa448f4baacc6ae84029e43#blade/Microsoft_Azure_Education/EducationMenuBlade/jobRole