# resume-dio-azure

# ☁️ Azure para Desenvolvedores:

## 1. Computação em Nuvem: Domínio do Objetivo
**Principais funcionalidades no Azure:**
- ⚡ **Escalabilidade Elástica**  
  - Auto-scaling com *Virtual Machine Scale Sets*
  - Balanceamento de carga integrado
- 🛡️ **Alta Disponibilidade**  
  - *Availability Zones/Set* para tolerância a falhas
  - SLAs até 99.99%
- 🤖 **Gerenciamento Automatizado**  
  - *Azure App Service* (PaaS) para apps Java
  - *Azure Functions* (serverless) para execução sem infraestrutura

## 2. Modelos de Nuvem Comparados
| Modelo | Serviços Azure              | Casos de Uso Java               |
|--------|-----------------------------|--------------------------------|
| **IaaS** | Máquinas Virtuais (VMs)     | Apps legadas/complexas         |
| **PaaS** | Azure Spring Apps, Azure SQL | Microserviços, APIs REST       |
| **SaaS** | Azure DevOps, Office 365    | CI/CD e gestão de aplicações   |
| **Híbrida** | Azure Arc                 | Integração on-premise + nuvem |

## 3. CapEx vs. OpEx no Azure
### 💰 Redução de CapEx (Investimento Inicial)
- ✅ Zero custo com hardware físico  
- ✅ Eliminação de gastos com infraestrutura local  
- ✅ Previsibilidade orçamentária  

### 🔄 Vantagens OpEx (Custos Operacionais)
- ⏱️ Pagamento por uso (ex: segundos de execução no Functions)  
- 📉 Economia de escala com *Reserved Instances*  
- 📊 Controle em tempo real com *Azure Cost Management*  

## 🛠️ Serviços Azure Essenciais para Java
| Categoria       | Serviços Recomendados                     |
|-----------------|-------------------------------------------|
| **Computação**  | App Service, Container Apps, Functions    |
| **Banco de Dados** | Azure SQL, Cosmos DB, Database for MySQL |
| **DevOps**      | Azure DevOps (CI/CD pipelines)            |
| **Monitoramento**| Application Insights, Log Analytics      |

## 🚀 Estratégias Recomendadas
```mermaid
graph LR
A[App Java] --> B{Modelo?}
B -->|Controle total| C[IaaS: VMs]
B -->|Produtividade| D[PaaS: App Service]
B -->|Eventos pontuais| E[Serverless: Functions]
