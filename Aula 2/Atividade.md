

## Item 1 – Acompanhar pedido

- Como cliente, quero saber onde meu pedido está para não ficar ansioso.

### Critérios de aceitação

- Dado que o pedido foi confirmado, quando o pedido for enviado, então recebo um código de rastreio.
- Dado que o pedido foi recusado, quando eu não souber o motivo, então recebo uma notificação informando o motivo da recusa.
- Dado que o pedido foi enviado, quando eu quiser saber onde ele está, então recebo um link com sua localização.

## Item 2 – Item do cardápio indisponível

- Como Chef de Cozinha, quero saber quando um item do cardápio fica indisponível para não colocar o que não tem no cardápio.

### Critérios de aceitação

- Dado que o produto está acabando, quando ele estiver próximo de acabar, então o sistema emite um alerta.
- Dado que o item acabou, quando o usuário procurar por ele, então o item deve ficar oculto.
- Dado que o item acabou, quando o usuário tiver o item nos favoritos, então deve aparecer como indisponível.

## Item 3 – Reportar problemas na entrega

- Como motoboy, quero um lugar para colocar os problemas que acontecem durante a entrega para não ter que ligar para o estabelecimento toda vez que algo acontece.

### Critérios de aceitação

- Dado que estou realizando uma entrega, quando acontecer um problema, então posso acessar uma área para reportar o ocorrido.
- Dado que estou na área de reportar problemas, quando selecionar o tipo de problema e descrever o que aconteceu, então o sistema deve registrar a ocorrência.
- Dado que registrei um problema durante a entrega, quando enviar o relatório, então o estabelecimento recebe uma notificação informando o ocorrido.

## Priorização MoSCoW

### Must Have (Deve ter)
- Acompanhar o status do pedido.
- Avisar quando um item do cardápio estiver indisponível.
- Reportar problemas durante a entrega.

### Should Have (Deveria ter)
- Receber notificações sobre o status do pedido.
- Alertas de produtos próximos de acabar.
- Notificação ao estabelecimento sobre problemas na entrega.

### Could Have (Poderia ter)
- Histórico de problemas nas entregas.
- Filtro para visualizar apenas itens disponíveis.

### Won't Have (Não terá nesta versão)
- Relatórios avançados de problemas.
- Integração com outros aplicativos de rastreamento.
