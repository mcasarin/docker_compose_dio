# Containers de aplicação Web
Repositorio utilizado para entrega de trabalho no Curso de Fundamentos de Docker na DIO
--
Neste projeto foi utilizada imagem do Nextcloud 31.0.7, há persistência de dados na aplicação e no banco de dados utilizando o host local.
Redis é utilizado para criar cache das edições online e controla os compartilhamentos.
Proxy utilizando Alpine (NGinx) e certificados SSL administrados por um container dedicado Let's Encrypt.
Banco de dados está configurado fixamente na versão 11.4 por exigência do Nextcloud (versão Community).
Suite de edição de arquivos é utilizado o Collabora, possui um subdomínio especifico para que o WOPI (Comunicação web entre os serviços) funcione corretamente.
