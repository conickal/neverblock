require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "neverblock"
    gem.summary = %Q{Utilities for non-blocking stack components}
    gem.description = %Q{NeverBlock is a collection of classes and modules that help you write evented non-blocking applications in a seemingly blocking mannner.}
    gem.email = "conickal@gmail.com"
    gem.homepage = "http://github.com/conickal/neverblock"
    gem.authors = ["Muhammad A. Ali", "Ahmed Sobhi", "Osama Brekaa", "Nicholas Silva"]
    gem.add_dependency('eventmachine', '>= 0.12.2')
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

Dir['tasks/*.rake'].each { |rake| load rake }

task :default => :spec

