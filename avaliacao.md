# Projeto 2 - Gerenciamento de Membros e Pagamentos

## Avaliação

### Nota
8,5

### Comentários

#### Sobre a página web

1. Membros da instituição

* (a) Cadastrar membros: O usuário deve poder cadastrar membros da instituição, fornecendo nome e outras informações relevantes para a instituição. No mínimo três campos de informação devem ser informados pelo usuário no cadastro.
  + **Comentário**: Atendido.

* (b) Gerar identificação única: Além dos campos informados pelo usuários, o sistema deve gerar automaticamente um ID único para cada membro cadastrado. Esses IDs devem ter o mesmo prefixo, indicando que são membros da instituição.
  + **Comentário**: Atendido.

* (c) Excluir membros: O usuário deve poder excluir membros da instituição selecionando o membro a ser excluído a partir de uma lista de membros cadastrados. Membros excluídos devem deixar de ser exibidos em tela, mas não podem ser removidos do sistema.
  + **Comentário**: Atendido.

* (d) Editar membros: O usuário deve poder editar as informações de um membro da instituição selecionando o membro a ser editado a partir de uma lista de membros cadastrados. O único campo que não pode ser editado é o ID do membro.
  + **Comentário**: Atendido.

* (e) Buscar membros: O usuário deve poder buscar por membros a partir de seu nome (completo ou parcial), ID ou qualquer das outras informações cadastradas. Todas as correspondências encontradas devem ser exibidas na tela.
  + **Comentário**: Atendido.

2. Pagamentos

* (a) Registrar pagamentos: O usuário deve poder registrar os pagamentos realizados pelos membros da instituição. Deve ser registrado o valor pago, a data do pagamento e do que se trata o pagamento. Todos os pagamentos devem estar associados a um membro da instituição.
  + **Comentário**: Atendido.

* (b) Gerar identificação única: Além dos campos informados pelo usuário, o sistema deve gerar automaticamente um ID único para cada pagamento registrado. Esses IDs devem ter o mesmo prefixo, indicando que são pagamentos realizados por membros da instituição.
  + **Comentário**: Atendido.

* (c) Excluir pagamentos: O usuário deve poder excluir pagamentos registrados selecionando o pagamento a ser excluído a partir de uma lista de pagamentos registrados. Pagamentos excluídos devem deixar de ser exibidos em tela, mas não podem ser removidos do sistema.
  + **Comentário**: Atendido.

* (d) Buscar pagamentos: O usuário deve poder buscar por pagamentos a partir de seu ID, valor, data, descrição ou membro associado. Todas as correspondências encontradas devem ser exibidas na tela.
  + **Comentário**: Não atendido.

3. Relatórios

* (a) Relatório de membros: O usuário deve poder emitir um relatório com a lista de membros cadastrados na instituição, contendo as informações de cada membro.
  + **Comentário**: Atendido.

* (b) Relatório de pagamentos: O usuário deve poder emitir um relatório com a lista de pagamentos registrados na instituição, contendo as informações de cada pagamento.
  + **Comentário**: Atendido.

* (c) Apresentação do relatório: Os relatórios devem ser apresentados em uma nova página, com um cabeçalho e rodapé personalizados. Os relatórios devem ser formatados para boa visualização, tanto em formato digital (tela) quanto impresso. No formato digital deve ser incluído um botão para impressão do relatório. No formato impresso, elementos desnecessários para a impressão devem ser ocultos, como o menu de navegação e o rodapé da página.
  + **Comentário**: Atendido.

4. Atividades da instituição

* (a) Galeria de imagens: A aplicação deve conter uma galeria de imagens com fotos das atividades realizadas pela instituição. No mínimo dez fotos devem ser exibidas, sendo que não pode haver repetição de fotos. Cada foto deve conter uma legenda.
  + **Comentário**: Atendido.

* (b) Descrição das atividades: A aplicação apresentar uma descrição das atividades realizadas pela instituição, ilustrando com pelo menos duas imagens que não estejam na galeria.
  + **Comentário**: Atendido.

* (c) Contato: A aplicação deve conter informações de contato da instituição, como endereço, telefone e e-mail. Além disso, deve conter um formulário para facilitar o contato dos interessados.
  + **Comentário**: Atendido.

5. Interface

* (a) Menu de navegação: A aplicação deve conter um menu de navegação que permita ao usuário acessar as funcionalidades da aplicação e as informações da instituição.
  + **Comentário**: Atendido.

* (b) Rodapé: A aplicação deve conter um rodapé com informações sobre a instituição e os desenvolvedores da aplicação.
  + **Comentário**: Atendido.

* (c) Responsividade: A aplicação deve ser responsiva e se adaptar a pelo menos três tamanhos de tela: > 1024px (desktop), ≤ 1024px e > 320px (tablet) e ≤ 320px (smartphone).
  - i. Elementos HTML não podem ter seu conteúdo cortado, sobreposto ou tocando o limite da tela ou o conteúdo de outro elemento.
  - ii. Rolagem horizontal não deve ser usada.
  - iii. O menu de navegação deve ser substituído por um botão de menu (hamburguer) quando a interface for exibida em smartphones
  + **Comentário**: Parcialmente atendido. elementos tocando o limite da tela em telas médias (tablets) e pequenas (smartphones).

* (d) Idioma: A aplicação deve ser apresentada em português.
  + **Comentário**: Atendido.

#### Sobre o sistema

1. O sistema deve ser desenvolvido utilizando HTML, CSS e JavaScript. Nenhuma biblioteca ou framework externo deve ser utilizado. Recursos externos, como fontes e imagens, podem ser utilizados.
  + **Comentário**: Atendido.

2. O sistema deve conter pelo menos três páginas (documentos HTML separados). 
  + **Comentário**: Atendido.

3. Todos os elementos HTML devem possuir semântica adequada. Caso precise utilizar elementos genéricos, a semântica deve ser atribuída por meio dos atributos `id` e `class`.
  + **Comentário**: Atendido.

4. Os dados dos membros, pagamentos e dos contatos devem ser armazenados localmente, em um arquivo `JSON` e/ou `localStorage`.
  + **Comentário**: Atendido.

5. O código deve estar bem organizado e separado em arquivos diferentes (HTML, CSS e JS), de acordo com a responsabilidade de cada um.
  + **Comentário**: Parcialmente atendido. Utilização de funções JS nos arquivos HTML.

6. O código deve estar validado de acordo com os padrões W3C para HTML e CSS.
  + **Comentário**: Não atendido. Muitos erros de validação.