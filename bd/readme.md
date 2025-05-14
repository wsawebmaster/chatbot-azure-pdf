# 🚀 Criando uma Instância de Banco de Dados na Azure

# 📃 Este guia fornece orientações passo a passo para criar uma instância de banco de dados no Portal do Azure.

## Pré-requisitos

- Ter uma conta no Azure. Se você não possui, crie uma conta gratuita [aqui](https://azure.microsoft.com/free).

## Passo a Passo para Criar uma Instância de Banco de Dados

### 1. Acessar o Portal do Azure

- Entre no [Portal do Azure](https://portal.azure.com).

### 2. Criar a Instância de Banco de Dados

1. No painel de pesquisa, digite **Banco de Dados**.
2. Em **Serviços**, selecione **Banco de Dados SQL**.
3. Clique em **Criar** para iniciar a configuração da instância.

### 3. Configurações da Instância de Banco de Dados

- **Nome do Banco de Dados**: Insira um nome, como `meuBancoDeDados`.
- **Assinatura**: Selecione sua assinatura do Azure.
- **Grupo de Recursos**: Escolha um grupo existente ou crie um novo.
- **Servidor**: Selecione um servidor existente ou crie um novo servidor SQL.
  - **Nome do servidor**: Insira um nome exclusivo.
  - **Administração**: Forneça um nome de usuário e senha, atendendo aos requisitos de complexidade.
- **Configurações de Desempenho**: Escolha a opção de desempenho desejada (por exemplo, S0, S1, etc.).

4. Clique em **Examinar + criar** e, em seguida, clique em **Criar** após a validação.

### 4. Conectar-se ao Banco de Dados

1. Após a implantação, vá para a página de visão geral do banco de dados.
2. Anote o **endereço do servidor** e as credenciais de administrador que você configurou.
3. Use um cliente SQL, como **SQL Server Management Studio** ou **Azure Data Studio**, para conectar ao banco de dados.

### 5. Configurar Firewall

- No portal, vá para as configurações de **Firewall e redes virtuais** do servidor SQL.
- Adicione seu endereço IP à lista de permissões para permitir a conexão.

### 6. Criar Tabelas e Inserir Dados

- Conecte-se ao banco de dados usando seu cliente SQL e execute scripts SQL para criar tabelas e inserir dados.

### 7. Limpar Recursos

Quando não precisar mais do banco de dados:

1. Na página do banco de dados, clique em **Grupo de recursos**.
2. Selecione **Excluir grupo de recursos** e confirme digitando o nome do grupo.

### 8. Monitoramento e Desempenho

- Utilize o Azure Monitor para acompanhar o desempenho do banco de dados e configurar alertas conforme necessário.

## Referência

Para mais detalhes, consulte o artigo completo no [Microsoft Learn](https://learn.microsoft.com/pt-br/azure/sql-database/sql-database-get-started-portal).

---

## 📧 Contato

[LinkedIn](https://www.linkedin.com/in/wsawebmaster/)

[wsawebmaster@yahoo.com.br](mailto:wsawebmaster@yahoo.com.br)