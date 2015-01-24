Vagrant.configure(2) do |config|

  config.vm.box = 'ubuntu/trusty64'

  config.vm.provider 'virtualbox' do |virtualbox|
    virtualbox.memory = 1024
    virtualbox.cpus = 2
  end

  config.vm.define :development

end
