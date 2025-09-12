## Checklist de estudos AZ-900 (Microsoft Azure Fundamentals)

- [x] Introdução e conceitos de nuvem
	- [x] O que é computação em nuvem (características, benefícios)
	- [x] Modelos de serviço: IaaS vs PaaS vs SaaS
	- [x] Modelos de implantação: Nuvem Pública, Privada, Híbrida
	- [x] CapEx vs OpEx e responsabilidade compartilhada

- [ ] Arquitetura e serviços principais do Azure
	- [ ] Regiões, Zonas de Disponibilidade, Pares de Regiões
	- [ ] Grupos de Recursos e Azure Resource Manager (ARM)
	- [ ] Computação
		- [ ] Máquinas Virtuais (VMs), Conjuntos de Escala (VMSS)
		- [ ] Contêineres: Azure Container Instances, Azure Kubernetes Service (AKS) — visão geral
		- [ ] Funções/Serverless: Azure Functions — visão geral
		- [ ] App Service — visão geral
	- [ ] Rede
		- [ ] Rede Virtual (VNet), Sub-redes, NSG
		- [ ] Balanceadores de Carga (LB), Application Gateway
		- [ ] VPN Gateway, ExpressRoute
		- [ ] DNS do Azure, CDN — noções
	- [ ] Armazenamento
		- [ ] Tipos de conta de armazenamento
		- [ ] Blobs, Arquivos, Filas, Tabelas — cenários e camadas de acesso (Hot/Cool/Archive)
		- [ ] Redundância: LRS, ZRS, GRS, RA‑GRS
	- [ ] Bancos de dados
		- [ ] Azure SQL (PaaS) vs SQL em VM
		- [ ] Cosmos DB — conceitos (APIs, consistência)
		- [ ] Banco de Dados para PostgreSQL/MySQL — visão geral

- [ ] Identidade, acesso e segurança
	- [ ] Microsoft Entra ID (Azure AD): identidades, grupos, locatário
	- [ ] Autenticação vs Autorização, RBAC no Azure
	- [ ] Políticas do Azure (Azure Policy) e Blueprints — noções
	- [ ] Segurança de rede: NSG, Firewall do Azure, Defender for Cloud (visão geral)
	- [ ] Key Vault — gerenciamento de segredos/chaves/certificados
	- [ ] Zero Trust — princípios básicos

- [ ] Governança, conformidade e gerenciamento
	- [ ] Estrutura de gerenciamento: Assinaturas, Grupos de Gerenciamento
	- [ ] Tags e organização de recursos
	- [ ] Bloqueios de recurso (Resource Locks)
	- [ ] Azure Policy: definição, atribuição, efeitos
	- [ ] Microsoft Purview/Compliance Manager — noções

- [ ] Custos, SLAs e ciclo de vida
	- [ ] Calculadora de Preços e Calculadora de TCO
	- [ ] Gerenciamento de custos e orçamentos (Cost Management + Billing)
	- [ ] SLAs de serviço, SKUs e resiliência
	- [ ] Zonas vs conjuntos de disponibilidade e impacto em SLA

- [ ] Ferramentas e métodos de implantação
	- [ ] Portal do Azure, Cloud Shell, CLI, PowerShell — quando usar cada um
	- [ ] Modelos ARM e Bicep — conceitos
	- [ ] Azure Advisor e Service Health — uso básico
	- [ ] Monitoramento: Azure Monitor, Logs, Métricas, Alerts

- [ ] Soluções e casos de uso comuns
	- [ ] Web app simples com App Service + Banco de Dados
	- [ ] Data e Analytics (Data Lake, Synapse) — visão geral
	- [ ] Mensageria (Service Bus, Event Grid, Event Hubs) — noções
	- [ ] Edge/IoT — conceitos básicos

- [ ] Privacidade, confiança e padrões
	- [ ] Privacidade e Proteção de Dados no Azure
	- [ ] Regulatórios e certificações (ISO, SOC, GDPR) — visão geral
	- [ ] Termos do produto e DPA — noções

- [ ] Preparação para a prova
	- [ ] Ler a skill outline oficial (objetivos medidos)
	- [ ] Fazer labs guiados no Portal (criar/deletar recursos com segurança)
	- [ ] Simulados práticos e flashcards de conceitos
	- [ ] Revisar perguntas típicas: SLA, RBAC vs Policy, redundância de storage, IaaS/PaaS/SaaS

### Dicas rápidas
- Foque em “o que é” e “quando usar” cada serviço, não em configuração profunda.
- Decore 3 a 5 exemplos claros para IaaS/PaaS/SaaS e os tipos de redundância de armazenamento.
- Entenda bem RBAC, Policy, regiões/zonas e como isso afeta custo/SLA.