My composer template for a Rails app
====================================

My default setup for a rails 4 app with composer.

Create a new app from this template with:
`rails new myapp -m https://raw.github.com/DanyHunter/my_composer_template/master/template.rb`

Description
-----------

This is a pristine installation with only the user model, no views and no controllers. Installs bootstrap 3.

database.yml
---
The created database.yml file does not have the username and password fields. It also adds `host: localhost`. This is the setup that works for me to create a database.

Extra gems:
`@gems = ["high_voltage", "kaminari", "meta_request"]`

preferences:
*   **server:** thin
*   **database:** postgresql
*   **templates:** haml
*   **unit_test:** rspec
*   **integration:** rspec-capybara
*   **continuous_testing:** guard
*   **fixtures:** factory_girl
*   **frontend:** bootstrap
*   **bootstrap:** sass
*   **email:** sendgrid
*   **authentication:** devise
*   **devise_modules:** default
*   **authorization:** cancan
*   **form_builder:** simple_form
*   **starter_app:** none
*   **local_env_file:** true

Todo:
---

*   Change the application template recipe to use bootstrap 3
