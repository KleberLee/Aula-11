# Aula 11 – Redes de Computadores: Topologias, Dispositivos e Meios

## Objetivo
Primeiro, a organização física da rede é a forma como os dispositivos estão conectados no mundo real. Isso envolve as chamadas topologias, como estrela (um ponto central conectando tudo), barramento (todos ligados em um único cabo), anel (em formato circular) e malha (todo mundo conectado com todo mundo). Aqui entram também os cabos, roteadores, switches e tudo que você consegue “ver e tocar”.

Já a organização lógica da rede é como os dados circulam dentro dessa estrutura física. Ou seja, não importa só como está conectado, mas como a informação trafega. Isso envolve protocolos (como o TCP/IP), endereçamento IP e regras de comunicação que garantem que a mensagem saia de um ponto e chegue corretamente ao destino.

Agora, sobre os principais dispositivos:

Roteador (Router): conecta redes diferentes e direciona os dados.
Switch: conecta dispositivos dentro da mesma rede local.
Hub: versão mais simples do switch (hoje quase não se usa).
Modem: faz a ligação com a internet.
Access Point: permite conexão sem fio (Wi-Fi).

E por fim, os meios de transmissão, que são os caminhos por onde os dados passam:

Cabos de par trançado (Ethernet): muito comum em redes locais.
Fibra óptica: altíssima velocidade e estabilidade.
Ondas de rádio (Wi-Fi): conexão sem fio.
Outros: como satélite e micro-ondas.

### 1. Diagramas de Topologias
<img width="1061" height="631" alt="Captura de tela 2026-04-20 193037" src="https://github.com/user-attachments/assets/355ec5d0-207e-442a-8a72-c8f1af22ca43" />

### 2. Quadro Comparativo de Dispositivos
Hub

Função principal:
O hub é o mais simples. Ele recebe um dado e envia pra todos os dispositivos conectados, sem saber quem é o destino.

Vantagens:

Barato
Fácil de usar

Limitações:

Gera muito tráfego desnecessário (todo mundo recebe tudo)
Baixa segurança
Pode causar lentidão na rede

Exemplo de uso:

Redes antigas ou ambientes bem simples (hoje quase não se usa mais)
Switch

Função principal:
O switch já é mais inteligente. Ele envia os dados apenas para o dispositivo correto, usando o endereço físico (MAC).

Vantagens:

Muito mais rápido que o hub
Reduz tráfego na rede
Mais seguro

Limitações:

Não conecta redes diferentes
Pode ser mais caro que hub

Exemplo de uso:

Redes de empresas
LANs (redes locais em casas, escolas, escritórios)
Roteador (Router)

Função principal:
O roteador conecta redes diferentes (por exemplo, sua casa com a internet) e decide o melhor caminho para os dados.

Vantagens:

Permite acesso à internet
Gerencia tráfego entre redes
Pode oferecer Wi-Fi e segurança (firewall)

Limitações:

Mais complexo de configurar
Custo maior

Exemplo de uso:

Internet residencial
Empresas conectando várias redes
Provedores de internet
