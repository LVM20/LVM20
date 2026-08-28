

<img width="1500" height="500" alt="baner" src="https://github.com/user-attachments/assets/030b3f3a-1df7-4bb6-9ea5-13b2acd737fd" />

## 👨‍💻 Sobre

Sou graduado em **Análise e Desenvolvimento de Sistemas** e pós-graduado em **Segurança da Informação**.

Este GitHub reúne os laboratórios e projetos que desenvolvo para estudar e documentar, na prática, como funcionam ambientes corporativos, desde a infraestrutura, identidade e hardening até monitoramento, detecção e resposta a incidentes.

Mais do que estudar ferramentas isoladamente, meu objetivo é construir os ambientes, enfrentar os problemas que surgem durante a implementação e entender como as diferentes camadas de segurança se relacionam.

---

# 🏢 LVM Corporate Lab

O **LVM Corporate Lab** é meu principal projeto.

O objetivo é construir e evoluir uma infraestrutura corporativa simulada, utilizando tecnologias e conceitos encontrados no dia a dia de equipes de **Infraestrutura, Blue Team e SOC**.

Cada etapa do laboratório é documentada em um repositório próprio, mostrando a implementação, os desafios encontrados, as soluções aplicadas e as evidências dos resultados.

---

# ✅ Projetos concluídos

## Projeto 1 — Active Directory Corporate Lab

Construção da infraestrutura de identidade e serviços corporativos.

* Windows Server 2025
* Active Directory Domain Services
* DNS
* Organizational Units (OUs)
* Usuários e grupos
* RBAC
* Compartilhamentos SMB
* Permissões
* Estações Windows ingressadas no domínio
* Configuração de rede

🔗 Repositório:
https://github.com/LVM20/LVM-Active-Directory-Lab

---

## Projeto 2 — Group Policy (GPO) & Windows Hardening

Aplicação de políticas de segurança e hardening sobre a infraestrutura criada no Projeto 1.

* GPOs corporativas
* Políticas de senha
* Account Lockout
* Auditoria de eventos
* Windows Firewall
* Microsoft Defender
* Restrições de usuários
* Hardening de estações Windows
* Baselines e configurações de segurança

🔗 Repositório:
https://github.com/LVM20/LVM-GPO-Hardening-Lab

---

## Projeto 3 — Wazuh SIEM + Sysmon

Implementação da camada de monitoramento e visibilidade de segurança do laboratório.

* Wazuh Server
* Wazuh Agents
* Sysmon
* Coleta e análise de eventos
* Regras de detecção
* MITRE ATT&CK
* Dashboards de monitoramento
* Monitoramento de múltiplos endpoints
* Análise de processos e eventos Windows

Durante essa etapa também trabalhei na migração do laboratório de **VirtualBox para KVM/QEMU**, além da resolução de problemas de rede, DNS, comunicação entre máquinas e integração dos agentes.

🔗 Repositório:
https://github.com/LVM20/LVM-Wazuh-SIEM-Sysmon

---

## Projeto 4 — Incident Detection & Threat Hunting

Evolução do ambiente de monitoramento para uma abordagem prática de **Threat Detection e Threat Hunting** utilizando o **Wazuh SIEM**.

Foram desenvolvidos **10 casos controlados de investigação** em endpoints Windows, analisando processos, usuários, autenticações, linhas de comando e eventos de segurança.

Entre os cenários investigados:

* Criação de contas e alteração de privilégios
* Account Manipulation
* Reconhecimento local
* Reconhecimento interno
* PowerShell
* Windows Command Shell
* Scheduled Tasks
* Windows Services
* PowerShell Encoded Command
* Análise de Process Trees
* Falhas de autenticação
* Limpeza do Windows Security Log
* Correlação de eventos
* Análise de Command Line
* Mapeamento MITRE ATT&CK

Os principais eventos analisados incluíram:

```text
4624 — Successful Logon
4625 — Failed Logon
4688 — Process Creation
4720 — User Account Created
4732 — Group Membership Changed
7045 — Service Installed`
```

🔗 Repositório:
https://github.com/LVM20/4-LVM-Incident-Detection-Threat-Hunting

# 🛣️ Evolução do laboratório

| Status | Projeto                                     |
| ------ | ------------------------------------------- |
| ✅      | Active Directory Corporate Lab              |
| ✅      | Group Policy & Windows Hardening            |
| ✅      | Wazuh SIEM + Sysmon                         |
| ✅     | Incident Detection & Threat Hunting         |
| ✅     | Incident Response                           |
| 🔄     | Vulnerability Management                    |
| 🔄     | Identity & Access Management                |
| 🔄     | Network Security                            |
| 🔄     | Corporate Penetration Testing               |
| 🔄     | Detection Engineering & Security Automation |

---

# 🛠️ Tecnologias e conhecimentos

### Infraestrutura

* Windows Server
* Active Directory
* DNS
* Group Policy
* SMB
* KVM/QEMU
* Linux

### Segurança

* Wazuh
* Sysmon
* SIEM
* MITRE ATT&CK
* Windows Hardening
* Defesa em camadas
* Princípio do menor privilégio
* Conceitos de Zero Trust

### Automação e Scripting

* Python
* Bash
* PowerShell

---

# 🎯 Objetivo

Continuar evoluindo o laboratório para simular cenários cada vez mais próximos de ambientes corporativos reais, conectando **infraestrutura, prevenção, monitoramento, detecção, investigação e resposta a incidentes**.

A ideia é que cada novo projeto não seja apenas a implementação de uma ferramenta, mas uma evolução da arquitetura e da minha capacidade de analisar e proteger um ambiente.

---

## 📂 Repositórios

Todos os projetos do LVM Corporate Lab:

https://github.com/LVM20?tab=repositories
