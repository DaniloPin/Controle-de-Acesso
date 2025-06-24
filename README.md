Desenvolvi um sistema de acesso a dados médicos. Informações sensíveis, como um código de prontuário, não devem ser acessadas de fora da aplicação, mas ainda podem ser lidas por classes dentro do mesmo projeto.

Criei duas classes:

- Paciente (pública), com propriedades públicas Nome e Idade.
- HistoricoMedico (com modificador internal), contendo uma propriedade CodigoProntuario e um método ExibirCodigo() que imprime o código no console.
