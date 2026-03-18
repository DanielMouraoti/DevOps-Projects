# DevOps Projects — Daniel Mourão

Portfólio de estudos e projetos práticos de **DevOps / Cloud (AWS)**.  
Aqui eu versiono minha evolução, notas e implementações (Terraform, Linux, CI/CD, etc.).

> **Crédito / referência:** este trabalho foi iniciado com base no repositório `NotHarshhaa/DevOps-Projects`.  
> Este repositório contém **minhas adaptações** e meu progresso.

---

## Visão rápida

- **Foco:** AWS + Terraform + automação + boas práticas
- **Objetivo:** aprender fazendo e manter um histórico real de evolução
- **Status:** em progresso (atualizado em **2026-03-18**)

---

## Projetos

### 01) AWS 3-Tier com Terraform (ALB + ASG + RDS)
**Pasta:** `DevOps-Project-01/`

O que tem aqui:
- Infra modular com Terraform (network + security + compute + database)
- Boas práticas de variáveis (`terraform.tfvars.example`)
- Passo a passo para subir e destruir o ambiente

Acesse: `DevOps-Project-01/infrastructure/`

**Como rodar (resumo):**
```bash
cd DevOps-Project-01/infrastructure
terraform init
terraform plan
terraform apply
```

**Destruir (evitar custo):**
```bash
terraform destroy
```

> Atenção: **RDS** e **NAT Gateway** podem gerar custo se ficarem ligados.

---

## Estrutura do repositório (resumo)

- `DevOps-Project-01/` — projeto principal (AWS + Terraform)

---

## Próximos passos (roadmap)
- [ ] Melhorar README do Projeto 01 com diagrama e outputs
- [ ] Padronizar nomes e variáveis (validações e defaults)
- [ ] Adicionar troubleshooting (erros comuns do Terraform/AWS)

---

## Licença
Se existir um arquivo `LICENSE` neste repositório, ele define os termos de uso.
