# Coleta de Tesouros no Dungeon

## 📝 Descrição

Sua missão é vasculhar as salas da masmorra em busca de recompensas lendárias e desafios perigosos. Cada sala pode conter monstros formidáveis, tesouros preciosos ou ambos. Use suas habilidades estratégicas para enfrentar as ameaças e coletar os tesouros!

## 🎯 Objetivo

`Tarefa`: Escreva um programa que simule sua jornada heróica pela masmorra. O programa deve percorrer cada sala e verificar se há tesouros ou monstros. Se você encontrar um tesouro, colecionará a recompensa. Se encontrar um monstro, terá que derrotá-lo para continuar.

>[!NOTE]
> Em nossa resolução utilizamos a função.includes() do JavaScript para verificar se um número (representando a sala atual) está presente nos arrays salasComTesouro e salasComMonstro.

## 📥 Entrada

O número total de salas no dungeon (um número inteiro).

## 📤 Saída

- Sempre que encontrar um tesouro, imprima `Tesouro na sala X!`.
- Sempre que encontrar um monstro, imprima `Monstro na sala X!`.

## ✏️ Tabela de exemplos de entrada e saída

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.


| Entrada  | Saída                                               |
| :------: | :----------------: |
|          | Tesouro na sala 2! |
| 3        | Monstro na sala 3! |
| -------- | ------------------ |
|          | Monstro na sala 2! |
|          | Monstro na sala 3! |
| 4        | Monstro na sala 4! |
| -------- | ------------------ |
| 2        | Monstro na sala 4! |