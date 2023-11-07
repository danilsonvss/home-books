# Home Books
O desafio consiste em criar um aplicativo responsivo para gestão de livros digitais.

O prazo para finalização do projeto é de 5 dias.

## Stack recomendada
1. NodeJs (Express, Nest etc.)
2. PHP (Laravel, Zend etc.)
3. ReactJs(NextJs,Remix, Expo etc.)
4. Tailwindcss
5. Material Symbols

## Layout no figma
[Clique aqui](https://www.figma.com/file/lPZVwxoBB94OQ5rbZKsaq2/Home-Books?type=design&mode=design&t=654oCV8wlV0363Sm-1) para acessar o layout.

## Login

Integrar o login utilizando a API do github.
**Critérios de aceitação**: 
1. Validar se o usuário está logado
2. Validar se o aplicativo foi autorizado pelo github
3. Redirecionar o usuário para o dashboard após o login

## Área logada
Esta área é composta por Categorias, Autores e Livros

**Critérios de aceitação para Categorias, Autores e Livros**: 
1. Botão para cadastro
2. Formulário de cadastro e edição
3. Listar os itens existentes
4. Paginação de 10 itens
5. Filtros/Busca

### Sidebar

1. O menu ativo por padrão deve ser **Dashboard**
2. Ao tirar o mouse de cima, deve recolher a **Sidebar**
3. Quando recolhida, mostrar apenas os icones

### Categorias
Deve conter filtro nos campos: Id, Nome, Descrição, Ativo

1. Id (Auto)
2. UUID (Auto)
3. Nome (Obrigatório)
4. Descrição (Opcional)
5. Ativo (Default: true)

### Autores
Deve conter filtro nos campos: Id, Nome, Biografia, Ativo

1. Id (Auto)
2. UUID (Auto)
3. Nome (Obrigatório)
4. Biografia (Obrigatório)
5. Ativo (Default: true)

### Livros
Deve conter filtro nos campos: Id, Titulo, Categoria, Autor, Ativo

1. Id (Auto)
2. UUID (Auto)
3. Titulo (Obrigatório)
4. Categoria (Obrigatório)
5. Descrição (Obrigatório)
6. Autor (Obrigatório)
7. Ativo (Default: true)

### Dashboard
A criação dessa página é de responsabilidade do desenvolvedor.

Coloque sua criatividade em prática. Tenha em mente o prazo.
