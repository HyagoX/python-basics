# Fundamentos de Python - Aula Prática

Este repositório contém os códigos desenvolvidos durante a aula de fundamentos de Python, abordando conceitos essenciais para iniciantes na linguagem.

## 📚 Conteúdo da Aula

### 1. Variáveis e Constantes (`variaveis_constantes.py`)

**Conceitos abordados:**
- Declaração de variáveis
- Atribuição múltipla de variáveis
- Convenções para constantes em Python
- Uso de f-strings para formatação de texto

**Pontos importantes:**
- Em Python, não existe diferenciação técnica entre variáveis e constantes
- Por convenção, constantes são escritas em MAIÚSCULO
- É possível atribuir valores a múltiplas variáveis em uma única linha
- F-strings (`f"texto {variavel}"`) facilitam a interpolação de variáveis em strings

**Exemplo prático:**
```python
nome, idade = 'Hyago', 17
LIMITE_SAQUE_DIARIO = 1000  # Constante por convenção
print(f"Meu nome é {nome} e tenho {idade} anos")
```

### 2. Conversão de Tipos (`convertendo_tipos.py`)

**Conceitos abordados:**
- Verificação de tipos com `type()`
- Diferença entre divisão inteira (`//`) e divisão real (`/`)
- Conversão explícita de tipos (`int()`, `float()`)

**Pontos importantes:**
- A divisão com `/` sempre retorna um float
- A divisão com `//` retorna um int (divisão inteira)
- Python permite conversão entre tipos numéricos quando compatível
- A função `type()` é útil para verificar o tipo de uma variável

**Exemplo prático:**
```python
preco = 10
divisao_real = preco / 2    # Resultado: 5.0 (float)
divisao_inteira = preco // 3  # Resultado: 3 (int)
```

### 3. Entrada e Saída de Dados (`print_input.py`)

**Conceitos abordados:**
- Captura de entrada do usuário com `input()`
- Formatação de saída com `print()`
- Parâmetros `sep` e `end` da função `print()`

**Pontos importantes:**
- `input()` sempre retorna uma string
- O parâmetro `sep` define o separador entre valores no print
- O parâmetro `end` define o que será impresso ao final (padrão é `\n`)
- Duas formas principais de formatação: f-strings e parâmetros do print

**Exemplo prático:**
```python
nome = input('Informe seu nome: ')
idade = input('Informe sua idade: ')
print(nome, idade, sep=' - ', end='!\n')
```

## 🎯 Objetivos de Aprendizado

Após estudar estes códigos, você deve ser capaz de:

1. **Trabalhar com variáveis**: Criar, modificar e usar variáveis em Python
2. **Entender tipos de dados**: Reconhecer diferentes tipos e fazer conversões
3. **Interagir com o usuário**: Capturar entrada e exibir saída formatada
4. **Aplicar boas práticas**: Usar convenções adequadas para nomes e constantes

## 📝 Exercícios para Prática

1. Um programa que pede nome, idade e cidade, e exiba uma mensagem personalizada
2. Uma calculadora simples que aceite dois números e mostre diferentes tipos de divisão
3. Diferentes formatações usando os parâmetros do `print()`

## 💡 Dicas de Estudo

- Practice os exemplos modificando os valores
- Teste diferentes tipos de entrada nos programas
- Observe como Python lida automaticamente com tipos
- Use `type()` para explorar diferentes variáveis

---

*Desenvolvido durante aula de Python - Fundamentos da Linguagem*