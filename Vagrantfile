Vagrant.configure("2") do |config|

  config.vm.define "build-host-01" do |build-host-01|
    build-host-01.vm.box = "debian/buster64"
    build-host-01.vm.hostname = "build-host-01.hasanyousuf.com"
    #build-host-01.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.17"
    build-host-01.vm.provider "libvirt" do |v|
      v.memory = 2048
      v.name = "build-host-01"
      v.cpus = 1
    end
  end

  config.vm.define "build-host-02" do |build-host-02|
    build-host-02.vm.box = "debian/buster64"
    build-host-02.vm.hostname = "build-host-02.hasanyousuf.com"
    #build-host-02.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.18"
    build-host-02.vm.provider "libvirt" do |v|
      v.memory = 2048
      v.name = "build-host-02"
      v.cpus = 1
    end
  end

  config.vm.define "jenkins" do |jenkins|
    jenkins.vm.box = "debian/buster64"
    jenkins.vm.hostname= "jenkins.hasanyousuf.com"
    #jenkins.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.19"
    jenkins.vm.provider "libvirt" do |v|
      v.memory = 2048
      v.name = "jenkins"
      v.cpus = 1
    end
  end

  config.vm.define "gitlab" do |gitlab|
    gitlab.vm.box = "debian/buster64"
    gitlab.vm.hostname = "gitlab.hasanyousuf.com"
    #gitlab.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.20"
    gitlab.vm.provider "libvirt" do |v|
      v.memory = 2048
      v.name = "gitlab"
      v.cpus = 1
    end
    #gitlab.vm.network "public_network", bridge: "en1: Wi-Fi (AirPort)"
  end

  config.vm.define "yum-server" do |yum-server|
    yum-server.vm.box = "debian/buster64"
    yum-server.vm.hostname = "yum-server.hasanyousuf.com"
    #server.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.21"
    server.vm.provider "libvirt" do |v|
      v.memory = 2048
      v.name = "server"
      v.cpus = 1
    end
  end

  config.vm.define "nexus-server" do |nexus-server|
    nexus-server.vm.box = "debian/buster64"
    nexus-server.vm.hostname = "nexus-server.hasanyousuf.com"
    #server.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.21"
    nexus-server.vm.provider "libvirt" do |v|
      v.memory = 1024
      v.name = "nexus-server"
      v.cpus = 1
    end
  end

  config.vm.define "jira" do |jira|
    jira.vm.box = "debian/buster64"
    jira.vm.hostname = "jira.hasanyousuf.com"
    #jira.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.21"
    jira.vm.provider "libvirt" do |v|
      v.memory = 4096
      v.name = "jira"
      v.cpus = 1
    end
  end



  config.vm.define "confluence" do |confluence|
    confluence.vm.box = "debian/buster64"
    confluence.vm.hostname = "confluence.hasanyousuf.com"
    #dev-server-02.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.21"
    confluence.vm.provider "libvirt" do |v|
      v.memory = 4096
      v.name = "confluence"
      v.cpus = 1
    end
  end

  config.vm.define "dev-server-01" do |dev-server-01|
    dev-server-01.vm.box = "debian/buster64"
    dev-server-01.vm.hostname = "dev-server-01.hasanyousuf.com"
    #dev-server-01.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.21"
    dev-server-01.vm.provider "libvirt" do |v|
      v.memory = 2048
      v.name = "dev-server-01"
      v.cpus = 1
    end
  end


  config.vm.define "dev-server-01" do |dev-server-01|
    dev-server-01.vm.box = "debian/buster64"
    dev-server-01.vm.hostname = "dev-server-01.hasanyousuf.com"
    #dev-server-01.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 8265", ip: "192.168.0.21"
    dev-server-01.vm.provider "libvirt" do |v|
      v.memory = 2048
      v.name = "dev-server-01"
      v.cpus = 1
    end
  end



end