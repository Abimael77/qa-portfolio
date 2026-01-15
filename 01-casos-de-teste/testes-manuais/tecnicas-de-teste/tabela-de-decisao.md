 Tabela de Decisão

 O que é?
 
Técnica de teste utilizada para validar regras de negócio que possuem múltiplas condições e diferentes resultados possíveis.

 Quando usar?
 
Quando o comportamento do sistema depende da combinação de várias condições.

 Exemplo prático – Login de usuário

| Usuário válido | Senha válida | Resultado esperado              |
|----------------|--------------|---------------------------------|
| Sim            | Sim          | Login realizado com sucesso     |
| Sim            | Não          | Mensagem de erro                |
| Não            | Sim          | Mensagem de erro                |
| Não            | Não          | Mensagem de erro                |


