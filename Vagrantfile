# rubocop:disable Naming/FileName
# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_DIR = File.dirname(__FILE__)

require "#{VAGRANTFILE_DIR}/vagrant/lib/forklift"

loader = Forklift::BoxLoader.new("#{VAGRANTFILE_DIR}/vagrant")
loader.load!
distributor = Forklift::BoxDistributor.new(loader.boxes)
distributor.distribute!

# rubocop:enable Naming/FileName
