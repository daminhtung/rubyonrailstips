Mysql2 error gem: 
sudo gem install mysql2 -v '0.5.2' -- --with-ldflags=-L/usr/local/opt/openssl/lib --with-cppflags=-I/usr/local/opt/openssl/include

The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
Fetching gem metadata from https://rubygems.org/...
Retrying dependency api due to error (2/4): Bundler::HTTPError Network error while fetching https://index.rubygems.org/api/v1/dependencies?gems=bootsnap%2Cbyebug%2Ccapybara%2Cchromedriver-helper%2Ccoffee-rails%2Cjbuilder%2Clisten%2Cmysql2%2Cpuma%2Crails%2Csass-rails%2Cselenium-webdriver%2Cspring%2Cspring-watcher-listen%2Cturbolinks%2Ctzinfo-data%2Cuglifier%2Cweb-console (execution expired)............
Fetching gem metadata from https://rubygems.org/..
Resolving dependencies...
Using rake 12.3.2
Following files may not be writable, so sudo is needed:
  /Users/iOSDev/.rbenv/versions/2.6.1/lib/ruby/gems/2.6.0/build_info/mysql2-0.5.2.info
Using concurrent-ruby 1.1.5
Using i18n 1.6.0
Using minitest 5.11.3
Using thread_safe 0.3.6
Using tzinfo 1.2.5
Using activesupport 5.2.3
Using builder 3.2.3
Using erubi 1.8.0
Using mini_portile2 2.4.0
Using nokogiri 1.10.3
Using rails-dom-testing 2.0.3
Using crass 1.0.4
Using loofah 2.2.3
Using rails-html-sanitizer 1.0.4
Using actionview 5.2.3
Using rack 2.0.7
Using rack-test 1.1.0
Using actionpack 5.2.3
Using nio4r 2.3.1
Using websocket-extensions 0.1.3
Using websocket-driver 0.7.0
Using actioncable 5.2.3
Using globalid 0.4.2
Using activejob 5.2.3
Using mini_mime 1.0.1
Using mail 2.7.1
Using actionmailer 5.2.3
Using activemodel 5.2.3
Using arel 9.0.0
Using activerecord 5.2.3
Using mimemagic 0.3.3
Using marcel 0.3.3
Using activestorage 5.2.3
Using public_suffix 3.0.3
Using addressable 2.6.0
Using io-like 0.3.0
Using archive-zip 0.12.0
Using bindex 0.7.0
Using msgpack 1.2.10
Using bootsnap 1.4.4
Using bundler 1.17.2
Using byebug 11.0.1
Using regexp_parser 1.5.1
Using xpath 3.2.0
Using capybara 3.21.0
Using childprocess 1.0.1
Using chromedriver-helper 2.1.1
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using coffee-script 2.4.1
Using method_source 0.9.2
Using thor 0.20.3
Using railties 5.2.3
Using coffee-rails 4.2.2
Using ffi 1.11.1
Using jbuilder 2.9.1
Using rb-fsevent 0.10.3
Using rb-inotify 0.10.0
Using ruby_dep 1.5.0
Using listen 3.1.5
Fetching mysql2 0.4.10


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle install --path vendor/bundle

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password: 
Installing mysql2 0.4.10 with native extensions
Gem::Ext::BuildError: ERROR: Failed to build gem native extension.

    current directory: /private/var/folders/r0/bbc_pzms6l74_gr_yppw3h440000gn/T/bundler20190525-12785-1dnaqofmysql2-0.4.10/gems/mysql2-0.4.10/ext/mysql2
/Users/iOSDev/.rbenv/versions/2.6.1/bin/ruby -I /Users/iOSDev/.rbenv/versions/2.6.1/lib/ruby/2.6.0 -r ./siteconf20190525-12785-wpzacj.rb extconf.rb --with-mysql-config\=/usr/local/bin/mysql/mysql_config
checking for rb_absint_size()... yes
checking for rb_absint_singlebit_p()... yes
checking for ruby/thread.h... yes
checking for rb_thread_call_without_gvl() in ruby/thread.h... yes
checking for rb_thread_blocking_region()... no
checking for rb_wait_for_single_fd()... yes
checking for rb_hash_dup()... yes
checking for rb_intern3()... yes
checking for rb_big_cmp()... yes
-----
Cannot find mysql_config at /usr/local/bin/mysql/mysql_config
-----
*** extconf.rb failed ***
Could not create Makefile due to some reason, probably lack of necessary
libraries and/or headers.  Check the mkmf.log file for more details.  You may
need configuration options.

Provided configuration options:
	--with-opt-dir
	--without-opt-dir
	--with-opt-include
	--without-opt-include=${opt-dir}/include
	--with-opt-lib
	--without-opt-lib=${opt-dir}/lib
	--with-make-prog
	--without-make-prog
	--srcdir=.
	--curdir
	--ruby=/Users/iOSDev/.rbenv/versions/2.6.1/bin/$(RUBY_BASE_NAME)
	--with-mysql-dir
	--without-mysql-dir
	--with-mysql-include
	--without-mysql-include=${mysql-dir}/include
	--with-mysql-lib
	--without-mysql-lib=${mysql-dir}/lib
	--with-mysql-config

To see why this extension failed to compile, please check the mkmf.log which can be found here:

  /var/folders/r0/bbc_pzms6l74_gr_yppw3h440000gn/T/bundler20190525-12785-1dnaqofmysql2-0.4.10/extensions/x86_64-darwin-17/2.6.0-static/mysql2-0.4.10/mkmf.log

extconf failed, exit code 1

Gem files will remain installed in /var/folders/r0/bbc_pzms6l74_gr_yppw3h440000gn/T/bundler20190525-12785-1dnaqofmysql2-0.4.10/gems/mysql2-0.4.10 for inspection.
Results logged to /var/folders/r0/bbc_pzms6l74_gr_yppw3h440000gn/T/bundler20190525-12785-1dnaqofmysql2-0.4.10/extensions/x86_64-darwin-17/2.6.0-static/mysql2-0.4.10/gem_make.out

An error occurred while installing mysql2 (0.4.10), and Bundler cannot continue.
Make sure that `gem install mysql2 -v '0.4.10' --source 'https://rubygems.org/'` succeeds before bundling.

In Gemfile:
  mysql2
  
  
# Solution

## sudo gem install mysql2 -v '0.5.2' -- --with-ldflags=-L/usr/local/opt/openssl/lib --with-cppflags=-I/usr/local/opt/openssl/include
