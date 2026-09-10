# Ambientes de TI em Nuvem: Desafios de Implantação e Otimização de Custos na Migração de Infraestrutura On-Premises

Repositório público contendo o Trabalho de Conclusão de Curso (TCC) apresentado ao Centro Universitário UniCarioca como requisito para obtenção do título de Especialista em Computação em Nuvem: Arquiteto de Operações e Segurança.

* **Autor:** Wellington de Alcantara
* **Perfil Profissional (LinkedIn):** [linkedin.com/in/alcantaraw](https://www.linkedin.com/in/alcantaraw/)
* **Artigo Completo (PDF):** [TCC - Wellington Alcantara - 2016202296.pdf](./TCC%20-%20Wellington%20Alcantara%20-%202016202296%20(1).pdf)

---

## 📌 Resumo Executivo

A migração de ambientes on-premises para a nuvem representa um desafio estratégico crítico em organizações com infraestruturas heterogêneas. Embora a computação em nuvem ofereça previsões de redução de custos operacionais (20% a 30%), cerca de 60% das empresas enfrentam gastos não planejados e *bill shock* decorrentes de dimensionamento inadequado e custos ocultos de transferência e armazenamento.

Este trabalho analisa os vetores técnicos, operacionais e financeiros da migração, demonstrando como a governança por meio de **FinOps** e a estruturação de um **Cloud Center of Excellence (CCoE)** são essenciais para assegurar previsibilidade orçamentária, alcançando reduções de custos mensais de até 35%. O estudo estabelece ainda critérios técnicos objetivos sobre cenários em que a retenção de sistemas legados on-premises é recomendada e avalia comparativamente os principais provedores de mercado (**AWS, Azure, GCP e OCI**).

---

## 🧭 Estrutura do Estudo

1. **Fundamentação Técnica e Modelos Econômicos:** Análise comparativa entre infraestruturas On-premises (CAPEX) versus Cloud (OPEX) e modelos IaaS, PaaS e SaaS.
2. **Desafios em Ambientes Híbridos:** Estratégias de conectividade, conformidade regulatória (LGPD, BACEN), segurança sob o modelo de responsabilidade compartilhada e suporte a SOs legados (Solaris, AIX, Windows Server legados).
3. **Estratégias de Migração:** Critérios práticos para *Rehosting (Lift and Shift)*, *Replatforming (Move and Improve)*, *Refactoring (Cloud-Native/Strangler Fig)* e *Repurchasing (SaaS)*.
4. **Governança Financeira & FinOps:** Implementação de alocação por tags, automação de desligamento, políticas de instâncias reservadas/Savings Plans e prevenção de desperdícios de rede (egress).
5. **Benchmark entre Provedores:** Comparativo detalhado de latência, throughput de storage, IOPS, custos de licenciamento e suporte a legados entre AWS, Azure, GCP e Oracle Cloud (OCI).
6. **Estudos de Caso Reais:** Análise de dados públicos e implementações corporativas (Banco Itaú, Magazine Luiza e Embraer).

---

## 📊 Síntese Comparativa de Provedores

| Dimensão Técnica / Financeira | AWS | Microsoft Azure | Google Cloud (GCP) | Oracle Cloud (OCI) |
| :--- | :--- | :--- | :--- | :--- |
| **Ponto Forte de Destaque** | Maturidade global e ecossistema de microsserviços | Integração com ecossistema corporativo (AD, Arc) | Processamento de dados massivos e Big Data | Cargas transacionais e bancos Oracle (Exadata) |
| **Benefício de Licenciamento** | Bring Your Own License (BYOL) | Azure Hybrid Benefit (redução de até 45%) | Descontos por uso sustentado automáticos | Universal Credits + BYOL Oracle |
| **Modernização de Legados** | AWS Mainframe Modernization | Suporte estendido para legados Windows Server | Containerização de VMs legadas (Anthos) | Suporte nativo a Solaris e arquitetura SPARC/x86 |
| **Ferramenta Nativa de FinOps** | AWS Cost Explorer / Budgets | Azure Cost Management | Cloud Billing Reports | OCI Budgets & Cost Analysis |

---

## 🛠️ Competências Relacionadas

* **Cloud Architecture:** Nuvem Híbrida, Estratégias Multicloud, IaaS/PaaS, Kubernetes, Conectividade Dedicada.
* **FinOps & Governança:** Redução de TCO, Modelagem OPEX, Rightsizing, Gestão de Egress, Estruturação de CCoE.
* **Engenharia de Sistemas:** Integração de Aplicações Críticas, Modernização de Sistemas Legados, Continuidade Operacional.

---

## 🔗 Conexões e Contato

* **Repositório:** [github.com/alcantaraw/tcc](https://github.com/alcantaraw/tcc)
* **LinkedIn:** [Wellington de Alcantara](https://www.linkedin.com/in/alcantaraw/)
* **E-mail:** [alcantaraw@gmail.com](mailto:alcantaraw@gmail.com)
