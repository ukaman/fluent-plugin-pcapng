require "bundler/gem_tasks"
require "rake/testtask"

Rake::TestTask.new(:test) do |test|
  test.libs << "test"
  test.test_files = FileList['test/**/test_*.rb']
  test.verbose = true
end

task :default => [:build]
