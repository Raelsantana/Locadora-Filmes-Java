# Sistema de Gerenciamento de Locadora

Você foi contratado para desenvolver um sistema de gerenciamento
para uma locadora de filmes. O sistema deve permitir o controle de
clientes, itens para locação e operações de aluguel.
Ações/Operações no Sistema:

### Gestão de Clientes:
- Cadastrar novo cliente
- Atualizar dados de cliente existente
- Consultar cliente por CPF
- Listar todos os clientes (com filtros opcionais)
- Ver histórico de locações de um cliente
### Gestão de Itens da Locadora:
- Cadastrar novo item para locação
- Atualizar informações de um item
- Alterar status do item (disponível/alugado/manutenção)
- Buscar itens por título, gênero ou tipo
- Listar itens disponíveis para locação
- Gerar relatório de itens mais alugados
- 
### Operações de Locação:
- Registrar nova locação (vinculando cliente e itens)
- Registrar devolução de itens
- Calcular valor total da locação
- Calcular multa por atraso (se aplicável)
- Listar locações ativas
- Listar locações com devolução em atraso
- Cancelar locação (antes da retirada)
- 
### Fluxo Básico do Sistema:

1. Um novo cliente chega à locadora e é cadastrado no sistema
2. O cliente busca por um filme específico ou navega pelos itens disponíveis
3. O atendente seleciona os itens desejados e registra a locação
4. O sistema calcula o valor total baseado no preço diário de cada item
5. O cliente recebe os itens e a data prevista para devolução
6. Ao devolver os itens, o sistema verifica se houve atraso e calcula multa se
necessário
7. O atendente registra a devolução e o item volta ao status "disponível"
