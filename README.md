# Projeto-Gerenciador-Tarefas
Projeto criado, em conjunto com o Gemini, para me ajudar no treinamento e desenvolvimento de programação.

# Direcionamentos iniciais do Gemini
##🛠️ O Projeto: Gerenciador de Tarefas (CLI)
O objetivo é criar um programa interativo rodando direto no terminal do VS Code onde você pode cadastrar, listar, filtrar, remover e salvar tarefas em um arquivo.

##📋 Requisitos e Funcionalidades
###Menu Interativo (Loop Principal):

*O programa deve exibir um menu com opções (ex: 1. Adicionar Tarefa, 2. Listar Tarefas, 3. Marcar como Concluída, 4. Remover Tarefa, 5. Sair).

*O programa só deve fechar quando o usuário escolher explicitamente a opção de sair.

###Estrutura de Dados Organizacional:

*Cada tarefa precisa conter no mínimo: ID (ou índice), Descrição, Prioridade (Alta, Média, Baixa) e Status (Pendente / Concluída).

Dica: Utilize uma lista de dicionários para representar essa estrutura em Python.

###Desafios de Lógica e Tratamento:

*Validação de Entradas: Se o sistema pedir um número do menu e o usuário digitar letras (ex: "abc"), o programa não pode quebrar! Trate o erro com try/except e peça a entrada novamente.

*Filtros de Listagem: Permita listar todas as tarefas ou filtrar apenas as pendentes ou por prioridade.

*Persistência em Arquivo (JSON): Salve os dados em um arquivo .json. Quando você fechar o terminal e abrir o programa novamente, os dados anteriores devem ser carregados automaticamente.

##🧠 Conceitos da Faculdade que Você Vai Dominar
###Este projeto cobre quase todo o núcleo de Lógica e Estrutura de Dados I:

*Variáveis e Tipos de Dados: Manipulação de strings, inteiros e booleanos.

*Estruturas de Dados: Uso prático de listas e dicionários.

*Estruturas de Repetição: Loops while (para manter o menu rodando) e for (para percorrer a lista de tarefas).

*Estruturas Condicionais: Blocos if / elif / else para responder às escolhas.

*Funções: Organização do código modularizando cada ação em funções separadas (ex: adicionar_tarefa(), salvar_dados()).

*Tratamento de Exceções: Blocos try / except para prevenir crash no código.

*Manipulação de Arquivos: Uso dos módulos de leitura e escrita (open(), json.dump(), json.load()).
