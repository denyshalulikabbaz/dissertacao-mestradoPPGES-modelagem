# Dissertação de Mestrado – Modelagem e Simulação de Processos

Este repositório contém os modelos e códigos desenvolvidos no âmbito da dissertação de mestrado no Programa de Pós-Graduação em Engenharia de Sistemas (PPGES).

---

## 📌 Objetivo

Desenvolver e integrar modelos computacionais para simulação de processos envolvendo:

- Reforma seca do biogás (Dry Reforming of Methane – DRM)
- Produção de gás de síntese (syngas)
- Síntese de Fischer-Tropsch (FT) para obtenção de hidrocarbonetos líquidos
- Integração entre simulação de processos e modelagem matemática

---

## 🔄 Fluxo do Processo

Biogás → DRM → Produção de syngas → FT → Hidrocarbonetos líquidos

---

## ⚙️ Metodologia

Os modelos foram desenvolvidos utilizando:

- Simulação de processos no DWSIM
- Modelagem matemática em Python
- Equação de estado de Peng-Robinson para descrição termodinâmica
- Modelos cinéticos heterogêneos do tipo Langmuir-Hinshelwood-Hougen-Watson (LHHW)

A abordagem adotada combina simulação de processos com implementação de modelos matemáticos, permitindo maior flexibilidade na análise e integração dos sistemas de reforma e síntese.

---

## 📁 Estrutura do Repositório
dwsim/
Arquivos de simulação (.dwxmz)

python/
Scripts para modelagem, integração e cálculos auxiliares

---

## ▶️ Como utilizar

### 1. Simulações no DWSIM
- Abrir os arquivos `.dwxmz` na pasta `/dwsim`
- Executar as simulações conforme configuradas
- Verificar condições operacionais (temperatura, pressão e vazões)

### 2. Scripts em Python
- Executar os scripts da pasta `/python` utilizando Python 3.x
- Garantir que as dependências estejam instaladas (quando aplicável)
- Utilizar os scripts para cálculos auxiliares e integração de modelos

---

## 🔁 Reprodutibilidade

Este repositório foi estruturado para permitir a reprodução dos resultados apresentados na dissertação.

Para isso, recomenda-se:

- Utilizar o software DWSIM
- Executar os arquivos de simulação fornecidos
- Rodar os scripts Python conforme descrito
- Manter as mesmas condições operacionais utilizadas no estudo

---

## 📊 Aplicações

Os modelos desenvolvidos permitem:

- Avaliação de desempenho de reatores catalíticos
- Estudo do efeito de variáveis operacionais
- Integração entre processos de reforma e síntese
- Análise da produção de combustíveis sintéticos (C5+)

---

## 📚 Contexto Acadêmico

Este trabalho está inserido no contexto de:

- Valorização do biogás como fonte renovável
- Redução de emissões de gases de efeito estufa
- Produção de combustíveis sustentáveis
- Modelagem e simulação de processos químicos

---

## 👨‍🎓 Autor

Denys Haluli Kabbaz  
Programa de Pós-Graduação em Engenharia de Sistemas (PPGES)

---

## 📎 Observações

Este repositório possui finalidade acadêmica e visa garantir transparência, rastreabilidade e reprodutibilidade dos resultados obtidos.
