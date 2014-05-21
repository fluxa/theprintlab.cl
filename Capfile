require 'config/harp-deploy'

ssh_options[:forward_agent] = true
default_run_options[:pty] = true
set :application, "theprintlab.cl"
set :repository,  "git@github.com:fluxa/theprintlab.cl.git"
set :user, "git"
set :password, "biohazard1980"
set :scm, :git
set :node_user, "git"
set :harp_binary, "/usr/bin/harp"
set :harp_port, "5000"
set :use_sudo, false
set :keep_releases, 2
role :app, "theprintlab.cl"
#set :node_env, "development" #or comment out for production
#set :app_environment, ""
set :deploy_to, "/home/git/apps/theprintlab.cl"