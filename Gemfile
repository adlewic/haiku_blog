source "http://rubygems.org"
ruby "2.3.0"

gem "sinatra"
gem "activerecord"
gem "sinatra-activerecord"
gem 'sqlite3', group: :development
group :production do
    gem 'pg'
    gem 'rails_12factor'
end
gem "rake"
gem "sinatra-flash"
gem "pg", :group => :production
gem "rails_12factor", :group => :production
# gem uninstall activerecord —version 5.0.0