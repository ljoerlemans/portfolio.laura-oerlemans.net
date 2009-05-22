desc 'Generate website'
task :website_generate do
  sh %{jekyll}
end

desc 'Publish website to RubyFest.nl'
task :website_upload do
  puts "Website upload not configured. See Rakefile for details."
  # local_dir  = '_site'
  # user       = 'root'
  # host       = 'forsakenlabs.com'
  # remote_dir = '/var/www/vhosts/forsakenlabs.com'
  # sh %{ssh #{user}@#{host} "rm -rf #{remote_dir}/*"}
  # sh %{scp -r #{local_dir}/* #{user}@#{host}:#{remote_dir}}
end

desc 'Generate and upload website files'
task :website => [:website_generate, :website_upload]
