# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError => e
  puts "ERROR: Rakefile: #{e.message}"
  return
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'clj'

  app.pods do
#    pod 'YapDatabase', git: 'https://github.com/ulutu/YapDatabase'
  end
end
