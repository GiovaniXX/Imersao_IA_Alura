Descrição do Projeto
Este projeto consiste em um assistente pessoal inteligente desenvolvido em Python, que utiliza a API do Google AI Studio para auxiliar o usuário em diversas tarefas do dia a dia. O objetivo principal é construir um agente capaz de "resolver tarefas por você" através da compreensão da linguagem natural e da geração de conteúdo inteligente.

O assistente oferece funcionalidades para gerenciamento de tarefas, geração de conteúdo criativo e prático, e organização de informações, tudo integrado em uma única ferramenta acessível via linha de comando.

Funcionalidades Principais
Gerenciamento de Tarefas Inteligente
Adiciona novas tarefas com descrição fornecida pelo usuário.

Utiliza a IA do Google AI Studio para sugerir automaticamente a categoria (pessoal, trabalho, estudo) e o nível de prioridade (alta, média, baixa) da tarefa com base em sua descrição.

Permite listar todas as tarefas cadastradas, exibindo seu status (concluída ou não), categoria e prioridade.

Possibilita marcar tarefas como concluídas através do seu ID.

As tarefas são persistidas localmente em um arquivo tarefas.json..

Geração de Conteúdo Criativo e Prático
Geração de E-mails
O usuário pode fornecer o assunto, destinatário e pontos principais, e a IA gera um rascunho de e-mail profissional.

Geração de Ideias para Blog
Dado um tema, a IA sugere ideias criativas e relevantes com títulos concisos para posts de blog.

Organização de Informações
Resumo de Textos
Fornecendo um texto, a IA extrai e apresenta os pontos principais de forma concisa e objetiva.

Organização de Notas
Ao inserir um conjunto de notas, a IA tenta organizá-las em tópicos principais e subtópicos, buscando uma estrutura lógica.

Como Utilizar
Pré-requisitos
Python 3.x instalado no seu sistema.

Uma conta no Google AI Studio e uma API Key válida.

A biblioteca google-generativeai instalada (você pode instalá-la com pip install google-generativeai).

Configuração
Clone este repositório para o seu ambiente local.

Abra o arquivo assistente_ia.py e substitua a placeholder "SUA_API_KEY" pela sua chave de API real do Google AI Studio.

Execução
Abra o terminal ou prompt de comando, navegue até o diretório do projeto e execute o script com o comando:

sh
python assistente_ia.py
Interação
O script apresentará um menu com as opções de funcionalidades. Digite o número da opção desejada e siga as instruções na tela.

Estrutura de Arquivos
