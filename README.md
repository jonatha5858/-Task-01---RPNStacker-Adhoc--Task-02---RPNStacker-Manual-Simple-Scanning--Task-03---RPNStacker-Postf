-Task-01---RPNStacker-Adhoc-
Roteiro:
- rever a Aula 07 sobre notacao posfixa [reverse polish notation]
- Implementar uma linguagem RPN stacker em Java usando uma pilha como estrutura de dados
- Programa le um arquivo com a expressao em RPN e avaliar

Exemplo de entrada:
10
10
+
Saida: 20

**Arquivo exemplo da linguagem em anexo calc1.stk




-Task-02---RPNStacker-Manual-Simple-Scanning-
Roteiro:
- rever a Aula 11 sobre introducao a analise lexica [scanning]
- evoluir o projeto da Task 01 para implementar uma feature de scanning:
   -- No geral, nosso Programa le um arquivo com a expressao em RPN e devolve a expressao avalliada
   -- a feature de scanning deve retornar uma lista de tokens
   -- a partir dessa lista de tokens que e realizada a interpretacao das expressoes com uma pilha
   -- a feature de scanning deve retornar um erro caso nao reconheca um "num" [numero] ou "op" [operator]

Exemplo de entrada [com sucesso]:
10
10
+
// a lista de tokens reconhecida [caso a imprima]
Token [type=NUM, lexeme=10]
Token [type=NUM, lexeme=10]
Token [type=PLUS, lexeme=+]

Saida: 20
