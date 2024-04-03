# NLW Unite 

## Pass In
O pass.in é uma aplicação de **gestão de participantes em eventos presenciais**.

A ferramenta permite que o organizador cadastre um evento e abra uma página pública de inscrição.

Os participantes inscritos podem emitir uma credencial para check-in no dia do evento.

O sistema fará um scan da credencial do participante para permitir a entrada no evento.

### Requisitos funcionais:
1. o organizador deve poder cadastrar um novo evento;
2. o organizador deve poder visualizar dados de um evento;
3. o organizador deve poder visualizar a lista de participantes;
4. o participante deve poder se inscrever em um evento;
5. o participante deve poder visualizar seu crachá de inscrição;
6. o participante deve poder realizar checkin no evento.

### Regras de negócio:
1. o participante só pode se increver em um evento, uma única vez;
2. o participante só pode se inscrever em eventos com vagas dispopníveis;
3. o participante só pode realizar check-in em um evento, uma única vez.

### Regras não-funcionais:
1. o check-in no evento será realizado através de um QRCode.