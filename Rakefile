require 'rake'
require 'rspec/core/rake_task'

require 'rubocop/rake_task'
RuboCop::RakeTask.new

RSpec::Core::RakeTask.new(:spec) do |t|
  t.pattern = Dir.glob('spec/**/*_spec.rb')
end

task default: [:spec]
