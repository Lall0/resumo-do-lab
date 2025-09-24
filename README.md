# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

---

## 💻 Notas de Azure (Resumo Rápido)

### **🛡️ Azure Bastion**
* **O que é:** Serviço gerenciado do Azure para **acesso RDP/SSH seguro** a VMs, **direto pelo navegador** 🌐.
* **Para que serve:** Elimina a necessidade de IPs públicos nas VMs, aumentando a **segurança** 🔒.
* **Ponto-chave:** **Dispensa a gestão de um servidor de salto dedicado.**

### **🚧 Jump Server (Servidor de Salto)**
* **O que é:** Uma **VM intermediária** dedicada que você usa para se conectar a outras VMs na rede privada 🖥️➡️🖥️.
* **Para que serve:** Centraliza o acesso e **protege** os servidores internos da exposição direta à internet.
* **Ponto-chave:** **Solução tradicional** (o Bastion é a moderna e recomendada).

### **📜 SLA (Acordo de Nível de Serviço)**
* **O que é:** O **contrato de garantia** do Azure sobre o **tempo que o serviço estará funcionando** (disponibilidade) ⏰.
* **Para que serve:** Se o Azure falhar e não cumprir a porcentagem de *uptime* (ex: 99,95%), o cliente recebe **créditos/desconto** na fatura 💸.
* **Ponto-chave:** **Garantia de Uptime** (tempo de atividade) e compensação financeira.

