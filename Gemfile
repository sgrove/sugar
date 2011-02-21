source 'http://rubygems.org'
source 'http://gems.github.com'

gem 'rails', '3.0.3'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# gem 'sqlite3-ruby', :require => 'sqlite3'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'

# To use debugger
# gem 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end


gem 'mysql'

# OpenID gem. The stock gem is incompatible with Ruby 1.9, this fixes that.
gem 'ruby-openid', :git => 'git://github.com/xxx/ruby-openid.git', :require => 'openid'

gem 'hpricot'
gem 'daemon-spawn', '0.2.0'
gem 'newrelic_rpm'

gem "delayed_job", :git => "git://github.com/pda/delayed_job.git"
#gem 'thinking-sphinx', :git => 'git://github.com/freelancing-god/thinking-sphinx.git', :branch  => 'rails3', :require => 'thinking_sphinx'
gem 'thinking-sphinx', '2.0.2', :require => 'thinking_sphinx'

# The GitHub version has fixed the deprecation notice, so let's use that for now
#gem 'ts-delayed-delta', '1.1.0', :require => 'thinking_sphinx/deltas/delayed_delta'
gem 'ts-delayed-delta', :git => 'git://github.com/freelancing-god/ts-delayed-delta.git', :require => 'thinking_sphinx/deltas/delayed_delta'

group :development do
	gem 'yui-compressor', :require => 'yui/compressor'
end

group :test do
	gem 'shoulda'
	gem 'factory_girl_rails'
end
