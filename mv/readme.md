# 🚀 Criando máquinas Virtuais na Azure

# 📃 Este guia fornece orientações passo a passo para criar uma máquina virtual (VM) Windows no Portal do Azure.

## Pré-requisitos

- Ter uma conta no Azure. Se você não possui, crie uma conta gratuita [aqui](https://azure.microsoft.com/free).

## Passo a Passo para Criar uma Máquina Virtual

### 1. Acessar o Portal do Azure

- Entre no [Portal do Azure](https://portal.azure.com).

### 2. Criar a Máquina Virtual

1. No painel de pesquisa, digite **máquinas virtuais**.
2. Em **Serviços**, selecione **Máquinas virtuais**.
3. Clique em **Criar** e escolha **Máquina virtual do Azure**.

### 3. Configurações da Máquina Virtual

- **Nome da Máquina Virtual**: Insira `myVM`.
- **Imagem**: Selecione **Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2**.
- **Conta de Administrador**:
  - Nome de usuário: `azureuser`
  - Senha: Mínimo de 12 caracteres, atendendo aos requisitos de complexidade.
- **Regras de Porta de Entrada**:
  - Selecione **Permitir portas selecionadas**.
  - Escolha **RDP (3389)** e **HTTP (80)**.

4. Clique em **Examinar + criar** e, em seguida, clique em **Criar** após a validação.

### 4. Conectar-se à Máquina Virtual

1. Na página de visão geral da VM, selecione **Conectar** > **RDP**.
2. Baixe o arquivo RDP.
3. Abra o arquivo RDP e clique em **Conectar**.
4. Na janela de segurança do Windows, use as credenciais criadas:
   - Nome de usuário: `localhost\azureuser`
   - Senha: a que você definiu.
5. Clique em **OK** e aceite o aviso do certificado, se necessário.

### 5. Instalar o Servidor Web IIS

- Abra o PowerShell na VM e execute o seguinte comando:

  ```powershell
  Install-WindowsFeature -name Web-Server -IncludeManagementTools

### 6. Exibir a Página de Boas-Vindas do IIS
Copie o endereço IP da VM na página de visão geral.
Cole o endereço IP em um navegador para ver a página de boas-vindas do IIS.

### 7. Limpar Recursos
Quando não precisar mais da VM:

Na página da VM, clique em Grupo de recursos.
Selecione Excluir grupo de recursos e confirme digitando o nome do grupo.

### 8. Desligamento Automático
Para gerenciar custos:

Na seção Operações da VM, selecione Desligamento automático.
Ative e defina um horário para o desligamento automático.
Salve as configurações.
Referência
Para mais detalhes, consulte o artigo completo no [Microsoft Learn](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)

---
---

## 📧 Contato

[LinkedIn](https://www.linkedin.com/in/wsawebmaster/)

[wsawebmaster@yahoo.com.br](mailto:wsawebmaster@yahoo.com.br)