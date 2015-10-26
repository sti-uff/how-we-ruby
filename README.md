# how-we-ruby
Quick-referencing guidelines for working with ruby on rails

## What is this repository for?

Quick-referencing our current rails stack on
Superintendência de Tecnologia da Informação - Universidade Federal Fluminense (STI-UFF, for short)

## Ruby
* ruby 2.1.5 or higher
* [rvm](https://rvm.io/) with .ruby-version and .ruby-gemset instead of .rvmrc

## Code quality checks
""All code in any code-base should look like a single person typed it, no matter how many people contributed."

* Style Guide: [Code style guides](https://github.com/bbatsov/ruby-style-guide/)
* Linting: [Rubocop](https://github.com/bbatsov/rubocop)
* Query analysis: [Bullet](https://github.com/flyerhzm/bullet)
* Code quality: [Rubycritic](https://github.com/whitesmith/rubycritic)
* Security Checks: [Brakeman](https://github.com/presidentbeef/brakeman) 

## Gems:
* Framework: Ruby on Rails (>= 4.2)
* Database: Mysql ([mysql2](https://github.com/brianmario/mysql2)) (Change this to what suits your case better)
* Internal authentication: portal-sso (Internal solution)
* Non-university authentication: [Devise](https://github.com/plataformatec/devise)
* Authorization: [CanCanCan](https://github.com/CanCanCommunity/cancancan)
* Pagination: [Kaminari](https://github.com/amatsuda/kaminari) or [will_paginate](https://github.com/mislav/will_paginate)
* PDF: [Prawn](https://github.com/prawnpdf/prawn)
* Dynamic nested forms: [cocoon](https://github.com/nathanvda/cocoon) 


## Testing:
* testing framework: [rspec-rails](https://github.com/rspec/rspec-rails), [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers), [factory-girl-rails](https://github.com/thoughtbot/factory_girl_rails)
* testing webservices: [vcr](https://github.com/vcr/vcr)
* integration: [capybara](https://github.com/jnicklas/capybara) with selenium-webdriver (no cucumber)
* page opening: [launchy](https://github.com/copiousfreetime/launchy)  
* email testing: [email-spec](https://github.com/bmabey/email-spec)

