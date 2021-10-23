# Dia 4

# O que vai ser feito?

* Criação de rota para obtenção dos dados
* Criar uma mensagem no banco de dados
* Módulo para separação e contagem de palavras
* Criar agendador de geração de relatórios

# Como vai ser feito?

## Vai ser usado Elixir com Phoenix

Para o Elixir:
https://elixir-lang.org/install.html

Para o Phoenix:
mix archive.install hex phx_new

Precisa instalar o PostGres:
https://www.postgresql.org/download/


## Para criar o projeto

mix phx.new heat_tags --no-html --no-assets


Para iniciar o projeto:

mix ecto.create

mix phx.create

* Estrutura de projeto Phoenix

* Criando Banco de dados
	mix ecto.gen.migration create_messages
	
mix ecto migrate

* Pattern Match

*Elixir Task

Elixir enum reduce

* Agendamento
	* Lib quantum
mix deps.get -> Baixa as dependências

# Desafios
- Ler do banco de dados todos os email unicos
- Enviar para todos os emails o report diário de palavras (Bamboo para enviar emails)
- Guardar report no banco de dados
- Pesquisar sobre fallback_controller e utilizá-lo para validação de erros



