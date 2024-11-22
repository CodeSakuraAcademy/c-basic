
# Configurando Seu Ambiente de Programação em C

Para começar a programar em C, você precisará de dois elementos básicos:

1. **Um editor de código**: Escolha aquele que você preferir. Algumas opções populares são:
   - **Visual Studio Code (VS Code)** – amplamente utilizado, flexível e repleto de recursos.
   - **Sublime Text**, **Atom**, **Notepad++**, entre outros.

2. **Um compilador de código C**: Esse será responsável por transformar seu código em um programa executável. Algumas opções são:
   - **Clang** (no Linux)
   - **GCC**
   - **MinGW** (no Windows)

---

## 🛠️ Instalando as Ferramentas Necessárias

### 🔷 **Visual Studio Code**
1. Acesse o site oficial do [Visual Studio Code](https://code.visualstudio.com/).
2. Baixe e instale a versão apropriada para o seu sistema operacional.

### 🔧 **Clang ou GCC (Linux)**
Para instalar um compilador no Linux, você pode usar os seguintes comandos no terminal:

- **Instalando o Clang**:
    ```bash
    sudo apt-get install clang
    ```

- **Instalando o GCC**:
    ```bash
    sudo apt-get install gcc
    ```

### 🟦 **MinGW (Windows)**
1. Acesse o site oficial do [MinGW](http://www.mingw.org/).
2. Baixe e instale o compilador seguindo as instruções no site.

---

## ⚙️ Configurando o Visual Studio Code para Programação em C

### 1. **Instalando a Extensão C/C++**
- Abra o **Visual Studio Code**.
- Clique no ícone de extensões (ou pressione `Ctrl+Shift+X`).
- Pesquise por **C/C++ (Microsoft)**.
- Instale a extensão.

### 2. **Configurando o Compilador**

Dependendo do compilador que você escolheu, você precisará ajustar a configuração do Visual Studio Code:

- **Clang**:
  1. Vá em `File -> Preferences -> Settings`.
  2. Pesquise por `"C_Cpp.default.compilerPath"`.
  3. Altere o valor para o caminho do Clang.

- **GCC**:
  1. Vá em `File -> Preferences -> Settings`.
  2. Pesquise por `"C_Cpp.default.compilerPath"`.
  3. Altere o valor para o caminho do GCC.

- **MinGW**:
  1. Vá em `File -> Preferences -> Settings`.
  2. Pesquise por `"C_Cpp.default.compilerPath"`.
  3. Altere o valor para o caminho do MinGW.

---

## ✅ Testando o Ambiente

Após configurar o editor e o compilador, teste se tudo está funcionando corretamente:

1. Crie um arquivo chamado **`main.c`** e insira o seguinte código:

    ```c
    #include <stdio.h>

    int main() {
        printf("Hello, World!\n");
        return 0;
    }
    ```

2. Compile e execute o arquivo:

    - **Usando Clang**:
      ```bash
      clang main.c -o main
      ./main
      ```

    - **Usando GCC**:
      ```bash
      gcc main.c -o main
      ./main
      ```

Se a mensagem **`Hello, World!`** for exibida no terminal, o ambiente está pronto! 🎉

---

## 🐳 Utilizando Docker com Devcontainer

Se preferir usar **Docker** para desenvolver no **Visual Studio Code**, você pode configurar um **Devcontainer**. Com isso, terá um ambiente isolado e pré-configurado com Clang ou GCC.

1. Configure um **container Docker** com as ferramentas necessárias.
2. Abra o Visual Studio Code, clique em **"Remote Explorer"** e escolha seu Devcontainer.
3. Desenvolva confortavelmente dentro do container!

---

**Parabéns!** Agora você está com seu ambiente configurado e pronto para começar a programar em C. 🚀

