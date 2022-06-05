# Configura-o-do-MPLS-L3VPN
Instrução de trabalho para configuração do MPLS L3VPN

## Passos para configuração na pratica
1 - Configurar uma VRF para cada cliente nos roteadores PE onde os pontos serão conectados
2 - Configurar a VPN no PE router para importar as rotas da VRF e divulgar via iBGP para o outro ou outros PEs
3 - Fazer a configuração inicial dos roteadores CE que é o roteador “do cliente” onde obrigatoriamente tem uma conexão com o PE, não tem MPLS configurada, e nem VRF
4 - Configurar roteamento entre CE e PE (BGP)

## Links para material de apoio
[Configuração da rede para suportar]
(https://brainwork.com.br/2017/04/18/configurando-mpls-l3vpn-ospf-ldp-vrf-bgp/)
(https://support.huawei.com/enterprise/en/doc/EDOC1000178321/ac3da89f/example-for-configuring-a-tunnel-policy-for-an-l3vpn)
(https://www.teleco.com.br/tutoriais/tutorialmplseb2/pagina_2.asp)
