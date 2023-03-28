# Static-Dynamic-NAT
Tarefas:

Configure a rede da seguinte forma:
1) Detalhes do roteador:
Fora = 8.8.8.100/24
Dentro = 10.1.1.254/24
Rota padrão para 8.8.8.8
2) Configure o NAT estático para que o PC externo possa acessar os servidores HTTP e FTP internos.
HTTP = 8.8.8.200 (NAT apenas a porta necessária). DNS = meuhttp.com
FTP = 8.8.8.201 (NAT estático completo). DNS = myftp.com
3) Configure o NAT dinâmico usando o endereço IP do roteador para que os PCs internos possam acessar os servidores da Internet
4) Verifique se o PC externo pode acessar os servidores internos usando os nomes DNS do servidor.
5) Verifique se os PCs internos podem acessar os servidores da Internet usando seus nomes DNS.

<img src="https://raw.githubusercontent.com/MattheusMartins/Static-Dynamic-NAT/main/1.PNG">
