# Conferência de Retenções – NFSe

Este documento descreve o procedimento para **conferência das retenções de impostos sobre NFSe**, com foco na validação das informações utilizadas na **EFD-Reinf** e no recolhimento do **ISSQN**.

---

## 📑 Sumário

- [Acesso ao PRISMA](#acesso-ao-prisma)
- [Conferência de Serviços Tomados](#conferência-de-serviços-tomados)
  - [Geração do Relatório](#geração-do-relatório)
  - [Local de Salvamento](#local-de-salvamento)
  - [Observações Importantes](#observações-importantes)
  - [ISSQN – Verificação e Recolhimento](#issqn--verificação-e-recolhimento)
- [Acesso ao SS](#acesso-ao-ss)
  - [Geração de Dados](#geração-de-dados)
  - [Conferência das Retenções](#conferência-das-retenções)
- [Conferência de Serviços Prestados](#conferência-de-serviços-prestados)
- [Conferência e Geração da Guia de ISSQN – Portal da Prefeitura](#conferência-e-geração-da-guia-de-issqn--portal-da-prefeitura)
- [Conclusão](#conclusão)

---

## 📌 Acesso ao PRISMA

---

## 🧾 Conferência de Serviços Tomados

### 📍 Caminho no sistema

- Contabilidade  
  - Contabilidade / Fiscal  
    - **Retenção de Impostos – Serviços Tomados**

---

### 📄 Geração do Relatório

- Salvar em **PDF**
- Nome do arquivo: **Relatório Prisma Retidos 01.2026**

<img width="1128" height="235" alt="image" src="https://github.com/user-attachments/assets/b90335c0-ab2e-4099-9e2e-63de5e7ea92d" />

---

### 💾 Local de Salvamento

```
Servidor: FERROSERVER2 (Y:)
Administração > Contabilidade > Fiscal
Pasta Fiscal - Obrigações Fiscais
FS_Matriz > 2026 > Reinf > 01.2026
```


---

### ℹ️ Observações Importantes

- O **relatório de retenções para a EFD-Reinf** é salvo **na Matriz**, pois:
  - A empresa “mãe” centraliza:
    - **CSRF (CSLL, PIS e COFINS)**
    - **INSS**
- Essa centralização garante **consistência e integridade** das informações enviadas à Reinf.

---

### 🏛️ ISSQN – Verificação e Recolhimento

- A retenção de **ISSQN** é verificada diretamente no **Portal da Prefeitura local**.
- Devem ser gerados:
  - **Guia de recolhimento**
  - **Relatório de lançamentos (Livro)**

#### 📂 Arquivamento

- Os documentos são salvos **conforme a empresa tomadora do serviço**.
- Atualmente:
  - Os **serviços tomados estão concentrados apenas na Loja**
  - Portanto, a conferência do **ISSQN** é realizada **somente para essa empresa**

---

## 🖥️ Acesso ao SS

Antes de iniciar a conferência das retenções no **SS**, é necessário **gerar as informações para a contabilidade**.

---

### ⚙️ Geração de Dados

#### 📍 Caminho no sistema

- Movimentação  
  - Gera dados p/ Livro Caixa  
    - **Geração**

#### 📅 Período

- De **01/01/2026** a **31/01/2026**

<img width="390" height="151" alt="image" src="https://github.com/user-attachments/assets/053af626-b06e-4d17-81cb-3cfddb9de8ba" />

---

### ✅ Conferência das Retenções

#### 📄 Relatório utilizado

- Relatórios Auxiliares Mensais  
  - Impostos Retidos:
    - **COFINS / PIS / CSLL**
    - **IRRF**
    - **INSS**
    - **ISS**

#### ⏰ Vencimento

- Impostos com vencimento **até o dia 20 de cada mês**

#### 📍 Caminho do relatório

<img width="1260" height="739" alt="image" src="https://github.com/user-attachments/assets/8e9e4aa1-31d9-4279-b026-152a23c109c4" />

#### 📊 Exemplo de Relatório

<img width="689" height="376" alt="Relatório de Impostos Retidos" src="https://github.com/user-attachments/assets/f4103718-d627-4dfd-af38-c8bf7dfcdbf9" />

---

## 🧾 Conferência de Serviços Prestados

### 📊 Livro de Serviços – Modelo 1

#### 📍 Caminho no sistema

- Relatórios  
  - Livros Fiscais  
    - **Livro de Serviços – Modelo 1**

<img width="1062" height="678" alt="Livro de Serviços - Modelo 1" src="https://github.com/user-attachments/assets/bc31b9dd-a50f-4e40-bce1-0b66742516f6" />

### ℹ️ Observações

- Este relatório contempla **os serviços prestados pela Loja**, referentes a:
  - Manutenção de ferramentas  
  - Manutenção de máquinas
- As informações servem de base para:
  - Conferência do **ISSQN devido**
  - Validação dos lançamentos no **Portal da Prefeitura**

---

## 🏛️ Conferência e Geração da Guia de ISSQN – Portal da Prefeitura

Este procedimento descreve as etapas para:

- Verificação dos **Serviços Prestados** e **Serviços Tomados**
- Conferência da **apuração do ISSQN**
- Emissão da **guia de recolhimento**

---

### 📄 Relatórios e Guias

`Relatório de Lançamentos / Livro - FS Filial ISS Relatorio Prestador Araras 01_2026`

<img width="1125" height="503" alt="image" src="https://github.com/user-attachments/assets/01aa69d4-116e-42a5-816c-e05dc36289b0" />

`Guia de Recolhimento do ISSQN - FS Filial ISSQN _ Prestador Araras 01_2026`

<img width="795" height="373" alt="image" src="https://github.com/user-attachments/assets/6f82af9f-6b56-4d83-bbdc-5762ea90971a" />

`Relatório de Lançamentos / Livro - FS Filial ISS Relatorio Tomador Araras 01_2026`

<img width="1125" height="503" alt="image" src="https://github.com/user-attachments/assets/aa9e558e-c1ce-4562-98e6-d81bbd6b1712" />

`Guia de Recolhimento do ISSQN - FS Filial ISSQN _ Tomador Araras 01_2026`

<img width="795" height="397" alt="image" src="https://github.com/user-attachments/assets/361cee32-ca24-4918-b26e-ee9da02a8e1d" />

---

### 💾 Local de Salvamento

```

Servidor: FERROSERVER2 (Y:)
Administração > Contabilidade > Fiscal
Pasta Fiscal - Obrigações Fiscais
FS_Filial > 2026 > ISSQN > 01.2026

```


---

## ❗ Conclusão

- Todos os relatórios e informações devem ser **encaminhados para a Priscila e para o Departamento Pessoal até o dia 05 de cada mês**.
- O e-mail contendo as **notas de serviços tomados pela Ferro Store** também deve ser encaminhado, conforme demonstrado abaixo:

<img width="1347" height="446" alt="image" src="https://github.com/user-attachments/assets/914fb6e7-357a-431e-a269-f2dac74e7f29" />

---

🖊️ **Elaborado pelo colaborador:** **Wellington Daniel**
