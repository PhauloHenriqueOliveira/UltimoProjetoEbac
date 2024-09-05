# Projeto de Processamento de Mensagens Telegram com AWS

## Introdução
Este projeto foi desenvolvido para automatizar o recebimento, armazenamento e processamento de mensagens recebidas via Telegram, utilizando a infraestrutura da AWS. A solução inclui a captura de mensagens através de uma API Gateway, a verificação do conteúdo e o armazenamento em buckets S3. Diariamente, as mensagens são consolidadas em arquivos Parquet compactados e armazenados para análises posteriores.

## Chat Bot
O chat bot é uma aplicação responsável por interagir com os usuários em tempo real. No contexto deste projeto, o chat bot está configurado para receber mensagens enviadas em um grupo específico no Telegram e processá-las para posterior armazenamento e análise. Ele é uma peça fundamental na comunicação entre usuários e sistemas, permitindo uma coleta automática de informações relevantes. Neste caso, utilizados o bot father, um sistema de bots do própio Telegram disponibilizado publicamente para qualquer um.

## Telegram
O Telegram é uma plataforma de mensagens instantâneas que permite a criação de bots para realizar tarefas automatizadas, como a coleta de dados, notificações e integração com sistemas externos. Neste projeto, o bot do Telegram recebe mensagens de um grupo específico, possibilitando a captura de dados em tempo real e sua integração com a infraestrutura da AWS.

## Objetivo
O objetivo deste projeto é automatizar o processo de captura, armazenamento e processamento de mensagens enviadas em um grupo do Telegram, utilizando serviços da AWS, como S3 e Lambda. O sistema armazena as mensagens recebidas no formato JSON e, em seguida, compacta e transforma esses dados em arquivos Parquet, particionados por data, permitindo uma organização eficiente e fácil acesso para análises futuras.

Como exemplo: as pessoas que mais interagem no grupo:
Os assuntos mais comentados atraves da pesquisa de palavras chaves
O momento que as pessoas estão mais ativas: pode ser um indicativo do momento que elas estão disponiveis para uma programação, ir a algum lugar,

Essas informações valiosa para marketing além de outros tipos de informações que podem ser uteis para diversos setores

