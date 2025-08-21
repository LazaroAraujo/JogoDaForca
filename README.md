# 웃 JogoDaForca

Um jogo da forca em Java onde o jogador tenta adivinhar uma palavra secreta, letra por letra. A cada erro, uma parte do boneco é desenhada. O jogo termina quando a palavra é descoberta ou o boneco é completado.

## 🛠 Tecnologias Utilizadas

- **Java JDK** (versão recomendada: 21)
- **Gradle**
- **Paradigma**: Programação Orientada a Objetos (POO)
- Entrada/saída via console (CLI)

## ▶️ Como executar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/LazaroAraujo/JogoDaForca.git
   ```
2. **Acesse o diretório**
   ```bash
   cd JogoDaForca
   ```
3. **Compile o projeto**
   ```bash
   ./gradlew shadowjar
   ```
4. **Execute**
   ```bash
   java -jar .\build\libs\JogoDaForca-1.0-SNAPSHOT-all.jar a m e i x a
   ```

---

## 🕹 Como jogar

```
Que comecem os jogos! Tente acertar a palavra oculta
DICA: é uma fruta.
Boa Sorte!
-----        
  |   |        
  |   |        
  |            
  |            
  |            
  |            
=========------

Selecione uma das opções:
1 - Informar uma letra
2 - Verificar status do jogo
3 - Sair do jogo
```

> O usuário deverá selecionar a opção nº1 e informar a letra usada na tentativa de descobrir qual a palavra oculta. O nº de '-' indica a quantidade de letras. Ao atingir o 5º erro o usuário terá perdido o jogo.

---

## 📜 Licença

Este projeto é de uso livre, podendo ser estudado e modificado para fins acadêmicos ou pessoais.

## 💡 Autores

O projeto foi desenvolvido no contexto do desafio de projeto ministrado pela DIO no bootcamp NTT DATA - Java e IA para Iniciantes.

