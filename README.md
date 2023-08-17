# Otimizando Sistema Bancario Com Funções Python

![python](https://github.com/Adriano1976/Sistema-Bancario-com-Python/assets/17755195/2db44fad-36b6-440c-8fd6-7c111ee821a4)

Neste desafio, tive a oportunidade de otimizar o Sistema Bancário previamente desenvolvido com o uso de funções Python. O objetivo é aprimorar a estrutura e a eficiência do sistema, implementando as operações de depósito, saque e extrato em funções específicas. Tive a chance de refatorar o código existente, dividindo-o em funções reutilizáveis, facilitando a manutenção e o entendimento do sistema como um todo. Com isso, tive a oportunidade de aplicar os conceitos avançados de programação e demonstrar minha habilidade em criar soluções mais elegantes e eficientes utilizando Python.

# Simulador Bancário

O **Simulador Bancário** é um programa em Python que simula um sistema bancário básico. Ele permite a realização de operações como depósito, saque, exibição de extrato, criação de novas contas e listagem de contas existentes. O programa é interativo e guiado por um menu, fornecendo uma experiência de usuário amigável.

## Funcionalidades Principais

### Menu

A função `menu()` exibe um menu de opções para o usuário e retorna a escolha feita. As opções incluem:

1. **Depositar**: Permite ao usuário fazer um depósito na conta.
2. **Sacar**: Permite ao usuário fazer um saque da conta.
3. **Extrato**: Exibe o extrato das operações realizadas.
4. **Nova conta**: Cria uma nova conta vinculada a um usuário.
5. **Listar contas**: Lista as contas existentes no sistema.
6. **Novo usuário**: Cria um novo usuário.
0. **Sair**: Encerra o programa.

### Operações Bancárias

O programa oferece duas operações bancárias principais: depósito e saque.

- A função `depositar(saldo, valor, extrato)` permite ao usuário realizar um depósito na conta. O saldo é atualizado e a operação é registrada no extrato.
- A função `sacar(saldo, valor, extrato, limite, numero_saques, limite_saques)` permite ao usuário realizar um saque. O saldo é atualizado, o extrato é registrado e verificações são feitas para limites de saldo, limite de saques e número de saques diários.

### Exibição de Extrato

A função `exibir_extrato(saldo, extrato)` mostra ao usuário o extrato das operações, incluindo a data e hora de cada transação.

### Criação de Usuários e Contas

- A função `criar_usuario(usuarios)` permite a criação de novos usuários, capturando informações como CPF, nome, data de nascimento e endereço.
- A função `filtrar_usuario(cpf, usuarios)` verifica se um usuário com determinado CPF já existe no sistema.
- A função `criar_conta(agencia, numero_conta, usuarios)` cria uma nova conta vinculada a um usuário existente, usando o número da agência e um número de conta sequencial.

### Listagem de Contas

A função `listar_contas(contas)` exibe detalhes de todas as contas cadastradas, incluindo agência, número da conta e nome do titular.

### Fluxo Principal

A função `main()` é responsável por orquestrar o fluxo principal do programa. Ela mantém um loop contínuo para interação com o usuário, oferecendo as opções do menu e invocando as funções correspondentes de acordo com a escolha do usuário.

### Considerações Finais

O **Simulador Bancário** oferece uma maneira simples de simular operações bancárias básicas. Ele é modular, facilitando a manutenção e expansão das funcionalidades. O código é estruturado, utiliza boas práticas de programação e fornece uma experiência interativa para o usuário.

### A construção desse código apresentou alguns desafios notáveis:

1. **Lógica das Operações Bancárias**: Criar a lógica precisa para as operações de depósito e saque, considerando limites de saldo, limite de saques e registro de extrato, requer uma compreensão sólida das regras bancárias e a habilidade de implementá-las corretamente.

2. **Gestão de Usuários e Contas**: Desenvolver um sistema que gerencia informações de usuários e contas de forma coerente pode ser complexo. Isso inclui verificar se um usuário ou conta já existe, associar corretamente contas a usuários e garantir que as informações sejam mantidas consistentes.

3. **Interação com o Usuário**: Criar um menu interativo e coletar entrada do usuário de forma robusta é um desafio em si. Lidar com diferentes tipos de entrada (números, strings) e garantir que o programa responda de forma adequada a cada escolha do usuário requer consideração cuidadosa.

4. **Validação de Entradas**: Garantir que o programa lide de forma robusta com entradas inválidas, como valores negativos, datas incorretas ou escolhas inválidas de menu, é fundamental para evitar erros e comportamentos inesperados.

5. **Organização e Manutenção**: Manter um código bem organizado, modular e legível é um desafio constante. À medida que o programa cresce, a capacidade de entender e modificar partes específicas do código torna-se crucial.

6. **Tratamento de Datas e Horários**: Lidar com datas e horários de maneira precisa pode ser complexo, especialmente quando se trata de cálculos de limite de saques diários e registros de transações com horários específicos.

7. **Integração de Funções**: Fazer com que as diferentes partes do código funcionem harmoniosamente pode ser um desafio. As funções precisam interagir corretamente e compartilhar informações de forma precisa para garantir que o programa funcione como um todo.

Superar esses desafios exigiu um bom entendimento das regras bancárias, bem como habilidades de programação sólidas para implementar as funcionalidades de maneira precisa e eficaz. Além disso, foi necessário testar e ajustar o código para garantir que ele funcione corretamente em várias situações e com diferentes entradas do usuário.

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=87CEFA&height=120&section=footer"/>
</div>
