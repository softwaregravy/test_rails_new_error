Full output 

```zsh
─(ruby-3.1.2@test_rails_new_error:)────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────( ~/workspace/test_rails_new_error)─┐
└─(130:80%(attached;):12:23:%)── rails new ./ -d postgresql -T --skip-system-test -c tailwind                                                                                                                                                                                                                                                                                                                             ──(Wed,Jul05)─┘
       exist
      create  README.md
      create  Rakefile
   identical  .ruby-version
      create  config.ru
      create  .gitignore
      create  .gitattributes
      create  Gemfile
         run  git init from "."
Initialized empty Git repository in /Users/username/workspace/test_rails_new_error/.git/
      create  app
      create  app/assets/config/manifest.js
      create  app/assets/stylesheets/application.css
      create  app/channels/application_cable/channel.rb
      create  app/channels/application_cable/connection.rb
      create  app/controllers/application_controller.rb
      create  app/helpers/application_helper.rb
      create  app/jobs/application_job.rb
      create  app/mailers/application_mailer.rb
      create  app/models/application_record.rb
      create  app/views/layouts/application.html.erb
      create  app/views/layouts/mailer.html.erb
      create  app/views/layouts/mailer.text.erb
      create  app/assets/images
      create  app/assets/images/.keep
      create  app/controllers/concerns/.keep
      create  app/models/concerns/.keep
      create  bin
      create  bin/rails
      create  bin/rake
      create  bin/setup
      create  config
      create  config/routes.rb
      create  config/application.rb
      create  config/environment.rb
      create  config/cable.yml
      create  config/puma.rb
      create  config/storage.yml
      create  config/environments
      create  config/environments/development.rb
      create  config/environments/production.rb
      create  config/environments/test.rb
      create  config/initializers
      create  config/initializers/assets.rb
      create  config/initializers/content_security_policy.rb
      create  config/initializers/cors.rb
      create  config/initializers/filter_parameter_logging.rb
      create  config/initializers/inflections.rb
      create  config/initializers/new_framework_defaults_7_0.rb
      create  config/initializers/permissions_policy.rb
      create  config/locales
      create  config/locales/en.yml
      create  config/master.key
      append  .gitignore
      create  config/boot.rb
      create  config/database.yml
      create  db
      create  db/seeds.rb
      create  lib
      create  lib/tasks
      create  lib/tasks/.keep
      create  lib/assets
      create  lib/assets/.keep
      create  log
      create  log/.keep
      create  public
      create  public/404.html
      create  public/422.html
      create  public/500.html
      create  public/apple-touch-icon-precomposed.png
      create  public/apple-touch-icon.png
      create  public/favicon.ico
      create  public/robots.txt
      create  tmp
      create  tmp/.keep
      create  tmp/pids
      create  tmp/pids/.keep
      create  tmp/cache
      create  tmp/cache/assets
      create  vendor
      create  vendor/.keep
      create  storage
      create  storage/.keep
      create  tmp/storage
      create  tmp/storage/.keep
      remove  config/initializers/cors.rb
      remove  config/initializers/new_framework_defaults_7_0.rb
         run  bundle install
Fetching gem metadata from https://rubygems.org/...........
Resolving dependencies...
Using rake 13.0.6
Using concurrent-ruby 1.2.2
Using minitest 5.18.1
Using websocket-extensions 0.1.5
Using erubi 1.12.0
Using mini_mime 1.1.2
Fetching date 3.3.3
Using rack 2.2.7
Fetching timeout 0.4.0
Fetching bindex 0.8.1
Using marcel 1.0.2
Fetching racc 1.7.1
Using crass 1.0.6
Using bundler 2.3.7
Using builder 3.2.4
Fetching msgpack 1.7.1
Using nio4r 2.5.9
Using method_source 1.0.0
Fetching io-console 0.6.0
Using thor 1.2.2
Using zeitwerk 2.6.8
Using i18n 1.14.1
Fetching pg 1.5.3
Using tzinfo 2.0.6
Using websocket-driver 0.7.5
Using rack-test 2.1.0
Fetching sprockets 4.2.0
Installing timeout 0.4.0
Installing bindex 0.8.1 with native extensions
Installing msgpack 1.7.1 with native extensions
Installing date 3.3.3 with native extensions
Installing io-console 0.6.0 with native extensions
Installing racc 1.7.1 with native extensions
Fetching puma 5.6.6
Installing sprockets 4.2.0
Installing pg 1.5.3 with native extensions
Installing puma 5.6.6 with native extensions
Using activesupport 7.0.6
Fetching net-protocol 0.2.1
Installing net-protocol 0.2.1
Using globalid 1.1.0
Using activemodel 7.0.6
Fetching net-pop 0.1.2
Fetching net-smtp 0.3.3
Installing net-pop 0.1.2
Installing net-smtp 0.3.3
Using activejob 7.0.6
Using activerecord 7.0.6
Using nokogiri 1.15.3 (arm64-darwin)
Using rails-dom-testing 2.1.1
Using loofah 2.21.3
Using rails-html-sanitizer 1.6.0
Using actionview 7.0.6
Using actionpack 7.0.6
Fetching jbuilder 2.11.5
Using actioncable 7.0.6
Using activestorage 7.0.6
Using railties 7.0.6
Using actiontext 7.0.6
Fetching sprockets-rails 3.4.2
Fetching importmap-rails 1.2.1
Installing sprockets-rails 3.4.2
Installing jbuilder 2.11.5
Installing importmap-rails 1.2.1
Fetching stimulus-rails 1.2.1
Fetching tailwindcss-rails 2.0.29 (arm64-darwin)
Fetching turbo-rails 1.4.0
Fetching web-console 4.2.0
Installing stimulus-rails 1.2.1
Fetching reline 0.3.5
Installing web-console 4.2.0
Installing turbo-rails 1.4.0
Installing reline 0.3.5
Fetching irb 1.7.1
Installing irb 1.7.1
Fetching debug 1.8.0
Installing debug 1.8.0 with native extensions
Installing tailwindcss-rails 2.0.29 (arm64-darwin)
Fetching bootsnap 1.16.0
Fetching net-imap 0.3.6
Installing bootsnap 1.16.0 with native extensions
Installing net-imap 0.3.6
Using mail 2.8.1
Using actionmailbox 7.0.6
Using actionmailer 7.0.6
Using rails 7.0.6
Bundle complete! 13 Gemfile dependencies, 62 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
         run  bundle binstubs bundler
       rails  importmap:install
Add Importmap include tags in application layout
      insert  app/views/layouts/application.html.erb
Create application.js module as entrypoint
      create  app/javascript/application.js
Use vendor/javascript for downloaded pins
      create  vendor/javascript
      create  vendor/javascript/.keep
Ensure JavaScript files are in the Sprocket manifest
      append  app/assets/config/manifest.js
Configure importmap paths in config/importmap.rb
      create  config/importmap.rb
Copying binstub
      create  bin/importmap
       rails  turbo:install stimulus:install
Import Turbo
      append  app/javascript/application.js
Pin Turbo
      append  config/importmap.rb
Enable redis in bundle
        gsub  Gemfile
         run  bundle install
[92801, #<Thread:0x000000010262cd40 run>, #<NameError: uninitialized constant Gem::Source

      (defined?(@source) && @source) || Gem::Source::Installed.new
                                           ^^^^^^^^
Did you mean?  Gem::SourceList>, ["/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:18:in `source'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:50:in `extension_dir'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:339:in `have_file?'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:86:in `contains_requirable_file?'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1038:in `block (2 levels) in find_in_unresolved_tree'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2555:in `block (2 levels) in traverse'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `each'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `block in traverse'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `each'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `traverse'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1034:in `block in find_in_unresolved_tree'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `each'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `find_in_unresolved_tree'", "<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:114:in `require'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:18:in `source'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:50:in `extension_dir'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:339:in `have_file?'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:86:in `contains_requirable_file?'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1038:in `block (2 levels) in find_in_unresolved_tree'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2555:in `block (2 levels) in traverse'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `each'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `block in traverse'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `each'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `traverse'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1034:in `block in find_in_unresolved_tree'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `each'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `find_in_unresolved_tree'", "<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:114:in `require'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/net-http-persistent/lib/net/http/persistent.rb:1:in `<top (required)>'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendored_persistent.rb:11:in `require_relative'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendored_persistent.rb:11:in `<top (required)>'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/fetcher.rb:3:in `require_relative'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/fetcher.rb:3:in `<top (required)>'", "<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:85:in `require'", "<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:85:in `require'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli/install.rb:50:in `run'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:255:in `block in install'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/settings.rb:131:in `temporary'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:254:in `install'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:31:in `dispatch'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:25:in `start'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:48:in `block in <main>'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/friendly_errors.rb:103:in `with_friendly_errors'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:36:in `<main>'"]]
[92801, #<Thread:0x000000010262cd40 run>, #<RuntimeError: CRITICAL: RUBYGEMS_ACTIVATION_MONITOR.owned?: before false -> after true>, ["<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:167:in `ensure in require'", "<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:167:in `require'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/net-http-persistent/lib/net/http/persistent.rb:1:in `<top (required)>'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendored_persistent.rb:11:in `require_relative'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendored_persistent.rb:11:in `<top (required)>'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/fetcher.rb:3:in `require_relative'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/fetcher.rb:3:in `<top (required)>'", "<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:85:in `require'", "<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:85:in `require'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli/install.rb:50:in `run'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:255:in `block in install'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/settings.rb:131:in `temporary'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:254:in `install'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:31:in `dispatch'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:25:in `start'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:48:in `block in <main>'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/friendly_errors.rb:103:in `with_friendly_errors'", "/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:36:in `<main>'"]]
/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:18:in `source': uninitialized constant Gem::Source (NameError)

      (defined?(@source) && @source) || Gem::Source::Installed.new
                                           ^^^^^^^^
Did you mean?  Gem::SourceList
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:50:in `extension_dir'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:339:in `have_file?'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:86:in `contains_requirable_file?'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1038:in `block (2 levels) in find_in_unresolved_tree'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2555:in `block (2 levels) in traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `block in traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1034:in `block in find_in_unresolved_tree'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `find_in_unresolved_tree'
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:114:in `require'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:18:in `source'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:50:in `extension_dir'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:339:in `have_file?'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:86:in `contains_requirable_file?'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1038:in `block (2 levels) in find_in_unresolved_tree'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2555:in `block (2 levels) in traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `block in traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1034:in `block in find_in_unresolved_tree'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `find_in_unresolved_tree'
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:114:in `require'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/friendly_errors.rb:26:in `log_error'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/friendly_errors.rb:109:in `rescue in with_friendly_errors'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/friendly_errors.rb:101:in `with_friendly_errors'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:36:in `<main>'
<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:167:in `ensure in require': CRITICAL: RUBYGEMS_ACTIVATION_MONITOR.owned?: before false -> after true (RuntimeError)
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:167:in `require'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli/install.rb:50:in `run'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:255:in `block in install'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/settings.rb:131:in `temporary'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:254:in `install'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:31:in `dispatch'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:25:in `start'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:48:in `block in <main>'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/friendly_errors.rb:103:in `with_friendly_errors'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:36:in `<main>'
<internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:167:in `ensure in require': CRITICAL: RUBYGEMS_ACTIVATION_MONITOR.owned?: before false -> after true (RuntimeError)
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:167:in `require'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/net-http-persistent/lib/net/http/persistent.rb:1:in `<top (required)>'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendored_persistent.rb:11:in `require_relative'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendored_persistent.rb:11:in `<top (required)>'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/fetcher.rb:3:in `require_relative'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/fetcher.rb:3:in `<top (required)>'
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:85:in `require'
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:85:in `require'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli/install.rb:50:in `run'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:255:in `block in install'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/settings.rb:131:in `temporary'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:254:in `install'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:31:in `dispatch'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:25:in `start'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:48:in `block in <main>'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/friendly_errors.rb:103:in `with_friendly_errors'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:36:in `<main>'
/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:18:in `source': uninitialized constant Gem::Source (NameError)

      (defined?(@source) && @source) || Gem::Source::Installed.new
                                           ^^^^^^^^
Did you mean?  Gem::SourceList
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:50:in `extension_dir'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:339:in `have_file?'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:86:in `contains_requirable_file?'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1038:in `block (2 levels) in find_in_unresolved_tree'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2555:in `block (2 levels) in traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `block in traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1034:in `block in find_in_unresolved_tree'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `find_in_unresolved_tree'
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:114:in `require'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:18:in `source'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/rubygems_ext.rb:50:in `extension_dir'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:339:in `have_file?'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/basic_specification.rb:86:in `contains_requirable_file?'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1038:in `block (2 levels) in find_in_unresolved_tree'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2555:in `block (2 levels) in traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2550:in `block in traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:2548:in `traverse'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1034:in `block in find_in_unresolved_tree'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `each'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/specification.rb:1033:in `find_in_unresolved_tree'
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:114:in `require'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/net-http-persistent/lib/net/http/persistent.rb:1:in `<top (required)>'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendored_persistent.rb:11:in `require_relative'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendored_persistent.rb:11:in `<top (required)>'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/fetcher.rb:3:in `require_relative'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/fetcher.rb:3:in `<top (required)>'
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:85:in `require'
	from <internal:/Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/rubygems/core_ext/kernel_require.rb>:85:in `require'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli/install.rb:50:in `run'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:255:in `block in install'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/settings.rb:131:in `temporary'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:254:in `install'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:31:in `dispatch'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/cli.rb:25:in `start'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:48:in `block in <main>'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/3.1.0/bundler/friendly_errors.rb:103:in `with_friendly_errors'
	from /Users/username/.rvm/rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/bundler-2.3.7/libexec/bundle:36:in `<main>'
Switch development cable to use redis
        gsub  config/cable.yml
Could not find gem 'redis (~> 4.0)' in locally installed gems.
Run `bundle install` to install missing gems.
       rails  tailwindcss:install
Could not find gem 'redis (~> 4.0)' in locally installed gems.
Run `bundle install` to install missing gems.
```
