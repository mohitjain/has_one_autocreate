require 'spec/rake/spectask'

require 'echoe'
Echoe.new 'has_one_autocreate' do |p|
  p.description     = "Automatic creation and building for has_one relationships."
  p.url             = "http://github.com/jqr/has_one_autocreate"
  p.author          = "Elijah Miller"
  p.email           = "elijah.miller@gmail.com"
  p.retain_gemspec  = true
  p.need_tar_gz     = false
  p.extra_deps      = [
  ]
  p.ignore_pattern  = ['spec/test.sqlite3']
end

desc 'Default: run specs'
task :default => :spec
task :test => :spec
