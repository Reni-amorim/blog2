# Load DSL and Setup Up Stages
require 'capistrano/setup'
require 'capistrano/deploy'

require 'capistrano/rails'
require 'capistrano/bundler'
require 'rvm1/capistrano3'
require 'capistrano/puma'
    install_plugin Capistrano::Puma  # Default puma tasks
    install_plugin Capistrano::Puma::Systemd

require 'sshkit/sudo'

# Loads custom tasks from 'lib/capistrano/tasks' if you have any defined.
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }

