ESTUDOS V6 — ACESSO ESTÁVEL

A V6 foi ajustada para não considerar o endereço IP do Wi-Fi como o endereço permanente da plataforma.

IMPORTANTE
O ícone da tela inicial só deve ser instalado depois que a V6 estiver aberta pelo endereço mDNS/Bonjour do SimpleHttpServer, e não por um endereço como 192.168.x.x ou 10.x.x.x.

CONFIGURAÇÃO NO SIMPLEHTTPSERVER
1. Use o SimpleHttpServer 3.5.0 ou mais recente.
2. Ative mDNS / Bonjour nas configurações do servidor.
3. Mantenha a pasta da V6 como pasta raiz (Root) e com escrita permitida.
4. Ative “Allow uploads”.
5. Abra a V6 pelo nome/endereço local anunciado pelo servidor, em vez de usar o IP mostrado pelo Wi-Fi.
6. Somente depois disso instale a V6 na tela inicial.

DADOS
A V6 mantém uma cópia local e também grava cópias em /dados/ no servidor. Cópias vazias nunca são enviadas ao servidor.
Se a recuperação automática não acontecer, Config. → Recuperar dados do servidor tenta carregar a cópia mais recente existente em /dados/.

OBSERVAÇÃO
O SimpleHttpServer é um servidor da rede local. A V6 continuará disponível somente quando o dispositivo que hospeda o servidor estiver acessível pela rede local.
