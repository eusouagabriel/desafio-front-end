[![Gabriel](https://uploads-ssl.webflow.com/62c2f32bb1aa5ddb4a4f925a/638646f5906918709c3caf0e_2021-logotipo-prima%CC%81rio-horizontal-p-500.webp)](https://www.gabriel.com.br/)
## Este repositório faz parte do desafio técnico para os candidatos a vaga para pessoas desenvolvedoras de software.

##### A Gabriel é uma startup focada em proteger pessoas. Com isso, buscamos talentos capazes de construir sistemas com foco em segurança e escalabilidade. 
Para descobrir se você é o próximo talento a integrar o nosso time, queremos propor o desafio a seguir. 
Se você se sentiu desafiado faça um fork deste projeto, desenvolva o desafio e nos envie o link de seu repositório. Teremos o imenso prazer em avaliar seu esforço.

### DESAFIO

Implementar um front end usando React.js para gerenciar e visualizar as câmeras de nossos protegidos. 
Através do front end deve ser possível:

- Pesquisar, ativar e desativar um cliente
- Listar as câmeras de um cliente
- Visualizar as câmeras de um cliente a partir de um player de vídeo. 

### Observações e requisitos não funcionais.
- Fique livre para expressar sua criatividade, use cores e formas que julgar necessários para estilizar os componetes.
- Será muito bem visto um app que possa rodar nas mais diversas resoluções de tela.
- A segurança da api é muito importante para nós, por isso toda requisição aos enpoints são autenticadas. 
- Para este desafio utilize esta api que dará todo o suporte necessário, esta api pode se encontrada neste repositório aqui: 
https://github.com/eusouagabriel/desafio-frontend-api

### 1 - A tela abaixo mostra o mockup para a tela de gerenciamento dos clientes

![gerenciamento-cliente](https://user-images.githubusercontent.com/60509554/211433023-42cdce6c-f184-4081-86f7-59890fd5d72f.png)

### Para esta tela acima as seguintes funcionalidades devem ser contempladas. 
- Ao acessar está página a lista de clientes deve ser carregada com os campos nome, endereço e o campo de ativo, que nos mostrará se um cliente está ativo ou não.
- A tabela deve mostrar 10 registros por página.
- A busca poderá ser por nome ou por endereço e somente começar a filtrar os registros após digitar o terceiro caracter.
- Ativar ou desativar o cliente na coluna de Ativo.
- A coluna com o nome do cliente deverá ser um link para a página de visualização das câmeras somente quando o cliente estiver ativo.

### 2 - A tela abaixo mostra o mockup para a página de visualização das câmeras de determinado cliente.
![visualizacao-cameras](https://user-images.githubusercontent.com/60509554/211436289-74aeaca0-9a7d-409a-914b-636a03dbf0ff.png)

- Ao clicar no nome do cliente na página de gerenciamenteo de cliente, o sistema deverá redirecionar para esta tela acima, que permitirá a visualização das câmeras.
- Ao lado direito deverá ser carregado a lista de câmeras, com os seguintes campos: thumbnail, id da câmera, descrição da câmera.
- Ao clicar na câmera, o vídeo deverá ser apresentado no player ao lado esquerdo.
- Ao clicar no botão do lado direito superior  <-  , este deverá voltar para a tela de listagem dos clientes.

