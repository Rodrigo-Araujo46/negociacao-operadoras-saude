# 🤝 Estratégia e Negociação com Operadoras de Saúde Baseada em Dados

Apoio técnico, analítico e estratégico para hospitais e clínicas em rodadas de negociação e reajuste contratual com operadoras de planos de saúde.

---

## 🎯 O Problema de Negócio
Muitas instituições sentam à mesa de negociação com operadoras sem conhecerem sua real margem de contribuição por procedimento ou convênio, aceitando pacotes deficitários ou reajustes lineares que não cobrem a inflação médica real.

## 💡 Como a Inteligência de Dados Apoia a Negociação
Utilização de histórico real extraído do ERP e modelado em BI/SQL para simular cenários financeiros antes e durante a negociação contratual.

### Frentes de Negociação Estruturadas:
* **Diárias e Taxas Hospitalares:** Análise de custos fixos e variáveis (trabalho a ser realizado com a equipe de custos do hospital) por tipo de acomodação (Enfermaria, Apartamento, UTI), taxas de sala cirúrgica e taxas de observação/pronto-socorro.
* **Honorários Médicos:** Estruturação de modelos baseados em CBHPM (portes, UCO, bandas de reajuste) ou tabelas próprias alinhadas à complexidade assistencial.
* **Materiais e Medicamentos (Mat/Med & OPME):** Simulação de impacto financeiro na adoção de tabelas referenciais (**Brasíndice / SIMPRO**), negociação de deflatores/inflatores, taxas de comercialização e regras de remuneração de OPME.
* **Modelagem de Pacotes (Fee-for-Bundle):** Cálculo de conta média histórica (curva de consumo real) para precificação segura de pacotes cirúrgicos e clínicos, protegendo a margem contra outliers.

---

## 📊 Metodologia de Simulação de Impacto Contratual
1. **Extração da Base Histórica (12 meses):** Levantamento de toda a produção faturada para a operadora alvo.
2. **Simulação "De / Para":** Aplicação da proposta da operadora sobre a produção real passada para medir o impacto exato no faturamento bruto e na margem líquida.
