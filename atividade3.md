
# Atividade – Requisitos Não Funcionais (RNF)

## História 1 – Avaliar o pedido

**História de usuário:**

Como cliente, quero avaliar o pedido depois da entrega, para ajudar outros clientes a escolherem melhor.

**Critérios de aceitação:**

- Dado que o pedido foi entregue, quando o cliente abre o app, então aparece a opção de avaliar o pedido.
- Dado que o cliente avalia com nota e comentário, quando confirma o envio, então a avaliação aparece no perfil do restaurante.

### RNF 1 – Usabilidade

O aplicativo deve apresentar uma tela de avaliação simples e intuitiva, permitindo que o cliente avalie o pedido sem dificuldade.

**Característica ISO/IEC 25010:** Usabilidade.

### RNF 2 – Segurança

O sistema deve garantir que apenas o cliente que realizou o pedido possa enviar uma avaliação relacionada àquela compra.

**Característica ISO/IEC 25010:** Segurança.

### RNF 3 – Confiabilidade

O sistema deve garantir que a avaliação seja armazenada corretamente após o envio, evitando a perda dos dados registrados.

**Característica ISO/IEC 25010:** Confiabilidade.

---

## História 2 – Salvar cartão de pagamento

**História de usuário:**

Como cliente, quero salvar um cartão de pagamento, para não digitar os dados a cada compra.

**Critérios de aceitação:**

- Dado que o cliente cadastra um cartão válido, quando confirma o cadastro, então o cartão fica disponível para escolha no checkout.
- Dado que o cliente tem um cartão salvo, quando faz um novo pedido, então pode selecionar esse cartão sem redigitar os dados.

### RNF 1 – Segurança

O sistema deve proteger os dados do cartão salvo, utilizando mecanismos de segurança para evitar o acesso não autorizado.

**Característica ISO/IEC 25010:** Segurança.

### RNF 2 – Usabilidade

O cadastro e a seleção do cartão salvo devem ser simples e fáceis de utilizar durante o checkout.

**Característica ISO/IEC 25010:** Usabilidade.

### RNF 3 – Eficiência de desempenho

O sistema deve carregar os cartões salvos em até 2 segundos após o cliente acessar a tela de pagamento, em condições normais de funcionamento.

**Característica ISO/IEC 25010:** Eficiência de desempenho.

---

## História 3 – Reportar problemas na entrega

**História de usuário:**

Como motoboy, quero um lugar para colocar os problemas que acontecem durante a entrega, para não ter que ligar para o estabelecimento toda vez que algo acontece.

**Critérios de aceitação:**

- Dado que o entregador está realizando uma entrega, quando acontecer um problema, então pode acessar uma área para reportar o ocorrido.
- Dado que o entregador preenche as informações do problema, quando enviar o relatório, então o estabelecimento recebe uma notificação informando o ocorrido.

### RNF 1 – Usabilidade

O sistema deve apresentar uma área de reporte simples e fácil de utilizar, permitindo que o entregador registre um problema durante a entrega.

**Característica ISO/IEC 25010:** Usabilidade.

### RNF 2 – Confiabilidade

O sistema deve garantir que os problemas registrados sejam armazenados corretamente, evitando a perda das informações enviadas pelo entregador.

**Característica ISO/IEC 25010:** Confiabilidade.

### RNF 3 – Eficiência de desempenho

O sistema deve processar o envio do relatório em até 3 segundos, em condições normais de funcionamento, para agilizar a comunicação com o estabelecimento.

**Característica ISO/IEC 25010:** Eficiência de desempenho.