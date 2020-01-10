Vagrant.configure("2") do |config|
  config.vm.box = "bento/debian-9.11"

  # Run Ansible from the Vagrant VM
  config.vm.provision "ansible_local" do |ansible|
    ansible.verbose = "vv"
    ansible.playbook = "playbooks/vagrant.yml"
  end
end
