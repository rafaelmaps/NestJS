# NestJS
Uso do framework NestJS. Integração com MongoDB, RabbitMQ, AWS

O intuito deste projeto é a construção de um sistema gerenciador de Ranking de jogadores amadores de Tênis.
As caracteriscas da aplicação envolvem:
1. Jogador:
    - Solicitar/Rejeitar partidas;
    - Resgistrar resultado de uma partida;
    - Consultar o Ranking dos jogadores;
    - Consultar dados de jogadores e histórico de partidas;
    - Notificação via e-mail;
2. Administrador:
    - Cadastrar categorias;
    - Cadastrar jogadores e associar a uma categoria;
    - Notificado caso haja partida pendente em mais de 10 dias
