# SBA Snippets

rails new sba_snippets -d mysql

*init*

rake db:create

*mysql*

- rails g devise:install
- rails g devise User
- rails g devise:views
- rake db:migrate
-rake db:seed

*devise User*

- rails g scaffold Snippet title code:text user:references
- rake db:migrate

*scaffolded Snippet*
