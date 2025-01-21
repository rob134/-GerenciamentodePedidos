# Gerenciamento de Pedidos
Um projeto em C# para gerenciamento de pedidos.
# ProjetoAPI
Este é um projeto de API desenvolvido em C# com ASP.NET Core. Ele fornece operações CRUD para gerenciar pedidos e seus itens.
## Tecnologias Utilizadas
- **C#**
- **ASP.NET Core**
- **Entity Framework Core**
- **Banco de Dados In-Memory**
- **Swagger** para documentação
## Como Executar o Projeto
### Pré-requisitos
- .NET SDK instalado
- Um editor de código como Visual Studio Code
- Git instalado
### Passos para Execução
1. Clone este repositório:
   ```bash
   git clone https://github.com/USERNAME/ProjetoAPI.git
   cd ProjetoAPI
   ```
2. Restaure os pacotes NuGet:
   ```bash
   dotnet restore
   ```
3. Execute o projeto:
   ```bash
   dotnet run
   ```
4. Acesse a documentação da API no Swagger: [https://localhost:5001/swagger](https://localhost:5001/swagger)
## Estrutura do Projeto
- **Models**: Contém as classes `Order`, `OrderItem` e `OrderContext` que representam os dados e o contexto do banco.
- **Controllers**: Contém o `OrdersController` que define os endpoints para gerenciar pedidos.
- **Program.cs**: Configura os serviços e middleware da aplicação.
## Endpoints da API
| Método | Endpoint          | Descrição                  |
|--------|-------------------|----------------------------|
| POST   | `/api/orders`     | Cria um novo pedido        |
| GET    | `/api/orders`     | Retorna todos os pedidos   |
| GET    | `/api/orders/{id}`| Retorna um pedido por ID   |
| PUT    | `/api/orders/{id}`| Atualiza um pedido existente |
| DELETE | `/api/orders/{id}`| Remove um pedido existente |
## Testes
O projeto contém testes de unidade utilizando xUnit. Para executá-los:
```bash
   dotnet test
```
## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir **issues** ou enviar **pull requests**.
## Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
