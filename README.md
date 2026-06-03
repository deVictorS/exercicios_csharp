# Exercícios C# 📚

Uma coleção organizada de exercícios práticos de sintaxe e conceitos fundamentais de C#, cobrindo estruturas de dados, orientação a objetos e manipulação de dados.

## 📋 Descrição

Este repositório contém uma série de exercícios educacionais em C# organizados por tema, desde estruturas homogêneas (arrays) até construtores e modificadores de visibilidade. Cada exercício demonstra conceitos importantes da linguagem através de programas práticos e interativos.

## 🎯 Objetivos

- ✅ Aprender conceitos fundamentais de C#
- ✅ Praticar programação orientada a objetos
- ✅ Entender estruturas de dados
- ✅ Desenvolver habilidades de lógica de programação
- ✅ Implementar menus interativos e fluxos de usuário

## 📂 Estrutura do Repositório

```
exercicios_csharp/
├── estruturasHomogeneas/          # Arrays e vetores
│   ├── exercicio1.cs              # Análise de vetor (maior, menor, pares/ímpares)
│   ├── exercicio2.cs              # Operações com vetores
│   ├── exercicio3.cs              # Manipulação avançada
│   └── Program.cs
├── estruturasHeterogeneas/        # Structs e tipos compostos
│   └── exercicio4.cs              # Cadastro de produtos com data de validade
├── classes/                       # Orientação a objetos
│   └── exercicio5.cs              # Agenda de clínica (classes aninhadas)
├── atributosPropriedadesMetodos/  # Membros de classe
│   └── exercicio6.cs              # Sistema de cadastro de veículos
├── visibilidadeAcessibilidade/    # Modificadores de acesso
│   └── exercicio7.cs              # Cadastro de funcionários
├── construtores/                  # Construtores e inicialização
│   └── exercicio8.cs              # Gerenciamento de vetores com construtores
└── README.md
```

## 🔍 Tópicos Cobertos

### 1️⃣ Estruturas Homogêneas (`estruturasHomogeneas/`)

**Exercício 1 - Análise de Vetor**
- Leitura de 10 valores inteiros
- Encontrar maior e menor valor
- Contar números pares e ímpares
- Calcular média aritmética
- Uso de `LINQ` (`.Max()`, `.Min()`)

**Exercício 2** - Operações com vetores

**Exercício 3** - Manipulação avançada

### 2️⃣ Estruturas Heterogêneas (`estruturasHeterogeneas/`)

**Exercício 4 - Cadastro de Produtos**
- Definição de structs
- Structs aninhadas (Produtos + Validade)
- Cadastro de até 30 produtos
- Busca por valor
- Dados: nome, preço, quantidade, data de validade

### 3️⃣ Classes (`classes/`)

**Exercício 5 - Agenda de Clínica**
- Classes aninhadas (Paciente, Data)
- Estruturas heterogêneas
- Menu de opções
- Marcar consultas
- Buscar por médico
- Dados: médico, paciente, hora, data (dia/mês/ano)

### 4️⃣ Atributos, Propriedades e Métodos (`atributosPropriedadesMetodos/`)

**Exercício 6 - Sistema de Cadastro de Veículos**
- Definição completa de classe
- Atributos: nome, marca, ano, placa
- Métodos: `Cadastro()`, `Listar()`
- Array de objetos (vetor de 30 veículos)
- Menu com opções de cadastro e listagem

### 5️⃣ Visibilidade e Acessibilidade (`visibilidadeAcessibilidade/`)

**Exercício 7 - Cadastro de Funcionários**
- Modificadores de acesso
- Busca sequencial
- Menu de opções
- Dados: nome, telefone

### 6️⃣ Construtores (`construtores/`)

**Exercício 8 - Gerenciamento de Vetores**
- Classe `Gerenciar` com múltiplos métodos
- Construtores com parâmetros
- Criação dinâmica de vetores
- Preenchimento automático com valores aleatórios
- Operações:
  - Definir tamanho (padrão: 10)
  - Preencher com valores aleatórios
  - Inserir elemento em posição
  - Pesquisar elemento
  - Listar todos
  - Encontrar maior e menor

## 💻 Como Usar

### Requisitos
- **Visual Studio 2019+** ou **Visual Studio Code**
- **.NET SDK 5.0+**
- **C# 9.0+**

### Compilar e Executar

```bash
# Entrar no diretório do exercício
cd exercicios_csharp/estruturasHomogeneas

# Compilar (usando .NET CLI)
dotnet build

# Executar
dotnet run

# Ou compilar e executar manualmente
csc exercicio1.cs
dotnet exercicio1.dll
```

### Compilação via Visual Studio

1. Abrir a solução no Visual Studio
2. Selecionar o projeto desejado
3. Pressionar `F5` para executar
4. Ou `Ctrl+Shift+B` para compilar

## 📝 Exemplos de Uso

### Exercício 1 - Análise de Vetor

```
---INSERÇÃO DE NÚMEROS---

Digite o elemento 1 do vetor: 
5
Digite o elemento 2 do vetor: 
10
...

O maior número é 25 e o menor 2
O vetor possui 5 elementos pares e 5 elementos ímpares
A média aritmética dos valores é: 12.5
```

### Exercício 5 - Agenda de Clínica

```
---AGENDA---
1 - MARCAR CONSULTA
2 - PROCURAR CONSULTA
0 - SAIR

Selecione: 1

Médico: Dr. Silva
Paciente: João
Horário: 14:30
Dia: 15
Mês: 06
Ano: 2026

[Selecione: 2]
Digite o nome do médico: Dr. Silva

Consultas agendadas-> Paciente João - Horário: 14:30 - Data: 15/06/2026
```

### Exercício 8 - Gerenciamento de Vetores

```
---VETORES---
1 - DEFINIR TAMANHO
2 - PREENCHER VETOR
3 - INSERIR UM ELEMENTO
4 - PROCURAR UM ELEMENTO
5 - LISTAR VETOR
6 - MOSTRAR OS PICOS
0 - SAIR

Selecione: 1
Defina o tamanho do vetor: 5

[Selecione: 2]
Digite o elemento mínimo do vetor: 1
Digite o elemento máximo do vetor: 100

[Selecione: 6]
Maior elemento do vetor: 95
Menor elemento do vetor: 12
```

## 🔑 Conceitos-Chave Cobertos

### Tipos de Dados
- `int`, `string`, `double`
- Arrays e vetores

### Estruturas
- **Structs** - Tipos por valor
- **Classes** - Tipos por referência
- **Classes Aninhadas** - Composição

### Orientação a Objetos
- **Atributos/Campos** - Dados da classe
- **Métodos** - Comportamento
- **Construtores** - Inicialização
- **Encapsulamento** - Modificadores de acesso

### Modificadores de Acesso
- `public` - Acessível de qualquer lugar
- `private` - Acessível apenas dentro da classe

### Funcionalidades C#
- **LINQ** - `.Max()`, `.Min()`, `.Sum()`
- **Console I/O** - Entrada e saída
- **Loops** - `for`, `do-while`, `while`
- **Condicionais** - `if`, `switch`
- **Random** - Geração de números aleatórios

## 📊 Organização por Nível

### Iniciante
- ✅ Exercício 1 - Análise de Vetor
- ✅ Exercício 2 - Operações com Vetores
- ✅ Exercício 3 - Manipulação Avançada

### Intermediário
- ✅ Exercício 4 - Structs e Estruturas Heterogêneas
- ✅ Exercício 5 - Classes Aninhadas
- ✅ Exercício 6 - Sistema de Cadastro

### Avançado
- ✅ Exercício 7 - Modificadores de Acesso
- ✅ Exercício 8 - Construtores e Gerenciamento

## 🎓 Dicas de Aprendizado

1. **Comece pelo Exercício 1** - Entenda arrays e vetores
2. **Progresso Gradual** - Avance de forma sequencial
3. **Modifique o Código** - Experimente mudanças
4. **Adicione Novas Features** - Estenda os exercícios
5. **Pratique Regularmente** - Consistência é fundamental

## 🚀 Próximos Passos

Depois de completar estes exercícios, explore:
- Herança e Polimorfismo
- Interfaces e Abstract Classes
- Tratamento de Exceções (try-catch)
- Arquivo I/O (leitura/escrita)
- Bancos de Dados (SQL)
- Async/Await

## 📚 Recursos Adicionais

- [Microsoft Docs - C#](https://docs.microsoft.com/en-us/dotnet/csharp/)
- [C# Programming Guide](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/)
- [LINQ Documentation](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/)
- [.NET Tutorial](https://dotnet.microsoft.com/learn)

## 📄 Licença

Este projeto não possui licença especificada.

## 👨‍💻 Autor

[deVictorS](https://github.com/deVictorS)

---

**Nota:** Estes exercícios foram desenvolvidos para fins educacionais, com o objetivo de consolidar conhecimentos sobre sintaxe e conceitos fundamentais de C#. Use como base para sua aprendizagem e adaptação.
