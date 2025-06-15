# ⚙️ Criação de Máquinas Virtuais no Microsoft Azure

Este documento apresenta um passo a passo completo para criar uma Máquina Virtual (VM) no Microsoft Azure utilizando o portal web. Ideal para iniciantes que desejam entender o processo básico de provisionamento de uma VM.

---

## 🧭 Pré-requisitos

Antes de começar, certifique-se de ter:

- Uma conta ativa no [Microsoft Azure](https://portal.azure.com)
- Um grupo de recursos criado (opcional, pode ser feito durante a criação da VM)
- Conexão estável com a internet

---

## 🚀 Etapas para Criar uma VM

### 1. Acesse o Portal Azure
- Vá até [https://portal.azure.com](https://portal.azure.com)
- Faça login com sua conta Microsoft

---

### 2. Navegue até **Máquinas Virtuais**
- No menu lateral ou no campo de busca, digite: **Máquinas Virtuais**
- Clique em **“Criar”** > **“Máquina Virtual”**

---

### 3. Guia: **Informações Básicas**
- **Assinatura**: Selecione a sua
- **Grupo de Recursos**: Escolha um existente ou crie um novo
- **Nome da VM**: Ex: `vm-dio-lab`
- **Região**: Escolha a mais próxima, ex: `Brazil South`
- **Imagem**: Escolha o sistema operacional (ex: Ubuntu 22.04 LTS ou Windows Server 2022)
- **Tamanho da VM**: Selecione um tipo de máquina (ex: B1s para testes)
- **Usuário e Autenticação**: Escolha entre senha ou chave SSH
- **Portas de Entrada**: Habilite RDP (Windows) ou SSH (Linux)

---

### 4. Guia: **Discos**
- Escolha entre SSD Padrão, Premium ou HDD
- Por padrão, o disco do sistema é suficiente

---

### 5. Guia: **Rede**
- Uma rede virtual será criada automaticamente (ou selecione uma existente)
- Certifique-se de que a **IP pública** está habilitada
- Grupo de segurança da rede (NSG): pode deixar como padrão

---

### 6. Guia: **Gerenciamento, Avançado e Tags**
- Para iniciantes, mantenha as configurações padrão

---

### 7. Guia: **Revisar + Criar**
- O Azure fará a validação das configurações
- Se tudo estiver certo, clique em **“Criar”**

---

## ⏳ Aguardar a Implementação

- O processo levará alguns minutos
- Quando finalizado, clique em **“Ir para o recurso”** para acessar sua VM

---

## 🖥️ Acesso à VM

### Para Linux:
```bash
ssh nome_de_usuario@ip_publico
