source :rubygems

puppetversion = ENV.key?('PUPPET_VERSION') ? "= #{ENV['PUPPET_VERSION']}" : ['~> 2.7.19']
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper', '>= 0.3.0'
gem 'guard-rspec', '~> 1.2.1'
gem 'rb-fsevent', '~> 0.9.1' if RUBY_PLATFORM =~ /darwin/i
