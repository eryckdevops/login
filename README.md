# PHP Login-Cadastro

> Site simples que possui, área de Login, Cadastro, Listagem de usuários e clientes com paginação e redefinição de senha.

## Autenticação e Autorização com PHP e JavaScript

> No subsistema de autenticação, a validação de credenciais ocorre no backend utilizando PHP. As requisições assíncronas e a manipulação dinâmica do DOM são orquestradas por scripts JavaScript, facilitando a interação do usuário. Em situações de recuperação de senha, a lógica é implementada em PHP, com operações assíncronas controladas por JavaScript para uma experiência mais fluida.

## Recuperação de Credenciais com PHP
> O processo de recuperação de credenciais é gerenciado pelo backend PHP, onde a validação e o processamento da solicitação ocorrem. A geração e envio automático de uma nova senha por e-mail são operacionalizados com PHP, enquanto o feedback e as atualizações de interface são intermediados por JavaScript.

## Registro e Gestão de Usuários com PHP e JavaScript
> O registro de usuários envolve operações complexas no backend com validação de dados utilizando PHP. O carregamento dinâmico de cidades, dependente do Estado selecionado, é implementado por meio de scripts JavaScript. A transição para a tela de login para usuários já registrados é controlada por scripts JavaScript.

## Página Inicial - Listagem e Navegação de Entidades com PHP e JavaScript
> Após autenticação, a página inicial é alimentada por consultas PHP ao banco de dados, fornecendo dados para a tabela exibida. A manipulação dinâmica entre tabelas de usuários e clientes é gerenciada por scripts JavaScript. A pesquisa interativa e o filtro de dados, bem como as operações de edição e exclusão, são executadas de forma assíncrona, com JavaScript interagindo diretamente com o backend PHP.

## Cadastro e Gestão de Clientes com PHP e JavaScript
>O formulário de cadastro de clientes é conduzido por scripts PHP, que realizam validação e processamento dos dados. A dinâmica de seleção de cidades, dependente do Estado, é gerida por scripts JavaScript. A submissão do formulário, a navegação entre páginas e a decisão de retornar à página inicial ou iniciar um novo cadastro são tratadas assincronamente, com interações entre PHP e JavaScript.

>
* Estado
* Cidade
* Nome
* Situação
* Origem
>


## Cadastro de Cliente

> Atráves do formulário contido nessa página, o usuário já autenticado, será possível adicionar dados de novos clientes ao banco de dados. Todos os campos deverão ser preenchidos de maneira correta:

>
* Nome Completo
* Endereço de E-mail
* Documento (CNPJ)
* Telefone
* Origem (Poderá ser mais de uma)
* Estado
* Cidade
* Observação (Não é obrigatório)
>

> Ao selecionar o Estado, serão carregadas todas as cidades do Estado selecionado.

>No fim do formulário o usuário poderá retornar a página inicial "Clique aqui" ou, cadastrar um novo cliente, preenchendo novamente os campos.

## Editar Cliente

>Nesta página, o usuário poderá alterar os dados cadastrados dos clientes. Campos semelhantes ao do cadastro, com exceção ao campo "Situação", onde será possível ativar ou inativar um cliente.

## Lista de Usuários

>Possui as mesmas propriedades da "Lista de Clientes", nessa página, o usuário autenticado poderá acessar os dados de todos os usuários cadastrados no sistema.

> O icone "Vermelho", para deletar o usuário, o icone "Azul", para editar o usuário, e o icone "Verde", para cadastrar um novo usuário, também são encontrados em seus respectivos locais.

> Poderá alternar entre a listagem de clientes e usuários, e fazer pesquisas para aplicar filtros nos dados com os termos:

>
* Estado
* Cidade
* Nome
* Situação
>

## Editar Usuário

> O usuário autenticado poderá alterar os dados cadastrados dos usuários.

## Considerações finais

> Apenas para praticar php




## 🤝 Desenvolvedor

> Software Engineer

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/109317442?v=4" width="160px;" alt="Erick Rodrigues"/><br>
        <sub>
          <b>Erick Rodrigues</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 Licença

Este projeto está sob licença. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

&#xa0;



<a href="#top">Volte para o topo</a>
