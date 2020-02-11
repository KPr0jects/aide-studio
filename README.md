# Compartilhe projetos e ajude outros usuários do AIDE

O AIDE Studio é um app para Android com o intuito de ajudar desenvolvedores que usam o app Android IDE (AIDE) a realizar algumas tarefas de maneira mais ágil, bem como ter alguns recursos extras que o AIDE não oferece nativamente.
Confira o [AIDE Studio na Play Store](https://play.google.com/store/apps/details?id=com.kproject.aidestudio) para mais informações.

Este pequeno guia destina-se a ensiná-lo como você pode enviar seus projetos para que eles apareçam no AIDE Studio e outros usuários possam baixá-los e conhecê-los.

No momento, a única restrição é de que sejam apenas projetos de Java-Android ou Java-Console, ou seja, projetos de aplicativos Android e projetos de Java para executar no console. É necessário que o projeto tenha sido feito ou testado no AIDE e que, obviamente, funcione.

# Como enviar meus projetos?
Para enviar seus projetos, você tem duas opções:
1. Basta que faça um pull request no [arquivo JSON principal](https://github.com/KPr0jects/AIDEStudio/blob/master/repositories.json) deste repositório, adicionando um novo JSON Object ao array de repositórios. Esse JSON Object deve ter o mesmo padrão dos anteriores e ser preenchido com os dados apresentados a seguir.
2. Enviando um email para **jsericksk@gmail.com** com os dados informados logo abaixo.

## Requisitos
**url:** URL do repositório do seu projeto no GitHub.

**project_name:** O nome do projeto. Você pode usar um título curto ou um nome simples, como preferir.

**author:** O nome do autor do projeto. Se você não for o autor mas quer compartilhar o repositório para outros usuários porque utilizou ele no AIDE com êxito, preencha esse campo com o nome de usuário do repositório.

**description:** Descrição do projeto. Descreva qual é a função dele para que os usuários possam entender facilmente para o que ele serve. Lembre-se que poderão sempre ler o README no repositório (caso exista), mas é importante preencher esse campo com uma descrição clara e objetiva para que possa aparecer no AIDE Studio.

**type:** O tipo de projeto. Os valores disponíveis são 0 e 1. 0 para projetos Java-Android e 1 para projetos Java-Console.

**Nota sobre o nome do projeto e descrição**: Só é permitida a escrita de ambos em 3 idiomas: Inglês, Português e Espanhol. Para atingir um maior número de usuários, é preferível que seja em Inglês, no entanto, você também pode usar o idioma Português ou Espanhol caso seja sua língua nativa.

## Quando meu projeto ficará disponível?
Após enviar seu projeto, ele passará por uma pequena análise e deverá ficar disponível em pelo menos 72 horas. Esse é o tempo máximo para que ele possa ser publicado. Caso exceda esse limite, por algum motivo ele não foi aprovado. Alguns dos motivos que podem fazer seu projeto não ser aprovado são:
- O projeto não é de Java-Android ou Java-Console.
- Está totalmente escrito em uma linguagem diferente de Java.
- É uma biblioteca.
- Não segue a regra dos idiomas permitidos para o nome do projeto e descrição.

**Note que a qualidade dos projetos é responsabilidade dos respectivos desenvolvedores. O AIDE Studio não se responsabiliza por eventuais erros de códigos contidos nos projetos enviados.**
