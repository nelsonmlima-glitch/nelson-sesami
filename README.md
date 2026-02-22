# 🟠 Nelson SESAMI
> Sales toolkit para vendas B2B em tecnologia para varejo alimentar

Acesse: **[nelsonmlima-glitch.github.io/nelson-sesami](https://nelsonmlima-glitch.github.io/nelson-sesami/)**

---

## 🛠️ Ferramentas

| Módulo | O que faz |
|--------|-----------|
| ✉️ **Follow-up** | Gera e-mail pós-reunião personalizado por cargo, objeção e próximo passo |
| 🎯 **Prospecção** | Mensagens para e-mail frio, LinkedIn, WhatsApp ou por indicação |
| 📊 **Calculadora ROI** | Calcula CAPEX/OPEX, payback e saldo por redução de perdas — modelo Gatecash |
| 📋 **Pipeline** | Kanban arrastar e soltar com 5 etapas (Prospecção → Fechado) |
| 📡 **Radar de Contas** | Monitor de clientes com sinais de mercado, sincronizado em tempo real via Supabase |

---

## 📡 Radar de Contas — Acesso

Ao entrar no módulo Radar, escolha seu perfil:

- 👑 **Admin** — pode adicionar, editar e importar contas
- 👁️ **Visualizador** — somente leitura, ideal para compartilhar com o time

Os dados ficam sincronizados em tempo real via **Supabase** — qualquer alteração feita pelo Admin aparece para todos os Visualizadores em até 30 segundos.

---

## 📥 Importação em Massa (Radar)

Faça upload de planilha `.xlsx`, `.xls` ou `.csv` com as colunas:

| Coluna | Obrigatório |
|--------|-------------|
| Nome | ✅ |
| Segmento | ✅ |
| Prioridade (quente/morno/frio) | ✅ |
| Lojas | — |
| Sinal | — |
| Tipo Sinal (expansão/notícia/concorrente) | — |

---

## 📊 Calculadora ROI — Como usar

1. Informe o nome do projeto (ex: Projeto Gatecash)
2. Preencha **CAPEX** (compra) e/ou **OPEX** (locação mensal)
3. Informe nº de PDVs e faturamento mensal por PDV
4. Preencha os % de perdas totais, perdas não identificadas e meta de redução
5. O resultado mostra automaticamente:
   - **ROI CAPEX** → meses para payback
   - **Saldo OPEX** → positivo ✓ ou negativo ✗

---

## 🗂️ Tecnologias

- **Frontend:** HTML, CSS, JavaScript puro — sem frameworks
- **Banco de dados:** [Supabase](https://supabase.com) (PostgreSQL + REST API)
- **Hospedagem:** GitHub Pages
- **Excel:** [SheetJS / XLSX.js](https://sheetjs.com)

---

## 👤 Autor

**Nelson Lima** — Vendas B2B · Tecnologia para Varejo Alimentar
