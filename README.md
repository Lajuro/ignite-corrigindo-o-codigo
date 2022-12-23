# **Desafio 03 - Corrigindo o código**

Nesse desafio foi passado um código com alguns erros e o desafio era corrigir esses erros fazendo com que passasse nos testes.

Cada uma das rotas possuia algum tipo de "pegadinha", alguns exemplos:

- A rota de criar repositórios não estava adicionando os repositórios no array de repositórios.
- A rota de deletar repositórios estava fazendo a verificação inversa no retorno do método `findIndex`, ao invés de verificar com `menor que zero` estava verificando com `maior que zero`.
- A rota de atualizar repositórios estava aceitando qualquer tipo de informação no corpo da requisição, o que faria adicionar qualquer informação.
- A rota de dar like em um repositório estava retornando uma string `likes` ao invés de retornar o número de likes.

Porém, além desses exemplos, haviam diversos outros erros que foram identificados e corrigidos, que podem ser verificados no commit `fix(challenge/README.md): foi feito a correção dos erros nas rotas e documentado no README.md` do repositório do desafio.
