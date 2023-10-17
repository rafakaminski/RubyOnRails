**Vagrant:**
- `vagrant`: Gerencia ambientes de desenvolvimento virtual (VM).
- `vagrant up`: Inicializa a máquina virtual.
- `vagrant suspend`: Pausa a máquina virtual.
- `vagrant halt`: Para a máquina virtual.
- `vagrant ssh`: Conecta-se à máquina virtual via SSH.

**Instalar Gem:**
- `gem install rails -v 5.2.8`: Instala a gema Ruby on Rails na versão especificada.

**RVM (Ruby Version Manager):**
- `rvm list`: Lista as versões do Ruby instaladas.
- `rvm list known`: Lista as versões do Ruby disponíveis para instalação.
- `rvm install 2.3`: Instala uma versão específica do Ruby.
- `rvm use 2.6`: Define a versão ativa do Ruby.

**Rails:**
- `rails new myapp -d postgresql`: Cria um novo aplicativo Ruby on Rails com PostgreSQL como o banco de dados padrão.
- `rails server -b 0.0.0.0 -e development`: Inicia o servidor de desenvolvimento, permitindo acesso de outras máquinas na mesma rede.

**Generators:**
- `rails generate controller <pagina_inicial>` ou `rails g controller <pagina_inicial>`: Gera um controlador.
- `rails destroy controller <pagina_inicial>` ou `rails d controller <pagina_inicial>`: Remove um controlador.
- `rails generate scaffold campo1:tipo ...`: Cria uma estrutura de CRUD para um recurso.
- `rails dbconsole`: Inicia um console de banco de dados.

**Tarefas do Banco de Dados:**
- `rails -T db`: Lista os comandos relacionados a banco de dados.
- `rails db:create`: Cria um novo banco de dados.
- `rails db:drop`: Exclui o banco de dados.
- `rails db:migrate`: Executa migrações pendentes.
- `rails db:rollback`: Reverte a migração mais recente.
- `rails db:seed`: Preenche o banco de dados com dados iniciais.
- `rails db:setup`: Cria o banco de dados, carrega o esquema e executa migrações.
