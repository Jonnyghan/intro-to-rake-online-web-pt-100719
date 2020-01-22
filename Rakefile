namespace :greeting do 
desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

desc'Pones hola al Terminal!'
task :hola do 
  puts "Hola de Rake!"
end
end

task :environment do
  require_relative './config/environment'
end

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do 
    
    Student.create_table
  end
end