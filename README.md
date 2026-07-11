# Introdução à Inteligência Artificial - UFPB

Repositório destinado aos projetos práticos desenvolvidos na disciplina de Introdução à Inteligência Artificial (IA) na Universidade Federal da Paraíba (UFPB).

---

## 📋 Visão Geral do Projeto

O objetivo deste repositório é documentar a evolução de aplicações práticas de IA ao longo do semestre. O projeto está dividido em duas etapas principais, cobrindo desde o aprendizado de máquina supervisionado clássico até abordagens mais avançadas.

---

## 🧠 Reconhecimento de Dígitos Manuscritos com SVM (Julho/2026)

Esta primeira etapa aborda um problema clássico de **classificação supervisionada**: o reconhecimento de padrões em imagens digitais de caligrafia humana. 

Utilizando o conjunto de dados **Digits** (nativo da biblioteca `scikit-learn`), o modelo analisa matrizes de 8x8 pixels (64 atributos numéricos por amostra) para classificar e identificar a qual dígito numérico (de 0 a 9) a imagem corresponde.

### 🛠️ Abordagem Técnico e Modelagem
* **Algoritmo Utilizado:** SVM (Support Vector Machine), instanciado por meio da classe `SVC` (Support Vector Classification).
* **Justificativa:** O SVM é amplamente reconhecido por sua eficácia em espaços de alta dimensionalidade (como os 64 pixels deste dataset), buscando encontrar o hiperplano ideal que maximiza a margem de separação entre as classes.
* **Divisão dos Dados:** 80% para treinamento e 20% para teste, utilizando amostragem estratificada para manter a proporção das classes equilibrada.