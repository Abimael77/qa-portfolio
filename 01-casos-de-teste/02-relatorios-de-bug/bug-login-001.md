ID: BUG-001
Título: Sistema permite login sem informar senha
Severidade: Alta
Prioridade: Alta
Ambiente: Homologação
Status: Aberto

Passos para reproduzir:
1. Acessar a tela de login
2. Informar um usuário válido
3. Deixar o campo senha em branco
4. Clicar no botão "Entrar"

Resultado esperado:
O sistema deve impedir o login e exibir mensagem de erro

Resultado obtido:
O sistema realiza o login sem validação da senha
