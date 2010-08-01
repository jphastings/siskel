require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "siskel"
    gem.summary = %Q{A nippy video metadata inspector library}
    gem.description = %Q{Inspect a video/audio file for properties and metadata, using mediainfo}
    gem.email = "jphastings@gmail.com"
    gem.homepage = "http://github.com/jphastings/AirVideo"
    gem.authors = ["JP Hastings-Spital","Jon Dahl"]
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

task :default => :build