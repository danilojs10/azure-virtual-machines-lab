# azure-virtual-machines-lab

# 🌐 Gerenciamento de Máquinas Virtuais no Microsoft Azure

Este repositório faz parte do desafio da DIO sobre uso do Azure. Aqui, você encontrará anotações, dicas e experiências práticas no gerenciamento de Máquinas Virtuais (VMs) na plataforma.

---

## 📚 Conteúdo

- [Resumo do Aprendizado](#resumo-do-aprendizado)
- [Passo a Passo: Criando sua VM](#passo-a-passo-criando-sua-vm)
- [Dicas Úteis](#dicas-úteis)
- [Erros Comuns](#erros-comuns)
- [Capturas de Tela](#capturas-de-tela)

---

## ✅ Resumo do Aprendizado

- Criação e gerenciamento de VMs no portal Azure
- Configuração de recursos (CPU, RAM, disco)
- Acesso remoto via RDP/SSH
- Regras de firewall e segurança
- Monitoramento e boas práticas de uso

---

## ⚙️ Passo a Passo: Criando sua VM

> Detalhes completos em [`vm-criacao.md`](./vm-criacao.md)

1. Acesse o [portal do Azure](https://portal.azure.com)
2. Navegue até **Máquinas Virtuais > Criar**
3. Configure:
   - Nome, região, imagem (Ubuntu/Windows), tipo de máquina
   - Rede virtual, grupo de segurança, disco, etc.
4. Revise e clique em **Criar**

---

## 💡 Dicas Úteis

> Dicas adicionais em [`dicas.md`](./dicas.md)

- Use o Azure Cloud Shell para comandos rápidos
- Automatize via Azure CLI ou ARM Templates
- Monitore VMs com Azure Monitor

---

## ❗ Erros Comuns

> Mais erros documentados em [`erros-comuns.md`](./erros-comuns.md)

- Problemas de acesso por SSH
- Falha ao alocar IP público
- Restrições de região

---

## 🖼️ Capturas de Tela

As imagens estão organizadas na pasta `/images` para facilitar a visualização dos passos.

---

## 🧾 Referências

- [Documentação oficial Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- [GitHub Docs](https://docs.github.com)
