require "fileutils"

desc "Install bash completion"
task :install do
  FileUtils.cp "padrino", "/etc/bash_completion.d/padrino"
end

desc "Uninstall bash completion"
task :uninstall do
  FileUtils.rm "/etc/bash_completion.d/padrino"
end

