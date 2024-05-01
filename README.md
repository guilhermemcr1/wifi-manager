
# WIFI Manager

Um projeto realizado para gerenciar hotspots Wi-Fi utilizando PfSense, FreeRadius e as controladoras dos seus APs.





## Funcionalidades e integraÃ§Ãµes

- Cadastro de UsuÃ¡rios no banco do FreeRadius
- Rede de visitantes com troca automÃ¡tica do cÃ³digo do Portal Cativo
- IntegraÃ§Ã£o com Portal Cativo do PfSense
- Permite utilizaÃ§Ã£o de autenticaÃ§Ã£o via MAC com validaÃ§Ã£o feita pela controladora do AP.
- Permite controle de banda e separaÃ§Ã£o por VLANs das redes criadas.
## Requisitos

- PfSense, OPNSense ou algum firewall ou equipamento que possua portal cativo personalizÃ¡vel.

- APs ou Roteadores que possuam controladoras gerenciÃ¡veis para inserir as informaÃ§Ãµes do servidor RADIUS e as VLANs.

- Servidor Linux com todos pacotes LAMP para salvar as informaÃ§Ãµes do FreeRadius e as informaÃ§Ãµes do Portal Administrativo, alÃ©m de executar o sistema de gestÃ£o.

## InstalaÃ§Ã£o do portal administrativo

1. Instalar e configurar o firewall ou Roteador em questÃ£o com as VLANs e os portais cativos necessÃ¡rios.

2. Importar os bancos de dados exemplos para o MySQL que vai executar o portal administrativo.

3. Configurar as informaÃ§Ãµes do banco de dados no arquivo funcoes.php

4. Colocar os arquivos no diretÃ³rio do servidor Web, a CPF padrÃ£o para acesso Ã© "00000000000" e a senha Ã© "admin".