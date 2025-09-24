# 🚀 Resumo de Lições Aprendidas no Azure (DIO)

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO e estudos sobre Fundamentos de Nuvem.

## 💻 Notas de Azure 

### **💰 CAPEX (Capital Expenditure)**
* **O que é:** **Despesa de Capital.** Investimento inicial de alto valor em ativos físicos, como a **compra** de servidores ou hardware de rede 🏢.
* **Para que serve:** Adquirir recursos que terão valor e utilidade por um longo período de tempo.
* **Ponto-chave:** Pagamento **adiantado**, valor contabilizado como um **ativo** (típico de *on-premises*).

---

### **💸 OPEX (Operational Expenditure)**
* **O que é:** **Despesa Operacional.** Gastos contínuos para manter um negócio funcionando, como aluguel, energia ou serviços 🔌.
* **Para que serve:** Pagar pelos recursos e serviços **conforme são utilizados** (modelo de nuvem).
* **Ponto-chave:** Pagamento **conforme o uso** (*pay-as-you-go*), valor contabilizado como uma **despesa** (típico da Nuvem).

---

### **☁️ Computação em Nuvem (Cloud Computing)**
* **O que é:** Entrega de serviços de TI (como servidores, armazenamento e softwares) sob demanda, **via internet** 🌐.
* **Para que serve:** Oferecer flexibilidade, escalabilidade e o modelo de pagamento por consumo (OPEX).
* **Ponto-chave:** Acesso a recursos de TI de forma **rápida** e **elástica**.

---

### **Modelo de Nuvem: Público**
* **O que é:** Recursos (hardware e software) de propriedade de um provedor (ex: Azure) e **compartilhados** com múltiplos clientes 🤝.
* **Para que serve:** Oferece maior escalabilidade e menor custo por não exigir gestão de hardware pelo cliente.
* **Ponto-chave:** **Compartilhado** e acessível por qualquer um via internet.

---

### **Modelo de Nuvem: Privado**
* **O que é:** Infraestrutura de nuvem dedicada a uma **única organização**, que pode ser *on-premises* ou hospedada externamente 🔒.
* **Para que serve:** Maior controle, segurança e conformidade, ideal para dados muito sensíveis.
* **Ponto-chave:** **Exclusividade** do ambiente e maior gestão do cliente.

---

### **Modelo de Nuvem: Híbrido**
* **O que é:** Combinação de infraestrutura **Pública + Privada**, permitindo que dados e aplicações se movam entre os dois ambientes 🔗.
* **Para que serve:** Oferecer a flexibilidade da nuvem pública com a segurança da nuvem privada.
* **Ponto-chave:** **Conexão** entre o ambiente *on-premises* (ou privado) e o ambiente público.

---

### **🛡️ Azure Bastion**
* **O que é:** Serviço gerenciado do Azure para **acesso RDP/SSH seguro** a VMs, **direto pelo navegador** 🌐.
* **Para que serve:** Elimina a necessidade de IPs públicos nas VMs, aumentando a **segurança** 🔒.
* **Ponto-chave:** **Dispensa a gestão de um servidor de salto dedicado.**

---

### **🚧 Jump Server (Servidor de Salto)**
* **O que é:** Uma **VM intermediária** dedicada que você usa para se conectar a outras VMs na rede privada 🖥️➡️🖥️.
* **Para que serve:** Centraliza o acesso e protege os servidores internos da exposição direta à internet.
* **Ponto-chave:** **Solução tradicional** (o Bastion é a moderna e recomendada).

---

### **📜 SLA (Acordo de Nível de Serviço)**
* **O que é:** O **contrato de garantia** do Azure sobre o **tempo que o serviço estará funcionando** (disponibilidade) ⏰.
* **Para que serve:** Se o Azure falhar e não cumprir a porcentagem de *uptime* (ex: 99,95%), o cliente recebe **créditos/desconto** na fatura 💸.
* **Ponto-chave:** **Garantia de Uptime** (tempo de atividade) e compensação financeira.

---

## ✨ Benefícios Essenciais da Nuvem

### **⬆️ Alta Disponibilidade & Escalabilidade**
* **O que é:** Capacidade de manter os aplicativos **sempre funcionando** (*High Availability*) e de **aumentar ou diminuir** recursos rapidamente (*Scalability*) conforme a demanda 📈.
* **Para que serve:** Garante que o serviço nunca pare e permite lidar com picos inesperados de tráfego, pagando apenas pelo que for usado.
* **Ponto-chave:** **Uptime** garantido e **crescimento/retração** sob demanda.

---

### **🤝 Confiabilidade & Previsibilidade**
* **O que é:** A nuvem utiliza redundância e *backups* automáticos para garantir a **confiabilidade** de que os dados não serão perdidos. A **previsibilidade** ajuda a estimar custos e desempenho 📊.
* **Para que serve:** Minimiza falhas e oferece estabilidade no desempenho, facilitando o planejamento financeiro e operacional.
* **Ponto-chave:** **Redundância** de dados e **estimativa** de gastos/performance.

---

### **🔒 Segurança & Governança**
* **O que é:** **Segurança** se refere à proteção física e digital da infraestrutura. **Governança** se refere à capacidade de aplicar políticas de acesso e conformidade em toda a organização 🛡️.
* **Para que serve:** O provedor (Azure) oferece segurança robusta de datacenter. A governança permite que a empresa aplique regras internas de forma consistente.
* **Ponto-chave:** **Proteção** de infraestrutura e **aplicação consistente** de regras e políticas.

---

### **⚙️ Capacidade de Gerenciamento**
* **O que é:** Refere-se às ferramentas e aos recursos que facilitam a **operação**, **monitoramento** e **automatização** dos serviços na nuvem 🤖.
* **Para que serve:** Reduz a necessidade de trabalho manual em tarefas rotineiras, como *patching* e *deployment*, permitindo que a equipe se concentre em inovação.
* **Ponto-chave:** **Automação**, **monitoramento** fácil e **redução** de esforço operacional.
```
