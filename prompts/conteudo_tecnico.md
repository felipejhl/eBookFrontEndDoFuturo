# Geração de Conteúdo Técnico e Exemplos de Código

## Contexto do E-book
Esta seção foca em provar a automação da IA na refatoração de código legado (Capítulo 1.2).

## Requisitos do Output
1.  **Código Legado (Input):** Uma função JavaScript que simule uma chamada assíncrona usando o padrão `callback` aninhado.
2.  **Código Moderno (Output):** A refatoração dessa mesma função para o padrão `async/await` com bloco `try/catch`.
3.  **Instrução de Conteúdo:** Crie um parágrafo que compare a legibilidade e a manutenção dos dois padrões.

## 💡 Prompt

"Gere dois snippets de código JavaScript (máximo 10 linhas por snippet). O primeiro deve ser uma função chamada 'fetchUserData' que usa callbacks aninhados para simular um erro e um sucesso. O segundo snippet deve ser a refatoração exata dessa função usando a sintaxe async/await, incluindo o tratamento de erro com try/catch. Inclua um parágrafo de 5 linhas explicando por que a versão async/await é superior para legibilidade."

---
*Dica: Após este ponto de partida, use prompts de refino para auditar o código gerado (ex: 'Confirme se o tratamento de erro está no catch e não no callback') e refinar a análise técnica do parágrafo explicativo.*
