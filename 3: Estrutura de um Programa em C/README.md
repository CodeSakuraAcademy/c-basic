
# Objetivo da Aula

Nesta aula, nosso objetivo é **apresentar a estrutura básica de um programa em C**, explicando seus principais elementos, como:

- Cabeçalho
- Funções
- Blocos de código

Ao final, você será capaz de **criar um programa simples em C**. Vamos lá!

---

## 📝 Visão Geral da Estrutura de um Programa em C

Um programa em C é composto por várias partes, cada uma com uma função específica. Abaixo, estão os principais elementos:

1. **Comentários**:  
   Trechos de texto que não são processados pelo compilador, usados para documentar o código.  
   - Exemplo:
     ```c
     // Este é um comentário de linha
     /* Este é um
        comentário de bloco */
     ```

2. **Diretivas de Pré-Processamento**:  
   Instruções que começam com `#` e são executadas antes da compilação.  
   - Exemplo: `#include <stdio.h>` (inclui bibliotecas).

3. **Função `main()`**:  
   A função principal e obrigatória de todo programa em C. É o ponto de partida da execução.

4. **Corpo da Função `main()`**:  
   Bloco delimitado por `{}` que contém as instruções do programa.

5. **Instruções**:  
   Comandos executáveis, como:
   - Declaração de variáveis
   - Atribuição de valores
   - Chamadas de funções

---

## 🔧 Estrutura Básica de um Programa em C

Aqui está um exemplo de um programa básico que exibe "Hello, World!" na tela:

```c
#include <stdio.h> // Inclui a biblioteca de entrada e saída

int main() {
    printf("Hello, World!\n"); // Exibe a mensagem na tela
    return 0; // Indica que o programa foi executado com sucesso
}
```

### 🛠️ Explicação do Código:
1. **`#include <stdio.h>`**:  
   Inclui a biblioteca `stdio.h`, que contém funções de entrada e saída, como `printf()`.

2. **`int main() { ... }`**:  
   Define a função principal. Ela é obrigatória em qualquer programa C.

3. **`printf("Hello, World!\n");`**:  
   Exibe a mensagem na tela. O caractere `\n` indica uma quebra de linha.

4. **`return 0;`**:  
   Finaliza o programa e retorna o valor `0` ao sistema operacional, indicando sucesso.

---

## 💡 Exercício Prático

**Tarefa**:  
Crie um programa em C que exiba a mensagem **"Olá, Mundo!"** na tela.  

**Dica**: Use o exemplo acima como referência, mas altere a mensagem exibida pelo `printf()`.

---

## 🚀 Compilação e Execução do Programa

Para compilar e executar seu programa, você pode usar o **GCC** (no Linux) ou **MinGW** (no Windows). Aqui estão os passos:

### 1. Compilação:
No terminal, digite o comando para compilar o programa:
```bash
gcc -o programa main.c
```

### 2. Execução:
Depois de compilar, execute o programa com o comando:
```bash
./programa
```

Se tudo estiver configurado corretamente, você verá a mensagem desejada na tela. 🎉

---

**Parabéns!** Você aprendeu a criar e executar seu primeiro programa em C. Continue praticando para fortalecer seus conhecimentos. 🚀
