source 'https://rubygems.org' do
gem 'sinatra', '~> 1.4.4'
gem 'hashie'
gem 'octokit' #, '~> 2.0', '=< 2.0'
gem 'awesome_print' git: "github.com/awesome-print/awesome_print.git"
end

group :development do 
  gem "pry" 
end 
group :test do 
  gem "rspec"
end 

# OTHER NOTES ABOUT GEMFILE CONTENT
# Options for grabbing gems to enhance your code may ne resource from many options.

# use the group syntax to access gems during development.
# and hide them from the production/public versions of you app
# set gem for use in :development , :test, :production
# SYNTAX  gem "pry", :groups => [:development, :test]

# gem 'mail', '~> 2.6', '>= 2.6.3'
# Rubyists have decided to call this ~> "Twiddle-Wakka." '~> 2.6' 
# means any minor version above 2.6. 2.7, 2.8, and 2.9 would work (including patches); but version 3.0 wouldn't work because it indicates a new major version.

# The mail gem has a second specification '>= 2.6.3'. 
# This means any version greater than or equal to 2.6.3. Because the mail gem has two specifications, both have to be true, so this gem couldn't use version 2.6 because it's lower than 2.6.3

# gem 'rack', git: 'https://github.com/rack/rack'
# gem whose developer(s) haven't yet pushed the code to RubyGems.org. Maybe you're one of those developers yourself! In that case, Bundler provides a few options.
# You can refer to the gem via its GitHub repository:

# gem 'nokogiri', :git => 'login@example.com:some-user-account/some-private-gem.git'
# the gem is private and needs to be accessed via SSH