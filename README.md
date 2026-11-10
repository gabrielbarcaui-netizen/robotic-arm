# 🦾 Robotic Arm - Concept Design & Mechanical Development

O objetivo principal é projetar uma estrutura otimizada, funcional e estruturalmente validada antes da fase de prototipagem física.


## 🛠️ Tecnologias e Ferramentas

* **Modelagem 3D & CAD:** Autodesk Fusion 360
* **Engenharia Analítica:** Python / Mathcad / Excel (para automação dos cálculos de torque e momento)
* **Simulação Estrutural:** Análise por Elementos Finitos (FEA) via Fusion 360 Simulation
* **Áreas de Domínio:** Cinemática, Dinâmica dos Corpos Rígidos, Resistência dos Materiais e Elementos de Máquinas


## 📐 Metodologia e Cálculos de Engenharia

Para garantir que a escolha dos motores (servos/steppers) e o dimensionamento das peças sejam precisos, o projeto abrange as seguintes etapas analíticas:

### 1. Estatística e Distribuição de Massa
* **Mapeamento de Peso e Volume:** Estimativa de massa de cada elo (link) e componente auxiliar a partir da densidade dos materiais selecionados no Fusion 360 (ex: PLA/PETG/Alumínio).
* **Centro de Gravidade (CG):** Cálculo da posição do CG acumulado em função do ângulo de abertura das articulações.

### 2. Dinâmica e Esforços de Torque
* **Torque Estático nas Juntas:** Determinação do momento fletor máximo ($M = F \cdot d$) atuante nos eixos da base, ombro e cotovelo na condição de máxima extensão (pior cenário).
* **Torque Dinâmico:** Consideração das acelerações angulares esperadas para garantir reserva de potência nos atuadores durante a movimentação.

### 3. Análise Estrutural e Resistência dos Materiais
* **Cálculo de Cisalhamento e Flexão:** Avaliação das tensões atuantes nos pinos de articulação, parafusos e eixos de transmissão.
* **Análise de Tensão por FEA (Elementos Finitos):** Identificação de regiões de concentração de tensão (*stress concentration*) nos elos do braço robótico sob carga útil nominal.
* **Fator de Segurança (FS):** Dimensionamento geométrico visando manter um FS adequado contra deformação plástica ou falha por fadiga.


## 🚀 Roadmap de Desenvolvimento *(Work in Progress)*

- [x] **Fase 1:** Pesquisa de conceitos, levantamento de referências técnicas e definição das dimensões gerais no Autodesk Fusion 360.
- [ ] **Fase 2:** Modelagem detalhada das peças, arranjo das juntas articuladas e encaixe dos atuadores *(Em Andamento)*.
- [ ] **Fase 3:** Formulação e execução da planilha de cálculos mecânicos (Torque, Peso, Matriz Cinemática).
- [ ] **Fase 4:** Simulação estrutural (FEA) das peças críticas e otimização topológica para redução de massa.
- [ ] **Fase 5:** Validação final e preparação dos arquivos STL para impressão 3D / fabricação.


## 🖼️ Galeria & Progresso CAD

*(Imagens e renderizações do modelo 3D no Fusion 360 serão adicionadas conforme a evolução do projeto).*


### 👤 Autor
**Gabriel Barcauí Guedes**  
Estudante de Engenharia Mecânica – CEFET/RJ  
[LinkedIn](https://www.linkedin.com/in/gabriel-guedes-a63479354/) | [GitHub](https://github.com/gabrielbarcaui-netizen)
