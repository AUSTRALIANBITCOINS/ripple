source :rubygems

gemspec

if ENV['RAILS31']
  gem 'activemodel', '~> 3.1.0'
else
  gem 'activemodel', '~> 3.0.10'
end

gem 'riak-client', :path => "../riak-client"

unless ENV['TRAVIS']
  gem 'guard-rspec'
  gem 'rb-fsevent'
  gem 'growl'
end

# platforms :mri_18, :jruby do
#   gem 'ruby-debug'
# end

# platforms :mri_19 do
#   gem 'ruby-debug19'
# end

platforms :jruby do
  gem 'jruby-openssl'
end
