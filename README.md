# 📊 Painel de Monitoramento de Voos – SIROS + Supabase

##  Sobre o Projeto e Links

Este projeto foi desenvolvido como atividade avaliativa da disciplina, com o objetivo de implementar um pipeline de dados completo utilizando **GitHub Actions**, **Supabase** e **GitHub Pages**.

O sistema realiza a coleta automática de informações de voos através da API pública do **SIROS/ANAC**, processa os dados e os armazena em um banco de dados hospedado no Supabase. Em seguida, os dados são disponibilizados em um painel web publicado pelo GitHub Pages.

###  Dashboards online

- SIROS API | GitHub Pages  
https://sn-2026-murilosc.github.io/1-A-A-2Tri-MuriloSouzaC/

- SIROS API | Vercel  
https://sirosdashboard.vercel.app/


## 🖼️ Imagens do Projeto

Abaixo estão algumas capturas de tela do sistema em funcionamento, demonstrando a interface do painel e suas principais funcionalidades.

### 🖥️ Dashboard Principal
<img width="1896" height="912" alt="image" src="https://github.com/user-attachments/assets/b470b664-d404-4e6d-99a4-3eb3b67978e9" />


### 📊 Gráfico de Movimentação
<img width="1897" height="662" alt="image" src="https://github.com/user-attachments/assets/0e5fc7f4-c5b1-403e-8eba-61ccb7bef068" />


### 📈 Histórico de Voos (ANAC)
<img width="1901" height="882" alt="image" src="https://github.com/user-attachments/assets/d76344e1-79fd-40e5-84bb-cf6b6e6e0638" />


### ⚙️ Pipeline de Processamento
<img width="1898" height="837" alt="image" src="https://github.com/user-attachments/assets/a6ca3f35-0802-4dcd-9e79-ccda0dbdee92" />



### 📁 Repositório

https://github.com/SN-2026-MuriloSC/1-A-A-2Tri-MuriloSouzaC

---

## ⚙️ Tecnologias Utilizadas

- Python 3.12  
- GitHub Actions  
- GitHub Pages  
- Supabase  
- PostgreSQL  
- HTML, CSS e JavaScript  
- API SIROS/ANAC  

---

##  Funcionalidades

- Coleta automática de voos via API SIROS/ANAC  
- Filtragem por aeroportos configurados  
- Armazenamento estruturado no Supabase  
- Pipeline automatizado via GitHub Actions  
- Painel web com visualização de chegadas e partidas  
- Filtros por aeroporto, data, companhia aérea e tipo de operação  
- Exibição de horários, aeronaves, assentos e origem/destino  

---

##  Arquitetura do Projeto

```text
API SIROS/ANAC
       ↓
GitHub Actions (ETL / Pipeline)
       ↓
Supabase (PostgreSQL)
       ↓
GitHub Pages / Vercel
       ↓
Painel Web
