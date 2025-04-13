# ☁️ Azure - Conceitos Fundamentais

Este repositório contém um resumo dos principais conceitos relacionados ao uso do **Microsoft Azure**, incluindo Máquinas Virtuais, Zonas de Disponibilidade, Redundância de Armazenamento e SLA.

---

## 🔹 Máquina Virtual (VM)

As **VMs (Virtual Machines)** do Azure permitem executar sistemas operacionais e aplicações em um ambiente virtualizado, com total controle sobre recursos e configurações.

- Suporte a Windows e Linux.
- Escalabilidade vertical e horizontal.
- Usadas em desenvolvimento, testes e ambientes de produção.
- Integração com redes virtuais, balanceadores de carga e serviços de armazenamento.

---

## 🔹 Zonas de Disponibilidade (Availability Zones)

As Zonas de Disponibilidade são localizações físicas isoladas dentro de uma mesma região do Azure. Cada zona possui sua própria infraestrutura de energia, rede e refrigeração.

- Garantem **alta disponibilidade** e **tolerância a falhas**.
- Ideal para distribuir VMs e serviços críticos.
- Aumentam a resiliência do sistema.

---

## 🔹 Redundância de Armazenamento

O Azure oferece diferentes opções de replicação para garantir segurança e disponibilidade dos dados:

| Tipo      | Descrição                                | Localização das Réplicas                        |
|-----------|-------------------------------------------|-------------------------------------------------|
| **LRS**   | Locally Redundant Storage                 | 3 cópias no mesmo data center                   |
| **ZRS**   | Zone-Redundant Storage                    | Cópias em diferentes zonas de disponibilidade   |
| **GRS**   | Geo-Redundant Storage                     | Cópias em outra região geográfica               |
| **RA-GRS**| Read-Access Geo-Redundant Storage         | GRS com acesso de leitura à réplica secundária  |

---

## 🔹 SLA (Service Level Agreement)

O SLA define os níveis mínimos de serviço garantidos pela Microsoft, geralmente relacionados à **disponibilidade**.

- Exemplo: **99,99%** de SLA para VMs distribuídas entre zonas.
- Garante confiança no serviço e continuidade do negócio.
- Quebras de SLA podem gerar **créditos financeiros** ao cliente.

### ⏱️ Tabela de Disponibilidade e Tempo Máximo de Indisponibilidade

| SLA (%)   | Tempo de Inatividade por Mês | Tempo de Inatividade por Ano |
|-----------|-------------------------------|-------------------------------|
| 99%       | ~7 horas e 18 minutos         | ~3 dias e 15 horas            |
| 99,9%     | ~43 minutos                   | ~8 horas e 45 minutos         |
| 99,95%    | ~21 minutos                   | ~4 horas e 22 minutos         |
| 99,99%    | ~4 minutos                    | ~52 minutos                   |
| 99,999%   | ~25,9 segundos                | ~5,26 minutos                 |

---

##  Links Úteis

- [Documentação oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Preços e SLA do Azure](https://azure.microsoft.com/pt-br/support/legal/sla/)
- [Calculadora de Preços do Azure](https://azure.microsoft.com/pt-br/pricing/calculator/)

---

##  Autor

**Lucas Dias Bernardes**  

Estudante de Ciência da Computação | UNIP
