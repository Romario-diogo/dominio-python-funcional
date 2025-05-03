# 🧠 Roteiro de Estudos Python Avançado

Este documento organiza todos os conceitos intermediários e avançados de Python essenciais para escrever código mais limpo, funcional e profissional.

Cada item descrito aqui é uma **função embutida (builtin)**, **expressão funcional** ou **sintaxe avançada** do Python. A maioria são **funções de ordem superior**, ou seja, funções que recebem outras funções como argumento.

---

## ✅ FASE 1 – Pensamento funcional (funções e iteração expressiva)

1. **Funções anônimas (`lambda`)**  
   Tipo: Expressão funcional. Criação de funções simples e sem nome.

2. **`map()`**  
   Tipo: Função embutida. Aplica uma função a cada item de um iterável.

3. **`filter()`**  
   Tipo: Função embutida. Filtra elementos com base em uma condição booleana.

4. **`reduce()` (via `functools`)**  
   Tipo: Função de ordem superior. Reduz uma lista a um único valor.

5. **`sorted()` com `key=...`**  
   Tipo: Função embutida. Ordena uma lista com base em critério personalizado.

6. **`max()` e `min()` com `key=...`**  
   Tipo: Funções embutidas. Retornam maior ou menor item com base em critério.

7. **Funções como argumentos**  
   Tipo: Conceito de primeira classe. Usar funções como valores.

---

## ✅ FASE 2 – Iteradores e coleções eficientes

8. **`enumerate()`**  
   Tipo: Função embutida. Itera com índice e valor.

9. **`zip()`**  
   Tipo: Função embutida. Combina múltiplos iteráveis.

10. **`set()`**  
   Tipo: Tipo de dado embutido. Remove duplicatas automaticamente.

11. **`collections.Counter`**  
   Tipo: Classe da biblioteca padrão. Conta elementos.

12. **`itertools` (básico)**  
   Tipo: Módulo da biblioteca padrão. Cria iteradores poderosos e combinatórios.

---

## ✅ FASE 3 – Compreensões Pythonic

13. **List Comprehension**  
    Tipo: Expressão sintática. Criar listas a partir de lógica inline.

14. **Dict Comprehension**  
    Tipo: Expressão sintática. Criar dicionários com lógica inline.

15. **Set Comprehension**  
    Tipo: Expressão sintática. Criar conjuntos únicos com lógica.

---

## ✅ FASE 4 – Funções avançadas e escopo

16. **Funções dentro de funções**  
    Tipo: Estrutura de escopo. Define lógica isolada e local.

17. **Closures**  
    Tipo: Padrão funcional. Funções que capturam contexto externo.

18. **Decorators (básico)**  
    Tipo: Funções de ordem superior. Modificam comportamento de outras funções.

19. **`*args` e `**kwargs`**  
    Tipo: Sintaxe de função. Aceita argumentos variáveis.

20. **Desempacotamento (`*`, `**`)**  
    Tipo: Sintaxe de atribuição. Expande listas/dicionários.

---

## ✅ FASE 5 – Sintaxe expressiva e Pythonic

21. **Fatiamento (`lista[start:stop:step]`)**  
    Tipo: Operação de sequência. Trabalha com pedaços de listas/strings.

22. **Operador ternário**  
    Tipo: Expressão condicional. Substitui `if` simples.

23. **`with` (context manager)**  
    Tipo: Bloco de contexto. Gerencia recursos automaticamente.

24. **`assert`**  
    Tipo: Verificação embutida. Validação para debug e testes.

25. **Walrus operator (`:=`)**  
    Tipo: Operador de expressão. Atribuição inline.

26. **`any()` e `all()`**  
    Tipo: Funções embutidas. Testes booleanos em coleções.

27. **`reversed()`**  
    Tipo: Função embutida. Itera ao contrário.

---

## ✅ FASE 6 – Geradores e performance

28. **`yield` e funções geradoras**  
    Tipo: Estrutura de controle. Cria geradores sob demanda.

29. **Generator expressions**  
    Tipo: Expressão sintática. Forma leve de criar geradores.

30. **`next()`**  
    Tipo: Função embutida. Avança um iterador manualmente.

---

> 💡 Este roteiro é incremental e pensado para praticar com exemplos reais. Siga fase por fase, aplicando os conceitos em projetos próprios.

---

📌 Repositório mantido por **Romário** – Desenvolvedor Python focado em automação, IA e análise de dados.
