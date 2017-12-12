require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec)  do |parametr|
  parametr.rspec_opts = '--format documentation'
end

task test: :spec
task default: :spec
