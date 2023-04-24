# BuscadorCEP

Este código se refere a um buscador de CEP (Código de Endereçamento Postal) utilizando ReactJS. O aplicativo permite que o usuário digite um CEP em um campo de entrada e, em seguida, clique em um botão para pesquisar. Em seguida, o aplicativo envia uma solicitação para a API dos Correios para recuperar informações sobre o endereço associado ao CEP inserido.

A função handleSearch() é responsável por enviar a solicitação de busca ao servidor. Antes de enviar a solicitação, ela verifica se o campo de entrada está vazio e exibe um alerta se estiver vazio. Se a solicitação for bem-sucedida, a função atualiza o estado do componente com as informações do endereço recuperado e limpa o campo de entrada.

O estado do componente é gerenciado usando o hook useState(), que é usado para armazenar o valor do campo de entrada e o objeto de endereço recuperado.

O código também usa o pacote react-icons/fi para exibir o ícone de pesquisa, bem como um arquivo de estilo CSS para estilizar o aplicativo. O arquivo index.js é responsável por renderizar o componente App em um elemento raiz do DOM.
