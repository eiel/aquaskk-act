# coding: utf-8

desc 'install'
task :install do
  install_path = "#{ENV['HOME']}/Library/Application\ Support/AquaSKK/"
  options = { :preserve => true }
  cp 'kana-rule.conf', install_path, options
  cp 'keymap.conf', install_path, options
end

task :default => :install
