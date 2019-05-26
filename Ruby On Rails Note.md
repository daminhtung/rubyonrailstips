# Migrate
> rails generate migration table_name
> rake db:migrate

---------------------------------------------------------

Run migration for product, test & development database:

library> export RAILS_ENV = production

library> rake db:migrate

library> export RAILS_ENV = test

library> rake db:migrate

library> export RAILS_ENV = development

library> rake db:migrate

---------------------------------------------------------

rake db:rollback STEP=5   //rollback 5 step of migrate
