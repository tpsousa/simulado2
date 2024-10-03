# simulado2

O seu ambiente Azure contém várias máquinas virtuais Azure.
Você precisa garantir que uma máquina virtual chamada VM1 possa ser acessada pela Internet por HTTP.
Solução: você modifica um DDoS
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Modificar um DDoS (Distributed Denial of Service) não é a solução correta para garantir que a máquina virtual VM1 possa ser acessada pela Internet por HTTP. Para permitir o acesso HTTP à VM1, você precisaria configurar regras de segurança apropriadas no grupo de segurança de rede (NSG) associado à VM, permitindo tráfego na porta 80 (que é a porta padrão para HTTP). Além disso, garantir que a VM tenha um endereço IP público também é necessário.






Você disse:
Para implementar um modelo de nuvem híbrida, uma empresa deve sempre migrar do modelo de nuvem privada.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Para implementar um modelo de nuvem híbrida, uma empresa não precisa sempre migrar de uma nuvem privada. A nuvem híbrida pode ser criada a partir de uma combinação de nuvem pública e nuvem privada, e uma empresa pode optar por integrar serviços existentes de nuvem pública com novos recursos em uma nuvem privada ou vice-versa. Portanto, não é necessário migrar do modelo de nuvem privada para implementar uma nuvem híbrida.






Você disse:
Um administrador do Azure planeja executar um script do PowerShell que cria recursos do Azure.
Você precisa recomendar qual configuração de computador usar para executar o script.
Solução: execute o script em um computador que execute macOS e tenha o PowerShell Core 6.0 instalado.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Executar o script do PowerShell em um computador que tenha o PowerShell Core 6.0 instalado no macOS atende ao objetivo, pois o PowerShell Core é uma versão multiplataforma do PowerShell que pode ser executada em diferentes sistemas operacionais, incluindo macOS. Portanto, essa configuração é adequada para criar recursos do Azure usando um script do PowerShell.






Você disse:
Se você criar duas máquinas virtuais do Azure que usam o tamanho B2S, cada máquina virtual gerará sempre o mesmo custo mensal.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Embora as máquinas virtuais do Azure que usam o mesmo tamanho (como B2S) tenham um custo base por hora semelhante, o custo mensal total pode variar devido a fatores como:

Uso de Recursos: Se uma máquina virtual é usada mais intensamente que a outra (por exemplo, com maior utilização de CPU ou disco), isso pode influenciar custos adicionais, como os de armazenamento ou transferência de dados.

Configurações de Rede e Armazenamento: Custos adicionais podem ser incorridos dependendo do tipo de disco (SSD vs. HDD) ou da configuração de rede (por exemplo, IPs públicos, balanceadores de carga).

Zonas de Disponibilidade: A implantação em diferentes regiões ou zonas pode resultar em variações de preço.

Portanto, mesmo que ambas as máquinas virtuais sejam do mesmo tamanho, os custos mensais podem não ser sempre os mesmos.






Você disse:
Você planeja implantar várias máquinas virtuais do Azure.
Você precisa garantir que os serviços em execução nas máquinas virtuais estejam disponíveis caso um único data center falhe.
Solução: você implanta as máquinas virtuais em dois ou mais conjuntos de dimensionamento.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Implantar máquinas virtuais do Azure em dois ou mais conjuntos de dimensionamento (scale sets) ajuda a garantir alta disponibilidade. Se um data center falhar, as máquinas virtuais em outro data center ainda estarão disponíveis, permitindo que os serviços continuem funcionando. Os conjuntos de dimensionamento podem ser configurados para distribuir automaticamente as instâncias de máquina virtual entre diferentes zonas de disponibilidade, o que oferece resiliência contra falhas em um único data center. Portanto, essa solução atende ao objetivo de manter os serviços disponíveis em caso de falha de um data center.






Você disse:
Pergunta 6 de 42
No Azure Service Health, um administrador pode criar uma regra para ser alertado se um serviço do Azure falhar.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

No Azure Service Health, os administradores podem criar regras de alerta para serem notificados sobre eventos de saúde de serviços do Azure, como interrupções ou degradações de serviço. Isso permite que os administradores fiquem informados sobre a saúde dos serviços que utilizam e tomem medidas proativas para mitigar qualquer impacto em suas operações. Portanto, a afirmação é verdadeira.






Você disse:
Pergunta 7 de 42
O Azure Advisor fornece recomendações sobre como configurar a rede em máquinas virtuais do Azure.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

O Azure Advisor fornece recomendações personalizadas sobre as melhores práticas para otimizar seus recursos do Azure, incluindo sugestões sobre configuração de rede em máquinas virtuais. Ele analisa suas configurações e o uso dos recursos, oferecendo orientações para melhorar a eficiência, segurança e desempenho da sua infraestrutura no Azure. Portanto, a afirmação é verdadeira.






Você disse:
Um grupo de recursos pode conter recursos de várias regiões do Azure.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Um grupo de recursos no Azure é limitado a conter recursos que estão na mesma região. Embora você possa criar grupos de recursos em várias regiões, cada grupo de recursos específico só pode incluir recursos que pertencem àquela única região. Portanto, a afirmação é falsa.






Você disse:
Identidades armazenadas no Azure Active Directory (Azure AD), serviços de nuvem de terceiros e Active Directory local podem ser usadas para acessar recursos do Azure.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Identidades armazenadas no Azure Active Directory (Azure AD), serviços de nuvem de terceiros e Active Directory local podem ser usadas para acessar recursos do Azure. O Azure AD permite a integração de identidades de várias fontes, permitindo uma gestão unificada de acesso a recursos do Azure.






Você disse:
A sua empresa planeia migrar todos os seus dados e recursos para o Azure. O plano de migração da empresa afirma que apenas soluções de plataforma como serviço (PaaS) devem ser usadas no Azure.
Você precisa implantar um ambiente do Azure que dê suporte à migração planejada.
Solução: você cria um serviço de aplicativo do Azure e contas de armazenamento do Azure.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Criar um serviço de aplicativo do Azure e contas de armazenamento do Azure atende ao objetivo de implementar um ambiente no Azure que suporte a migração planejada, utilizando soluções de Plataforma como Serviço (PaaS). O serviço de aplicativo é uma solução PaaS que permite desenvolver, implantar e dimensionar aplicativos web e serviços. As contas de armazenamento do Azure também são uma parte importante para armazenar dados de forma escalável na nuvem.






Você disse:
A autorização para acessar aos recursos do Azure só pode ser fornecida aos utilizadores do Azure Ative Directory (Azure AD).
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

A autorização para acessar os recursos do Azure pode ser fornecida não apenas aos usuários do Azure Active Directory (Azure AD), mas também a identidades de outros provedores de identidade, como serviços de nuvem de terceiros e Active Directory local. Além disso, os recursos do Azure podem ser acessados por meio de autenticação baseada em serviço, como o uso de contas de serviço e identidade gerenciada.






Você disse:
Os dados copiados para uma conta de Armazenamento do Azure são mantidos automaticamente em pelo menos três cópias.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Os dados copiados para uma conta de Armazenamento do Azure são mantidos automaticamente em pelo menos três cópias em diferentes locais dentro da mesma região, como parte do armazenamento redundante. Isso é feito para garantir a durabilidade e a alta disponibilidade dos dados. O Azure oferece várias opções de redundância, incluindo LRS (Locally Redundant Storage), GRS (Geo-Redundant Storage) e RA-GRS (Read-Access Geo-Redundant Storage), que ajudam a proteger os dados contra falhas.






Você disse:
Se definir permissões para um grupo de recursos, todos os recursos do Azure nesse grupo de recursos herdarão as permissões.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Quando você define permissões para um grupo de recursos no Azure, todos os recursos dentro desse grupo herdam essas permissões, a menos que permissões específicas sejam atribuídas diretamente aos recursos individuais. Essa herança facilita a gestão de permissões e garante que os recursos dentro de um grupo tenham um conjunto consistente de direitos de acesso.






Você disse:
No Azure Service Health, um administrador pode impedir que uma falha de serviço afete uma máquina virtual específica.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

O Azure Service Health fornece informações sobre o estado dos serviços do Azure e pode alertar os administradores sobre interrupções ou problemas, mas não tem a capacidade de impedir que uma falha de serviço afete uma máquina virtual específica. A prevenção de interrupções geralmente envolve práticas como a implementação de alta disponibilidade, replicação e balanceamento de carga.






Você disse:
Pergunta 15 de 42
No Azure Active Directory Premium, é garantida pelo menos 99,9% de disponibilidade.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

O Azure Active Directory Premium oferece um SLA (Acordo de Nível de Serviço) que garante pelo menos 99,9% de disponibilidade. Isso significa que a Microsoft se compromete a garantir que o serviço esteja disponível para os usuários de forma confiável.






Você disse:
Pergunta 16 de 42
Você tem um ambiente Azure. Você precisa criar uma nova máquina virtual do Azure a partir de um laptop Android.
Solução: você usa o portal do Azure.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Você pode usar o portal do Azure através de um navegador da web em um laptop Android para criar uma nova máquina virtual do Azure. O portal é acessível em dispositivos móveis e desktops, permitindo a gestão de recursos do Azure a partir de diferentes plataformas.






Você disse:
Pergunta 17 de 42
Uma conta de Armazenamento do Azure pode conter até 2 TB de dados e até um milhão de arquivos.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Uma conta de Armazenamento do Azure não tem um limite fixo de 2 TB ou um milhão de arquivos. Na verdade, uma conta de Armazenamento do Azure pode armazenar até 5 PB (petabytes) de dados e suportar um número muito maior de arquivos, dependendo do tipo de armazenamento (Blob, File, Queue, Table) e da configuração utilizada.






Você disse:
Pergunta 18 de 42
Um dos benefícios do Azure Synapse Analytics é que a alta disponibilidade está incorporada na plataforma.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Um dos benefícios do Azure Synapse Analytics é que ele oferece alta disponibilidade incorporada na plataforma, garantindo que os serviços permaneçam disponíveis mesmo em caso de falhas. Isso é parte do compromisso da Microsoft em fornecer uma solução confiável e escalável para análise de dados.






Você disse:
O Azure Advisor pode gerar uma lista de máquinas virtuais do Azure protegidas pelo backup do Azure.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

O Azure Advisor pode fornecer recomendações e gerar uma lista de máquinas virtuais que estão protegidas pelo Backup do Azure. Ele analisa o ambiente do Azure e sugere melhorias em áreas como segurança, desempenho, alta disponibilidade e gestão de custos, incluindo a proteção de recursos críticos como máquinas virtuais.






Você disse:
Você planeja implantar várias máquinas virtuais do Azure.
Você precisa garantir que os serviços em execução nas máquinas virtuais estejam disponíveis caso um único data center falhe.
Solução: você implanta as máquinas virtuais em duas ou mais zonas de disponibilidade.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Implantar máquinas virtuais em duas ou mais zonas de disponibilidade garante que os serviços em execução nessas máquinas virtuais permaneçam disponíveis, mesmo que um único data center falhe. As zonas de disponibilidade são locações fisicamente separadas dentro de uma região do Azure, projetadas para isolar falhas e garantir alta disponibilidade.






Você disse:
Você planeja implantar várias máquinas virtuais do Azure.
Você precisa garantir que os serviços em execução nas máquinas virtuais estejam disponíveis caso um único data center falhe.
Solução: você implanta as máquinas virtuais em duas ou mais zonas de disponibilidade.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Implantar máquinas virtuais em duas ou mais zonas de disponibilidade assegura que os serviços em execução nas máquinas virtuais permaneçam disponíveis, mesmo que um único data center falhe. As zonas de disponibilidade são projetadas para fornecer isolamento e proteção contra falhas em data centers dentro de uma região do Azure, garantindo alta disponibilidade.






Você disse:
Em um modelo de nuvem pública, apenas usuários convidados da sua empresa podem acessar os recursos na nuvem.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Em um modelo de nuvem pública, os recursos são geralmente acessíveis a todos os usuários que tenham as permissões adequadas, não apenas a usuários convidados de uma única empresa. A nuvem pública é compartilhada entre várias organizações e é projetada para fornecer acesso a uma ampla gama de usuários, desde que tenham as credenciais apropriadas.






Você disse:
Uma região do Azure contém um ou mais centros de dados que estão ligados através de uma rede de baixa latência.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Uma região do Azure é composta por um ou mais centros de dados que estão interconectados por uma rede de baixa latência. Isso permite que os serviços e recursos do Azure operem de forma eficiente e ofereçam alta disponibilidade e resiliência.






Você disse:
Uma empresa pode ampliar os recursos computacionais de sua rede interna usando a nuvem pública.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Uma empresa pode expandir seus recursos computacionais utilizando a nuvem pública, permitindo que ela adicione capacidade de processamento, armazenamento e outros serviços sem a necessidade de investimento em hardware adicional ou infraestrutura própria. Essa abordagem é conhecida como "escalabilidade na nuvem" e é uma das principais vantagens do uso de soluções em nuvem.






Você disse:
Cada assinatura do Azure pode conter vários administradores de conta.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Cada assinatura do Azure pode ter vários administradores de conta, permitindo que diferentes usuários tenham acesso e gerenciamento dos recursos associados à assinatura. Esses administradores podem incluir diferentes funções e permissões, dependendo das necessidades da organização.






Você disse:
Os recursos do Azure só podem aceder a outros recursos no mesmo grupo de recursos.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Os recursos do Azure podem acessar outros recursos, independentemente de estarem no mesmo grupo de recursos ou não. No entanto, as permissões de acesso e as configurações de rede (como redes virtuais e regras de segurança) podem afetar a comunicação entre recursos em grupos de recursos diferentes.






Você disse:
O Azure oferece flexibilidade entre despesas de capital (CapEx) e despesas de operacional (OpEx)
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

O Azure oferece flexibilidade entre despesas de capital (CapEx) e despesas operacionais (OpEx). As empresas podem optar por modelos de pagamento conforme o uso, que são característicos das despesas operacionais, ou podem investir em recursos pré-pagos, que se enquadram nas despesas de capital. Essa flexibilidade permite que as organizações escolham o modelo que melhor atende às suas necessidades financeiras e operacionais.






Você disse:
O Azure Advisor fornece recomendações sobre como reduzir o custo de execução de máquinas virtuais do Azure.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

O Azure Advisor fornece recomendações sobre como otimizar o uso de recursos, incluindo sugestões para reduzir o custo de execução de máquinas virtuais do Azure. Ele analisa a utilização dos recursos e oferece recomendações para melhorar a eficiência, o desempenho e os custos, ajudando as organizações a economizar dinheiro em suas operações na nuvem.






Você disse:
O seu ambiente Azure contém várias máquinas virtuais Azure.
Você precisa garantir que uma máquina virtual chamada VM1 possa ser acessada pela Internet por HTTP.
Solução: você modifica um perfil do Azure Traffic Manager.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Modificar um perfil do Azure Traffic Manager não garante que a máquina virtual VM1 possa ser acessada pela Internet por HTTP. O Azure Traffic Manager é usado para gerenciar a distribuição de tráfego entre várias instâncias de serviços, mas você precisa configurar as regras de firewall ou os grupos de segurança de rede (NSGs) na VM1 para permitir o tráfego HTTP (porta 80) de entrada. Portanto, apenas modificar um perfil do Traffic Manager não atenderá ao objetivo.






Você disse:
Você planeja implantar várias máquinas virtuais do Azure.
Você precisa garantir que os serviços em execução nas máquinas virtuais estejam disponíveis caso um único data center falhe.
Solução: você implanta as máquinas virtuais em duas ou mais regiões.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
TRUE.

Implantar as máquinas virtuais em duas ou mais regiões garante que os serviços em execução nelas estejam disponíveis caso um único data center falhe. Isso se deve ao fato de que as regiões do Azure são geograficamente separadas e operam de maneira independente, oferecendo redundância e resiliência em caso de falhas em um data center específico dentro de uma região. Portanto, essa solução atende ao objetivo de alta disponibilidade.






Você disse:
Se atribuir uma TAG a um grupo de recursos, todos os recursos do Azure nesse grupo de recursos serão atribuídos à mesma TAG.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Se você atribuir uma tag a um grupo de recursos no Azure, os recursos dentro desse grupo não herdarão automaticamente essa tag. Cada recurso pode ter suas próprias tags atribuídas, independentemente das tags do grupo de recursos. Portanto, é necessário atribuir as tags a cada recurso individualmente, se desejar que eles tenham a mesma tag.






Você disse:

Pergunta 32 de 42
Você tem um ambiente Azure. Você precisa criar uma nova máquina virtual do Azure a partir de um laptop Android.
Solução: você usa o portal PowerApps.
Isso atende ao objetivo?
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

O portal PowerApps não é a ferramenta apropriada para criar máquinas virtuais no Azure. Para criar uma nova máquina virtual do Azure, você deve usar o portal do Azure ou a CLI do Azure. Embora você possa acessar o portal do Azure a partir de um navegador em um dispositivo Android, o PowerApps não oferece essa funcionalidade.






Você disse:
A partir do Azure Service Health, um administrador pode ver o estado de funcionamento de todos os serviços implantados num ambiente Azure e de todos os outros serviços disponíveis no Azure.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

O Azure Service Health fornece informações sobre o estado de funcionamento dos serviços que você está usando em sua própria assinatura, bem como notificações sobre problemas e manutenção programada que possam afetar esses serviços. No entanto, ele não fornece um estado de funcionamento para todos os serviços disponíveis no Azure em geral. Para isso, você pode usar o Azure Status, que mostra o estado geral de todos os serviços do Azure em todas as regiões.






Você disse:
Um grupo de recursos do Azure contém várias assinaturas do Azure.
TRUE
FALSE
O ChatGPT disse:
ChatGPT
FALSE.

Um grupo de recursos do Azure não pode conter várias assinaturas. Um grupo de recursos é uma coleção de recursos do Azure que são gerenciados como uma única unidade, e todos os recursos em um grupo de recursos pertencem à mesma assinatura do Azure. Cada assinatura pode ter vários grupos de recursos, mas um grupo de recursos pertence apenas a uma única assinatura.






Você disse:
Quando uma Máquina Virtual do Azure é parada, você continua a pagar os custos de armazenamento associados à Máquina Virtual.
TRUE
FALSE
