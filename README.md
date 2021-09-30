## Cenário
Na Creditas, nós realizamos diversos procedimentos além da compra e venda do automóvel que precisam da presença física do mesmo. Entre eles, estão a inspeção prévia do veículo para divulgação no nosso site e visitas de possíveis compradores.

Para realizar tais procedimentos, obviamente, temos que pedir que o proprietário do veículo o traga para algum Centro de Atendimento Volanty (CAV), numa data pré-agendada.

### Inspeção
Para realizar uma inspeção, o proprietário do veículo precisa consultar a nossa agenda (via site ou pelo nosso telefone) e escolher um horário disponível em algum CAV.

### Visita
Para que a visita aconteça, o interessado num determinado veículo deve encontrar um horário disponível na nossa agenda (via site ou telefone), dado o CAV onde o proprietário se comprometeu de levar o veículo. Após a escolha do horário, notificamos o proprietário, que confirma a presença do veículo naquela data.

## Desafio
Dado o cenário acima, escreva uma api REST que seja possível gerenciar os CAVs e os eventos de agendamentos (inspeção e visita).

### Pré-requisitos
Utilize os arquivos JSON abaixo como fonte de dados (é permitido alterar os modelos caso julgue necessário);

[CAV](./src/cav.json), [Carros](./src/cars.json) e [Agenda](./src/calendar.json).


## Método de entrega
- O código pode ser escrito em Java, NodeJS, TypeScript, Python, Kotlin e Golang;

- Os dados deverão ser persistidos em qualquer base de dados e manter o estado em caso de restart do serviço;

- A execução do código não pode depender do uso de uma IDE específica.

- O projeto deverá rodar em qualquer ambiente com Docker sem instalação adicional de libs;

- Desejável testes;

