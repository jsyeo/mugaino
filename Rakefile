require "bundler/gem_tasks"
require 'net/http'

task :do_it do
  Net::HTTP.get('www.google.com', '/index.html')
end

task default: :do_it
