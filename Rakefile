require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new
#para no tener que poner -Ilib
$:.unshift File.dirname(__FILE__) + 'lib'

task :default => :test


desc "Ejecutar tests"
task :test do
        sh "rspec spec/fraction_spec.rb --format documentation"

end