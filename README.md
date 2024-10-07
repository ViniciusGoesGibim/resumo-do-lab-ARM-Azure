## Armazenamento Azure

## Contas de Armazenamento
As contas de armazenamento do Azure são estruturas que armazenam objetos de dados do Azure, como blobs, arquivos, filas e tabelas. Elas fornecem um namespace exclusivo para os dados do Azure, que podem ser acessados de qualquer lugar do mundo por HTTP ou HTTPS.</br>
O Azure é uma nuvem híbrida da Microsoft que oferece serviços de armazenamento, como:
#### Armazenamento de Blobs do Azure
Uma solução para armazenar grandes quantidades de dados não estruturados, como imagens, vídeos, documentos e arquivos de áudio.
#### Azure Queue Storage (AQS)
Um serviço de mensageria que permite receber mensagens de qualquer lugar do mundo para serem processadas.
#### Azure Data Lake Storage
Uma solução para a análise de Big Data que combina um sistema de arquivos de alto desempenho com grande escala e economia.
#### Arquivos do Azure
Um serviço que permite mover aplicativos e dados para o Azure, ou mover apenas os dados do aplicativo para o serviço.

## Redundância de Armazenamento
A redundância de armazenamento no Azure é uma funcionalidade que replica os dados de uma conta de armazenamento em várias cópias para protegê-los de falhas e desastres.</br>
O Azure oferece diferentes opções de redundância de armazenamento, incluindo:
#### Armazenamento com redundância local (LRS)
Copia os dados três vezes, de forma síncrona, em um único local físico na região primária. É a opção menos dispendiosa, mas não é recomendada para aplicativos que precisam de alta durabilidade ou disponibilidade.
#### Armazenamento com redundância de zona (ZRS)
Copia os dados três vezes, de forma síncrona, em três zonas de disponibilidade na região primária. É recomendado para aplicativos que precisam de alta disponibilidade.
#### Armazenamento com redundância geográfica (GRS)
Copia os dados três vezes, de forma síncrona, em uma zona de disponibilidade e, de forma assíncrona, em outra zona de disponibilidade.
#### Armazenamento com redundância de zona geográfica (GZRS)
Uma opção de replicação com redundância geográfica.

## Pontos de extremidade públicos do serviço de armazenamento
Um ponto de extremidade público de um serviço de armazenamento é um ponto de acesso que permite o acesso a uma conta de armazenamento por meio de um IP.</br>
No entanto, o acesso é restrito a locais especificados na configuração.</br> 
É possível restringir o acesso a uma conta de armazenamento de duas formas:
- Criando pontos de extremidade privados para a conta de armazenamento e restringindo o acesso ao ponto de extremidade público.
- Restrigindo o ponto de extremidade público a uma ou mais redes virtuais.</br>

Um ponto de extremidade é um ponto de extremidade da rede que atende um conjunto de APIs. Um serviço pode ter vários pontos de extremidade, e todos eles compartilham a mesma configuração de serviço.

### Camadas de acesso de armazenamento do Azure
As camadas de acesso de armazenamento do Azure são níveis de armazenamento de dados que definem a frequência com que os dados são acessados:
#### Camada quente (Frequente)
uma camada online otimizada para armazenar dados acessados ou modificados com frequência. A camada quente tem os custos de armazenamento mais altos, mas os custos de acesso mais baixos.
#### Camada fria (Esporádico)
uma camada online otimizada para armazenar dados acessados ou modificados com pouca frequência. Os dados na camada de acesso esporádico devem ser armazenados por um mínimo de 30 dias. A camada fria tem custos de armazenamento mais baixos e custos de acesso mais altos em comparação com a camada quente.
#### Camada de acesso frio
uma camada online otimizada para armazenar dados acessados ou modificados com pouca frequência, mas que ainda exigem uma recuperação rápida. Os dados na camada acesso frio devem ser armazenados por um mínimo de 90 dias. A camada de acesso frio tem custos de armazenamento mais baixos e custos de acesso mais altos em comparação com a camada de acesso esporádico.
#### Camada de arquivos (Arquivo Morto)
uma camada offline otimizada para armazenar dados acessados raramente e com requisitos de latência flexíveis, na ordem de horas. Os dados na camada de arquivos devem ser armazenados por um mínimo de 180 dias.

## Migrações para o Azure
As Migrações para Azure é um serviço que ajuda a migrar para o Azure, orientando na escolha do melhor caminho, na avaliação da preparação e no cálculo de custos. O serviço também oferece suporte para a migração de:
- Servidores
- Bancos de dados
- Aplicativos Web
- Áreas de trabalho virtuais
- VMs do VMware locais
- VMs do Hyper-V
- Outras VMs virtualizadas

O Azure Migrate usa ferramentas da Microsoft ou de terceiros para detectar, avaliar e migrar os aplicativos locais e máquinas virtuais.

### Azure Databox
Azure Data Box é um serviço do Microsoft Azure que permite a transferência de dados para o Azure de forma rápida, económica e segura.</br> 
O Azure Data Box funciona através de um dispositivo de armazenamento proprietário que é enviado pela Microsoft ao cliente.</br>
O cliente pode então copiar os dados para o dispositivo e devolvê-lo à Microsoft. O processo de transferência pode ser controlado através do portal do Azure.</br> 
O Azure Data Box pode ser uma solução prática para migrar para a nuvem, pois permite realizar o processo de forma estruturada e planejada, sem riscos de perdas ou incidentes.</br> 
O Azure Data Box está disponível em diferentes modelos, incluindo o Data Box Heavy, que tem uma capacidade de armazenamento de 1 PB.

## Opções de Gerenciamento de Arquivos
### AzCopy
O AzCopy é um utilitário de linha de comando que permite copiar arquivos e blobs para ou de uma conta de armazenamento do Azure.</br>
Ele pode ser usado para: 
- Copiar arquivos locais para o Azure Blob Storage 
- Copiar entre diferentes contas de armazenamento 
- Copiar dados entre um sistema de arquivos e uma conta de armazenamento

### Gerenciador de Armazenamento do Azure
O Gerenciador de Armazenamento do Microsoft Azure é um aplicativo que permite gerenciar contas e recursos de armazenamento do Azure. Ele está disponível para Windows, macOS e Linux.</br>
O Armazenamento do Microsoft Azure é um serviço gerenciado que fornece armazenamento em nuvem. Ele é composto por vários serviços principais e recursos de suporte.</br>
Algumas opções de armazenamento do Azure são: Armazenamento de Contêineres do Azure, Armazenamento de Arquivos do Azure, Armazenamento de Blobs do Azure, Azure Data Lake Storage.</br></br>
Algumas das funcionalidades do Gerenciador de Armazenamento do Azure são: 
- Conectar e gerenciar contas de armazenamento do Azure 
- Criar, excluir, exibir, editar e gerenciar recursos 
- Copiar um compartilhamento de arquivos para a área de transferência e colá-lo em outra conta de armazenamento

### Sincronização de Arquivos do Azure
A Sincronização de Arquivos do Azure é um serviço que permite armazenar em cache vários compartilhamentos de arquivos do Azure em um Windows Server local ou uma VM na nuvem.</br>
A Sincronização de Arquivos do Azure oferece os seguintes benefícios:
- Centraliza os compartilhamentos de arquivos da organização no serviço Arquivos do Azure 
- Mantem a flexibilidade, o desempenho e a compatibilidade de um servidor de arquivos do Windows 
- Transforma o Windows Server em um cache rápido do compartilhamento de arquivo do Azure 
- Permite acessar os dados localmente usando qualquer protocolo disponível no Windows Server, incluindo SMB, NFS e FTPS


