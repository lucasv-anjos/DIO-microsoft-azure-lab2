**Service Level Agreement(SLA)**

Um Service Level Agreement é um contrato ou compromisso formal entre um provedor de serviço e o cliente, no qual são definidos os níveis mínimos de serviço que o provedor se compromete a fornecer, no Microsoft azure ele especifica a disponibilidade e os tempos de resposta para diferentes serviços da nuvem, como computação, armazenamento e redes, ele é baseado em porcentagem e quanto mais proximo a 100% menor o tempo fora de execução, caso o azure não comprir com o nivel de serviço acordado, no caso, caso a aplicação fique fora do ar mais tempo do que o previsto o cliente é compensado com creditos dependendo da falha no SLA.

**Contas de Armazenamento**

O Microsoft azure possui tipos de redundancia de armazenamento que definem como os dados são armazenados e protegidos contra falhas, entre eles.

Locally Redundant Storage(LRS):
    
    mantém três cópias idênticas dos dados em um único data center, localizado em uma região específica
 

Geo-Redundant Storage(GRS):

    replica os dados em duas regiões geográficas diferentes. Primeiro, os dados são replicados de forma LRS em um data center primário, e depois são copiados para um segundo data center em uma região diferente.
 
Zone-Redundant Storage(ZRS):
    
    replica os dados em múltiplas zonas de disponibilidade dentro de uma mesma região. Isso significa que os dados são distribuídos entre datacenters fisicamente separados, mas localizados na mesma região.
 
Geo-Zone-Redundant Storage(GZRS):
    
    combina os benefícios do GRS e do ZRS. Ele replica os dados de forma zona-redudante dentro de uma região primária e, em seguida, replica essas cópias para uma segunda região geograficamente distante.

