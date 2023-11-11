pkt version: 8.2.0

## Resoluções dos exercicios propóstos em sala de Aula

> 27/10/2023

## Parte 1: Análise de uma Captura do Wireshark

### Qual é a importância do conteúdo do campo Endereço Destino?

    Identificação do Endereço MAC da máquina destinatária. É aqui que se encontra o endreço que será utilizado como destino.

### Por que o PC envia um broadcast ARP antes da primeira requisição ping?

    Ele faz esse envio para indentificar as maquinas presentes na rede, afim de saber se a maquina de destino se encontra nessa mesma rede.

### Qual é o endereço MAC origem no primeiro quadro?

    O endereço é: f0:1f:ad:50:fd:c8

### Qual é o ID do fornecedor (OUI) da NIC de origem na resposta do ARP?

    O ID é 30:46:9a

### Que parte do endereço MAC é a OUI?

    São os 3 primeiros Octetos, ou os 6 primeiros números hexadecimais.

### Qual é o número serial da NIC de origem? 

    O número serial é: 99:c5:72


## Parte 2: Usar o Wireshark para capturar e analisar quadros Ethernet II
> utilizado o arquivo NAT_home_side.pcap

### Etapa 6: 
    c. 
        - Qual é o endereço MAC da NIC do PC?
            00:22:68

        - Qual é o endereço MAC do gateway padrão?
            00:22:6b:45:1f:1b

    d.
        - Que tipo de quadro é exibido?
            Tipo : IPv4(0x0800)

    e.
        - Qual é o endereço IP de origem?
            192.168.1.100

        - Qual é o endereço IP de destino?
            10.199.240.64