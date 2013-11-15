$:.unshift File.dirname(__FILE__) + 'lib'
$:.unshift '.lib', './spec'

require "bundler/gem_tasks"
require "rspec/core/rake_task"
RSpec::Core::RakeTask.new(:spec)

task :default => :doc

desc "Documentacion"
task :doc do
	sh "cat README.md"
end
