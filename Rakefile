require './config/env'
require 'sinatra/activerecord/rake'

task :env do
    require './config/env'
end

desc "Start up a console so that you can interact with your code and db"
task :console => :env do
    Pry.start
end

