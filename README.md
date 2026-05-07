# projeto-matriz-sedetech
Laboratório de infraestrutura corporativa: Implementação de VLANs, serviços centralizados (DHCP/DNS), Wi-Fi e segurança em ambientes Cisco.

## Implementações de Infraestrutura (Maio/2026)

Nesta etapa do projeto, foquei na automação e segurança da rede local. Configurei o serviço de **DHCP no Roteador**, permitindo que os dispositivos das VLANs 10, 20 e 40 recebam endereçamento automático. Também implementei o acesso remoto seguro via **SSH v2** no Switch Principal para substituir o protocolo inseguro Telnet.

### Visão de Segurança (SOC)
Embora a segmentação por VLANs tenha sido concluída, identifiquei que o roteamento inter-VLAN permite a comunicação entre redes distintas como WiFi e RH. O próximo marco do projeto será a implementação de **ACLs (Access Control Lists)** para restringir essa movimentação lateral e aumentar o hardening da rede.