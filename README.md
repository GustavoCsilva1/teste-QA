# teste-QA // Contele Rastreador

## Erros e Bugs:

* Na opção "Buscar pelos itens listados" na aba motoristas, mesmo digitando informações como nome completo, apelido, dentre outras informações... a busca não filtra informação alguma.
* Na parte status do motorista existem diversos erros de visualização para o usuário. Não é mostrado o vencimento da CNH (com erro de digitação) e mesmo colocando um código de identificação, isso não é mostrado para o usuário no status.
* Ao clicar em "novidades do sistema" localizado no cabeçalho onde ficam os links, sou redirecionado para mesma página dos motoristas.
* Quando tento registrar um novo motorista inserindo todos os dados corretamente, ocorre um erro "erro ao registrar motorista".
* Quando clico em um funcionario abre uma página de erro "RangeError: Invalid time value". Esse erro se tornou comum conforme navegava pela página, ocorrendo diversas vezes. Evidencia logo abaixo:
 ![erro_selecione](https://user-images.githubusercontent.com/80724237/133548128-cd49c86e-6498-4764-801a-e9ea1e617d63.png)

* Quando clico em deletar qualquer um dos motoristas ocorre um erro e o procedimento não é realizado. Evidencia logo abaixo:
 ![erro_deletando_motorista](https://user-images.githubusercontent.com/80724237/133548042-423c0ae5-68ed-4cde-8c92-6255fd3b347a.png)



* Ao realizar o teste pelo "Netwok" da página em inspecionar elemento, foi encontrado um erro de requisição e utilizando o "Response" pude localizar onde estava o erro, como mostra o vídeo ao lado onde mostro todo o procedimento feito:
https://www.youtube.com/embed/ltj7r5Z3jso
* É possível evidenciar os erros listados acima indo em inspecionar elementos e source. Onde me mostra os erros e as linhas de código no qual estes erros estão... ao clicar no link que aparece o erro, também sou levado até a linha de erro do código, como mostra na imagem logo abaixo:
 ![evidencia](https://user-images.githubusercontent.com/80724237/133550743-2fcd9f6b-107a-4ad4-b71e-954c16b7540c.png)
 <br />
 <br />
 
 ## Pontos de melhoria//atenção:
 * Ao navegar pelas páginas senti muita lentidao para o carregamento, mesmo minha rede internet ultrapassando os 100 megas de down e up. Se colocando no lugar do usuário comum que vai utilizar essa interface diariamente, este ponto pode se tornar um incomodo e a página pode não trabalhar como deveria no dia a dia dependendo da internet do usuário.

 * No cabeçalho é possível ver os links e ícones duplicados, não acredito ter sido proposital pois não há necessidade de duplicar. Isto acaba deixando a página mais poluída e mais pesada, o que dificultaria ainda mais a navegação do usuário.

 * Como mostrado no print logo abaixo, o link em "motoristas" que deveria me encaminhar de volta para a página anterior não funciona. Se colocando no lugar do usuário comum, é  uma ferramenta que o usuário pode sentir falta.
 ![erro_link](https://user-images.githubusercontent.com/80724237/133551848-ae4ffb70-76dc-4a59-b6ba-f084026de66c.png)
 
 ## Considerações:
 * No geral, foram realizados diversos testes na parte de registro simulando o acesso de um usuário comum, nesta parte deixei de preencher propositalmente informações obrigatorias como apelido, numero da CNH... e ao clicar em registrar o script funcionou corretamente, me informando as lacunas que deixaram de ser preenchidas e não finalizando o registro.







