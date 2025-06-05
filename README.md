# 🌊 Watercall Solutions - Sistema de Monitoramento de Reservatório Contra Enchentes

## 📌 Descrição do Problema

A ocorrência de enchentes e transbordamentos de reservatórios é um problema comum em diversas regiões, principalmente durante o período de chuvas. A ausência de monitoramento adequado dos níveis de água impede ações preventivas, gerando prejuízos materiais e riscos à segurança da população.

## 🎯 Objetivo

Este projeto propõe o desenvolvimento de um sistema automatizado para **monitoramento do nível de água em reservatórios**, com alerta visual e sonoro, exibindo também o volume estimado em litros em tempo real por meio de um display LCD.

---

## 🛠️ Visão Geral da Solução

O sistema utiliza um **sensor ultrassônico HC-SR04** para medir a distância da superfície da água até o sensor, calcula o volume disponível no reservatório e aciona **LEDs indicadores** de nível junto a um **buzzer de alarme** em caso de nível crítico.

### Funcionalidades:

- Medição do nível de água em centímetros
- Cálculo do volume em **litros**
- Sinalização por **LEDs coloridos**
  - 🔴 Vermelho: Cheio
  - 🟠 Laranja: Alto
  - 🟡 Amarelo: Médio
  - 🟢 Verde: Baixo
  - 🔵 Azul: Crítico
- Alarme sonoro em nível crítico
- Exibição do volume atual no display LCD

---

## 🧪 Simulação do Projeto

**Como usar:**
1. Clique em “Start Simulation”
2. Veja o volume no display LCD e os LEDs mudando conforme o nível
3. Edite a distância manualmente no sensor para simular variações

### 🔗 Tinkercad (opcional)

[👉 Acesse o projeto no Tinkercad]([https://www.tinkercad.com/things/SEU_LINK_AQUI](https://www.tinkercad.com/things/baqUQUgbciy-global-solution-edge-computing/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard%2Fdesigns%2Fcircuits))

---

## 🎥 Vídeo Demonstrativo

📽️ Assista ao funcionamento completo do sistema:

[![Assista no YouTube](https://img.youtube.com/vi/SEU_ID_DO_VIDEO/0.jpg)]

---

## 📐 Fórmulas Utilizadas

- Altura máxima do reservatório: **334 cm**
- Área da base (exemplo): **10.000 cm²**
- Altura útil da água: `A = 334 - Cm`
- Volume em litros: `L = (A * ÁreaBase) / 1000`

---

## 🧾 Lógica de Níveis

| Distância (Cm) | Situação         | LED          | Alarme |
|----------------|------------------|--------------|--------|
| ≤ 110.33       | Cheio            | 🔴 Vermelho  | ❌     |
| 110.34–165.5   | Alto             | 🟠 Laranja   | ❌     |
| 165.51–220.66  | Médio            | 🟡 Amarelo   | ❌     |
| 220.67–275.833 | Baixo            | 🟢 Verde     | ❌     |
| > 275.833      | Crítico/Vazio    | 🔵 Azul      | ✅     |

---

## 🖼️ Esquema do Circuito

![Esquema de montagem](![Global Solution - Edge Computing](https://github.com/user-attachments/assets/f7985c60-a6a9-4f88-9635-1bea8e4bc75d)
)

---
## 🏢 Sobre a Empresa

**Watercall Solutions** é uma startup focada em soluções acessíveis de monitoramento e automação para prevenção de enchentes, controle hídrico e segurança residencial. Nosso objetivo é trazer segurança, praticidade e inovação para todos os públicos.

---

## 👥 Integrantes

- Ulisses Ribeiro
