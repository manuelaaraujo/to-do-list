# `Lista de afazeres` 

* [Introdução](#introdução)
* [Descrição](#descrição)
* [Funcionalidade](#funcionalidade)
* [Fontes-Utilizadas](#fontes-utilizadas)
* [Resultado](#resultado)



## `Introdução`
 A proposta da ativade era implementar o projeto To do List do seguinte video: [*🎥*](https://pucpredu-my.sharepoint.com/:v:/g/personal/leonardo_sidon_grupomarista_org_br/EdvhW1dXIchOgj76IU7ONr0B-Uc3xzANnbKjCdsngCOShA?e=KNchln)
e implementar o código dentro de um arquivo do github, documentando o README descrevendo o que o projeto faz, contendo obrigatóriamente os commits de cada parte realizada no projeto.

## `Descrição`
Este código HTML define a estrutura de uma página da web que parece ser uma aplicação de lista de tarefas (todo list) com funcionalidades avançadas. Vou explicar cada parte:

<!DOCTYPE html>: Declara o tipo de documento como HTML5, o que indica aos navegadores que tipo de HTML está sendo usado.

<html lang="en">: Abertura da tag HTML, indicando que o idioma padrão é inglês.

<head>: Aqui é onde são colocadas informações sobre a página, como o título, links para estilos e scripts, e metadados.

<meta charset="UTF-8">: Define o conjunto de caracteres como UTF-8, que suporta uma ampla variedade de caracteres.

<meta name="viewport" content="width=device-width, initial-scale=1.0">: Define a escala inicial e a largura da tela para dispositivos móveis.

<title>Todo Avançado</title>: Define o título da página como "Todo Avançado".

<link rel="js/scripts.js" href="css/styles.css">: Links para o arquivo CSS e JavaScript.

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="..." crossorigin="anonymous" referrerpolicy="no-referrer" />: Link para o arquivo CSS da biblioteca Font Awesome, que fornece ícones.

<script src="js/scripts.js" defer></script>: Link para o arquivo JavaScript com a opção defer, o que significa que o script será carregado após o conteúdo da página ser renderizado.

<body>: Aqui é onde está o conteúdo visível da página.

<div class="todo-container"></div>: Container onde serão exibidas as tarefas.

<header>: Cabeçalho da página.

<h1>todo Avançado</h1>: Título principal da página.
<form id="todo-form">: Formulário para adicionar novas tarefas.

<input type="text" id="todo input" placeholder="O que voce vai fazer?"/>: Campo de texto para adicionar uma nova tarefa.

<button type="submit">...</button>: Botão para enviar a nova tarefa.

<form id="edit-form">: Formulário para editar uma tarefa existente.

<input type="text" id="edit-input">: Campo de texto para editar a tarefa.

<button type="submit">...</button>: Botão para confirmar a edição da tarefa.

<button id="cancel-edit-btn">Cancelar</button>: Botão para cancelar a edição da tarefa.

<div id="toolbar">: Barra de ferramentas com opções de pesquisa e filtragem.

<div id="search">: Opção de pesquisa.

<input type="text" id="search-input" placeholder="Buscar">: Campo de texto para digitar o termo de pesquisa.

<button id="erase-button">...</button>: Botão para limpar o campo de pesquisa.

<div id="filtrer">: Opção de filtragem.

<select id="filter-select">...</select>: Menu suspenso para selecionar o filtro das tarefas.
<div id="todo-list">: Lista de tarefas.

<div class="todo">: Uma tarefa.

<h3>estou fazendo alguma coisa</h3>: Descrição da tarefa.

Botões para marcar como concluída, editar e remover a tarefa, cada um com um ícone associado da biblioteca Font Awesome.

Essencialmente, este código cria uma interface para gerenciar uma lista de tarefas com recursos de adição, edição, remoção, pesquisa e filtragem.

## `Funcionalidade`
Administrar um conjunto de atividades com capacidades de inclusão, alteração, exclusão, investigação e seleção.

## `Fontes utilizadas`
[*Vídeo do projeto*](https://pucpredu-my.sharepoint.com/:v:/g/personal/leonardo_sidon_grupomarista_org_br/EdvhW1dXIchOgj76IU7ONr0B-Uc3xzANnbKjCdsngCOShA?e=KNchln)

## `Resultado`