# Jogo de Adivinhação

Este é um simples jogo de adivinhação criado em **Java**, onde o jogador tem **5 tentativas** para adivinhar um número aleatório gerado pelo programa.

## Como funciona?
1. O programa gera um número aleatório entre **0 e 100**.
2. O jogador deve digitar um número e receberá dicas se o valor digitado é **maior ou menor** que o número gerado.
3. O jogador tem **5 tentativas** para acertar.
4. Se acertar, o programa exibe uma mensagem de sucesso.
5. Se errar todas as tentativas, o programa exibe o número correto.

## Tecnologias Utilizadas
- **Java**
- **Random** (para gerar números aleatórios)
- **Scanner** (para entrada de dados do usuário)

## Como executar o jogo?
1. Certifique-se de ter o **Java JDK** instalado.
2. Copie o código do arquivo `JogoAdivinhacao.java`.
3. Compile o arquivo no terminal:
   ```sh
   javac JogoAdivinhacao.java
   ```
4. Execute o programa:
   ```sh
   java JogoAdivinhacao
   ```
5. Insira um número e tente adivinhar!

## Exemplo de Execução
```
Digite um número entre 0 e 100: 50
O número digitado é menor que o número gerado.
Digite um número entre 0 e 100: 75
O número digitado é maior que o número gerado.
Digite um número entre 0 e 100: 62
Parabéns, você acertou o número em 3 tentativas!
```

## Melhorias Futuras
- Adicionar modo **fácil/médio/difícil** com diferentes quantidades de tentativas.
- Criar uma interface gráfica para o jogo.
- Permitir que o jogador jogue novamente sem precisar reiniciar o programa.

Divirta-se jogando! 🎮

