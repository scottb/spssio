# frozen_string_literal: true

begin
  require "rspec/core/rake_task"
  RSpec::Core::RakeTask.new(:spec)

  task default: :spec
rescue LoadError # rubocop:disable Lint/HandleExceptions
end
