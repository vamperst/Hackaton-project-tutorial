# Exercicio Hackathon



1. Os Nomes de todos os recursos criados devem conter o workspace.
2. Crie um ambiente de Homol e um Dev
3. Cada ambiente deve ter seu próprio repósitorio de imagem
4. Ao fazer o deploy, deve ser refletida branch com o mesmo nome do workspace
5. Serão ambiente com insfraestrutura diferentes
6. Faça um zip dos arquivos desse exercicio e submeta no portal da fiap.


#### Ajuda
1. [How to create modules](https://blog.gruntwork.io/how-to-create-reusable-infrastructure-with-terraform-modules-25526d65f73d)
2. [Modules Composition](https://www.terraform.io/docs/modules/composition.html)
3. [Creating Modules](https://www.terraform.io/docs/modules/index.html)
4. [AWS datasources](https://www.terraform.io/docs/providers/aws/d/instances.html)
#### dicas:
a. Utilize o comando ${terraform.workspace} nos nomes dos recursos para executar o que é pedido.
b. Suba novos pipelines, codebuilds e ECR para o ambiente de desenvolvimento que esta montando no exercício
c. O exercício é extenso e com detalhes, tente não deixar para a ultima hora.
d. Qualquer duvida não deixe de contatar o professor pelos meios já fornecidos.
f. As credenciais que vai colocar no S3 também expira a cada 3 horas caso esteja utilizando a conta de aluno. Não se esqueça de alterar sempre que mudar as credencias do Cloud9. Se estiver em uma conta pessoal esse problema não ocorre.
