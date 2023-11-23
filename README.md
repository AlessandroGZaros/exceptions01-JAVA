# exceptions01-JAVA
Versões de uma aplicativo de reservas, sendo aprimorado com o tratamento de exceções.


• Solução 1 (muito ruim): lógica de validação no programa principal
• Lógica de validação não delegada à reserva

• Solução 2 (ruim): método retornando string • A semântica da operação é prejudicada
• Retornar string não tem nada a ver com atualização de reserva
• E se a operação tivesse que retornar um string?
• Ainda não é possível tratar exceções em construtores
• Ainda não há auxílio do compilador: o programador deve "lembrar" de verificar se houve
erro
• A lógica fica estruturada em condicionais aninhadas

• Solução 3 (boa): tratamento de exceções
