# Universidade Federal do Tocantins

**Disciplina**: Estrutura de Dados 1  
**Professor**: Rafael Lima  
**Prazo**: 21/05/2025  
**Aluno**: Gabriel Henrique Coldebella de Souza    

---
  
# 🧬 Labirinto com Algoritmos Genéticos

Projeto acadêmico desenvolvido para a disciplina de **Estrutura de Dados 1**.

---
  
## 🧠 Objetivo

O sistema simula indivíduos de uma mesma espécie que percorrem um labirinto com base em movimentos gerados por algoritmos genéticos. 
O desempenho (fitness) de cada indivíduo é avaliado de acordo com sua eficiência em encontrar a saída do labirinto.

---
  
## 🧱 Estrutura do Projeto

projetoLabirinto/
1. main.c # Função principal
2. labirinto.c/.h -> Geração e manipulação do labirinto
3. individuo.c/.h -> Criação, importação e movimentação dos indivíduos
4. labirinto.txt -> Arquivo com a estrutura do labirinto
5. individuo.txt -> Arquivo com os dados dos indivíduos

---
  
## 💻 Compilação

Use o comando :  
gcc main.c labirinto.c individuo.c -o programa.exe -lm

Em seguida, execute:  
./programa.exe
