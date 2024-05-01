
# WIFI Manager

Um projeto realizado para gerenciar hotspots Wi-Fi utilizando PfSense, FreeRadius e as controladoras dos seus APs.





## Funcionalidades e integrações

- Cadastro de Usuários no banco do FreeRadius
- Rede de visitantes com troca automática do código do Portal Cativo
- Integração com Portal Cativo do PfSense
- Permite utilização de autenticação via MAC com validação feita pela controladora do AP.
- Permite controle de banda e separação por VLANs das redes criadas.
## Requisitos

- PfSense, OPNSense ou algum firewall ou equipamento que possua portal cativo personalizável.

- APs ou Roteadores que possuam controladoras gerenciáveis para inserir as informações do servidor RADIUS e as VLANs.

- Servidor Linux com todos pacotes LAMP para salvar as informações do FreeRadius e as informações do Portal Administrativo, além de executar o sistema de gestão.

## Instalação do portal administrativo

1. Instalar e configurar o firewall ou Roteador em questão com as VLANs e os portais cativos necessários.

2. Importar os bancos de dados exemplos para o MySQL que vai executar o portal administrativo.

3. Configurar as informações do banco de dados no arquivo funcoes.php

4. Colocar os arquivos no diretório do servidor Web, a CPF padrão para acesso é "00000000000" e a senha é "admin".