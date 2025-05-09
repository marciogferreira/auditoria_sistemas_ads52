
---

### 📄 **1. Diagrama de Rede (simplificado)**

```
[INTERNET]
     |
[Firewall]
     |
[Switch]
 |       |        |
[Servidor AD] [Servidor de Arquivos] [Estação do Usuário]
```

**Observações:**

* O firewall está com firmware desatualizado.
* O servidor de arquivos possui compartilhamentos públicos sem controle de acesso.

---

### 📋 **2. Política de Backup (fictícia)**

> **Política de Backup da TechSoluções Ltda.**
>
> * Backups são realizados diariamente às 23h.
> * São armazenados localmente no mesmo servidor de arquivos.
> * A restauração é testada trimestralmente.
> * Os backups são mantidos por 30 dias.

---

### 📃 **3. Log de Acesso (simulado)**

```
[2025-05-05 22:13:11] Login sucesso - usuário: administrador
[2025-05-05 22:17:45] Acesso negado - usuário: visitante
[2025-05-06 02:04:33] Login sucesso - usuário: administrador
[2025-05-06 02:07:12] Download arquivo: /financeiro/folha_maio.xlsx - usuário: visitante
```

**Observações:**

* Há um download feito por "visitante", o que indica falha no controle de permissões.
* Login de administrador fora do horário comercial.

---

### 🗂️ **4. Inventário de Ativos de TI**

| Equipamento         | Nome de Host | Função                 | Última Atualização |
| ------------------- | ------------ | ---------------------- | ------------------ |
| Servidor Windows    | SRV-AD       | Active Directory       | 2024-11-10         |
| Servidor Linux      | SRV-ARQUIVOS | Armazenamento de dados | 2023-10-01         |
| Estação de Trabalho | PC-JOSE      | Uso administrativo     | 2025-02-15         |

---

### 🗣️ **5. Entrevista Simulada com Gerente de TI**

> **Nome:** João Silva
> **Cargo:** Gerente de TI
>
> “Fazemos o que dá com a equipe pequena que temos. A maioria dos acessos é controlada via login e senha, mas já vi muitos usuários compartilhando credenciais para facilitar. Nosso backup é feito localmente mesmo, nunca tivemos problemas. O firewall não foi mais atualizado porque o fabricante mudou a política de suporte. E sobre os acessos, normalmente ninguém trabalha de madrugada, mas não posso garantir.”

---
