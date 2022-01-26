# Discutir conceitos fundamentais do Azure
# Objetivos de aprendizagem
**Depois de concluir este módulo, você poderá:**
- Identificar os benefícios e as considerações do uso dos serviços de nuvem
- Descrever as diferenças entre as categorias de serviços de nuvem
- Descrever as diferenças entre os tipos de computação em nuvem
# Tipos de Mocelos de Nuvem

**O que são nuvens públicas, privadas e híbridas?**
Existem 3 modelos de implantação para computação em nuvem: publica, privada e híbrida.
- Na nuvem pública os seus serviços não oferecidos pela Internet pública e ficam disponíveis para qualquer pessoa que deseje comprá-los. Os recursos de nuvem, como servidores e armazenamento são se propriedade e operados por um provedor de serviços de nuvem de terceiros e entregues pela internet. Ao contrário das nuvens privadas, as nuvens públicas podem poupar as empresas dos enormes gastos de compra, gerenciamento e manutenção e hardware local e infraestrutura de aplicativo. No caso da nuvem pública, o provedor de serviços de nuvem é responsável por todo o gerenciamento e manutenção do sistema. As nuvens públicas também podem ser implantadas mais rápido do que infraestruturas locais e com uma plataforma quase infinitamente escalonável. Todos os funcionários de uma empresa podem utilizar o mesmo aplicativo de um escritório ou filial usando o dispositivo de sua escolha, contanto que tenham acesso à Internet. Embora algumas questões sobre segurança tenham sido levantadas em relação aos ambientes de nuvem pública, quando implantada corretamente, a nuvem pública pode ser tão segura quanto a implantação de uma nuvem privada com gerenciamento altamente eficaz caso o provedor utilize métodos adequados de segurança, como sistemas de prevenção e detecção de invasão (IDPS).
- Na nuvem privada consiste em em recursos de computação usados exclusivamente  por usuários de uma empresa ou organização. Um nuvem privada pode estar localizada fisicamente no datacenter(local) da organização ou ser hospedada por um provedor de serviços de terceiros.Dois modelos de serviços de nuvem podem ser utilizados em uma nuvem privada. O primeiro é a infraestrutura como serviço (IaaS), que permite que a empresa use recursos de infraestrutura, como computação, rede e armazenamento como serviço. O segundo é a plataforma como serviço (PaaS), que permite que a empresa faça de tudo, desde aplicativos simples baseados em nuvem até aplicativos empresariais sofisticados. As nuvens privadas também podem ser combinadas com nuvens públicas para criar uma nuvem híbrida, permitindo que as empresas usufruam de arrebentamento de nuvem para liberar mais espaço e dimensionar serviços de computação para nuvem pública mediante aumento da demanda de computação.

- Ja ná nuvem híhrida é um ambiente de computação que combina uma nuvem privada, permitindo que dados e aplicativos sejam compartilhados entre elas.

**Comparação de modelos de nuvem**

- Nuvem pública

  -Nenhuma despesa de capital para escalar verticalmente.
  -Os aplicativos podem ser provisionados e desprovisionados rapidamente.
  -As organizações pagam apenas pelo que utilizam.

- Nuvem privada

  -O hardware deve ser comprado para inicialização e manutenção.
  -As organizações têm controle total sobre os recursos e a segurança.
  -As organizações são responsáveis pela manutenção e pelas atualizações de hardware.

- Nuvem híbrida

  -Fornece a maior flexibilidade.
  -As organizações determinam onde executar seus aplicativos.
  -As organizações controlam a segurança, a conformidade ou os requisitos legais.
# considerações e os benefícios da nuvem

**Vantagens:**

- **Alta disponibilidade:** dependendo do SLA(CONTRATO DE NIVEL DE SERVIÇO)os aplicativos baseados em nuvem poderão oferecer uma experiência de usuário contínua, sem tempo de inatividade aparente.
- **Escalabilidade:** podem ser dimensionados ->
   - Verticalmente->para aumentar a capacidade de computação adicionando RAM ou CPUS a uma máquina virtual
   - Horizontalmente->aumenta a capacidade de computação adicionando instancias de recursos, adicionando VNS a configuração por exemplo
- **Elasticidade:**  pode configurar aplicativos baseados em nuvem para aproveitar o dimensionamento automático, fazendo com que os aplicativos tenham os recursos que precisem.
- **Agilidade:** implante e configure com rapidez recursos baseados em nuvem á medida que os requisitos de aplicativo mudarem.
- **Distribuição Geografica:** implantar aplicativos e dados em data centers regionais, garantindo o desempenho dos clientes
- **Recuperação de desastre:** serviços de backup baseados em nuvem 
 
**Há dois tipos diferentes de despesas que você deve considerar:**
- CapEx(despesas de capital): gastos antecipados de dinheiro com infraestrutura e posterior dedução ;
- OpEx(despesas operacionais): gastos atuais com serviços ou produtos que são cobrados no ato;

Obs: os serviços de nuvem são Opex devido ao seu modelo de consumo.Os provedores de serviço de nuvem operam em um modelo baseado em consumo, o que significa que os usuários finais só pagam pelos recursos que usam.

# Modelos de Serviço de Nuvem

**IaaS (Infraestrutura como Serviço):**esse serviço é o mais proximo do gerenciamento de servidores físicos, um provedor de nuvem manterá o hardware atualizado, mas a manutenção do SO e a configuração da rede fica a cargo do locatório. Sendo a categoria mais básica entre os tipos de computação em nuvem, a IaaS permite que você alugue uma infraestrutura de TI (servidores e máquinas virtuais, armazenamento, redes e sistemas operacionais) de um provedor de nuvem em uma base paga conforme o uso. Exemplos: teste e desenvolvimento, armazenamento, bacckup e recuperação, suporte a servidores de aplicativos web

**PaaS (Plataforma como Serviço):**Esse modelo de serviço de nuvem é um ambiente de hospedagem gerenciado. O provedor de nuvem gerencia as máquinas virtuais e os recursos de rede e o locatário de nuvem implanta seus aplicativos no ambiente de hospedagem gerenciado, é um ambiente de desenvolvimento e implantação completo na nuvem, com recursos que permitem a você fornecer tudo, de aplicativos simples baseados em nuvem a sofisticados aplicativos empresariais habilitados para a nuvem. Você adquire os recursos necessários por meio de um provedor de serviços de nuvem em uma base paga conforme o uso e os acessa por uma conexão com a Internet segura.

**SaaS (Software como Serviço):**Nesse modelo de serviço de nuvem, o provedor de nuvem gerencia todos os aspectos do ambiente de aplicativo, como as máquinas virtuais, os recursos de rede, o armazenamento de dados e os aplicativos. O locatário de nuvem só precisa fornecer seus dados para o aplicativo gerenciado pelo provedor de nuvem.Ele é baseado em
assinaturas.Ele sobrepôe todos os serviços como o IasS e o PaaS. Exemplo: serviços de e-mail  baseados na web como hotmail, mail e outros, CRM(GERENCIAMENTO DE RELACIONAMENTO COM CLIENTE), ERP(PLANEJAMENTO DE RECURSOS EMPRESARIAIS) e gerenciadores de documentos
# Computação Sem servidor(Serverless)

**O que é uma computação sem servidor?**
Eliminando a necessidade de gerenciar a infraestrutura, a computação sem servidor permite que os desenvolvedores criem aplicativos de forma mais rápida. Com aplicativos sem servidor, o provedor de serviços de nuvem provisiona, dimensiona e gerencia automaticamente a infraestrutura necessária para executar o código.Ao entender a definição da computação sem servidor, é importante observar que os servidores ainda executam o código. O nome sem servidor se deve ao fato de que as tarefas associadas ao provisionamento e ao gerenciamento da infraestrutura são invisíveis para o desenvolvedor. Essa abordagem permite que os desenvolvedores se concentrem mais na lógica comercial e ofereçam mais valor à parte principal dos negócios. A computação sem servidor ajuda as equipes a aumentar a produtividade e a colocar os produtos no mercado com rapidez, o que permite que as organizações otimizem melhor os recursos e mantenham o foco na inovação.

**Padrões de Aplicação sem servidor(Servless)**
-Funções sem servidor elas aceleram o desenvolvimento usando um modelo controlado por eventos.
-Kurbenets sem servidor, os devs trazem os seus proprios conteiners orquestrados pelo os Kurbenets
-Ambientes de aplicativo sem servidor , fluxos de trabalho sem servidor, é possivel integrar vários serviços na nuvem, sem precisar aprender novas apis ...
-Gateway de API sem servidor

## apontamento
O que é Kubernetes? O Kubernetes é um software open-source de orquestração para a implantação, o gerenciamento e a escala de contêineres.Conforme os aplicativos crescem para abranger vários contêineres implantados em vários servidores, operá-los torna-se mais complexo. Para gerenciar essa complexidade, o Kubernetes fornece uma API de software livre que controla como e em que local esses contêineres serão executados.

Um blob, é uma coleção de dados binários armazenados como uma única entidade em um sistema de gerenciamento de banco de dados. Blobs geralmente são objetos de imagem, áudio ou outro objetos multimedia, apesar de algumas vezes código binário executável ser armazenado como um blob.
## Referencias

[https://docs.microsoft.com/pt-br/learn/modules/fundamental-azure-concepts/introduction]

[https://azure.microsoft.com/pt-br/overview/types-of-cloud-computing/?WT.mc_id=javascript-10027-gllemos]

[https://azure.microsoft.com/pt-br/topic/what-is-kubernetes/]

[https://azure.microsoft.com/pt-br/overview/serverless-computing/]