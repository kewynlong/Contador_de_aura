# ☕ Gui.java

<p align="center">
  **Aplicação Java com interface gráfica**
  
  Desenvolvido em Java, com suporte à compilação e empacotamento em formato `.jar`.
</p>

---

## 📋 Requisitos

Antes de começar, certifique-se de ter instalado:

- ☕ **Java JDK 21**
- 🖥️ Terminal ou prompt de comando
- 📄 Arquivo `Gui.java`

> [!IMPORTANT]
> É necessário utilizar o **Java 21 (JDK 21)** para compilar o projeto conforme as instruções abaixo.

## ⚙️ Compilação

Abra o terminal na pasta onde está localizado o arquivo `Gui.java` e execute:

```bash
javac --release 21 Gui.java
```

Esse comando compila o código utilizando as regras de compatibilidade do Java 21 e gera o arquivo `Gui.class` (além de outras classes, caso existam).

## 📦 Gerando o arquivo JAR

Após compilar o projeto, execute:

```bash
jar --create --file Gui.jar --main-class Gui Gui.class
```

Esse comando cria o arquivo `Gui.jar`, definindo `Gui` como a classe principal da aplicação.

> [!NOTE]
> O comando acima pressupõe que `Gui` possui um método `public static void main(String[] args)` e que não há outras classes ou recursos necessários fora de `Gui.class`. Se houver dependências, pacotes ou arquivos adicionais, eles também precisarão ser incluídos no JAR.

## ▶️ Executando a aplicação

Para iniciar a aplicação, utilize:

```bash
java -jar Gui.jar
```

Certifique-se de que o Java 21 ou uma versão compatível esteja instalado no sistema.

## 🛠️ Comandos úteis

| Comando | Descrição |
|---|---|
| `java -version` | Verifica a versão do Java |
| `javac -version` | Verifica a versão do compilador |
| `javac --release 21 Gui.java` | Compila para Java 21 |
| `java -jar Gui.jar` | Executa o arquivo JAR |

## 📁 Estrutura do projeto

```text
.
├── Gui.java
├── Gui.class
├── Gui.jar
└── README.md
```

Os arquivos `.class` e `.jar` são gerados durante o processo de compilação e empacotamento.

---

## 📄 Licença

Defina uma licença para o projeto caso pretenda distribuí-lo publicamente.

---

<p align="center">
  Feito com ☕ Java 21
</p>
