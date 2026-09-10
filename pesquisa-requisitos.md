A forma mais simples de entender a diferença entre os dois é pensar na relação entre **"O que"** e **"Como"**.

* **Requisitos Funcionais (O QUE o sistema faz):** São as funcionalidades, ações e comportamentos que o software deve ter. É tudo aquilo que o usuário (ou outro sistema) consegue fazer ou interagir. Sem eles, o aplicativo simplesmente não cumpre o seu propósito básico.
* **Requisitos Não Funcionais (COMO o sistema faz):** São os critérios de qualidade, restrições e performance do sistema. Eles não são uma ação que o usuário executa, mas definem a experiência, a segurança e a velocidade com que o sistema opera.

---

### Resumo Rápido

| Característica | Requisitos Funcionais | Requisitos Não Funcionais |
| --- | --- | --- |
| **Foco principal** | Ação, funcionalidade, regras de negócio. | Performance, segurança, usabilidade, escalabilidade. |
| **Pergunta que responde** | O que o aplicativo deve fazer? | Quão bem o aplicativo deve fazer isso? |
| **Exemplo cotidiano (Carro)** | O carro deve ter um volante e freios. | O carro deve ir de 0 a 100 km/h em 5 segundos. |

---

### 3 Exemplos Práticos (Imaginando um App tipo iFood)

Aqui está como essa separação funciona na prática na hora de planejar o aplicativo de delivery:

#### 🍔 Requisitos Funcionais (Ações)

1. **Carrinho de Compras:** O usuário deve conseguir adicionar, editar ou remover itens do seu carrinho antes de fechar o pedido.
2. **Gestão de Pedidos (Restaurante):** O painel do restaurante deve permitir que o estabelecimento aceite ou recuse um pedido recebido.
3. **Rastreamento em Tempo Real:** O aplicativo deve exibir um mapa atualizando a localização do entregador em tempo real após a retirada do pedido.

#### ⏱️ Requisitos Não Funcionais (Qualidade/Restrição)

1. **Performance:** A lista de restaurantes da tela inicial deve carregar em, no máximo, **2 segundos** após o usuário abrir o aplicativo.
2. **Escalabilidade (Disponibilidade):** O sistema deve ser capaz de suportar até **100.000 acessos simultâneos** sem cair durante os horários de pico (ex: sexta-feira à noite).
3. **Segurança:** Os dados do cartão de crédito do usuário devem ser **criptografados de ponta a ponta** e nunca armazenados em texto limpo no banco de dados.

**Dica de ouro:** Se você consegue colocar um botão na tela para o usuário clicar e realizar aquilo, é um Requisito Funcional. Se você precisa medir com um cronômetro, testar limite de carga ou auditar o código, é um Requisito Não Funcional.
