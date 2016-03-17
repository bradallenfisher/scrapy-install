# scrapy-install
Install Scrapy on Rhel
cools
    1  yum install openssh-server
    2  service sshd start
    3  chkconfig sshd on
    4  netstat
    5  yum install net-tools
    6  netstat -tulpn
    7  poweroff
    8  yum install nano wget gcc bzip2 make kernel-devel-`uname -r`
    9  groups
   10  groupadd admin
   11  usermod -G admin vagrant
   12  visudo
   13  su - vagrant
   14  wget http://yum.puppetlabs.com/el/7/products/x86_64/puppetlabs-release-7-10.noarch.rpm
   15  ls
   16  rpm -ivh puppetlabs-release-7-10.noarch.rpm 
   17  yum install puppet
   18  curl -L https://www.opscode.com/chef/install.sh | bash
   19  ls
   20  rm puppetlabs-release-7-10.noarch.rpm 
   21  yum clean all
   22  poweroff
   23  cd /media/
   24  ls
   25  ./autorun.sh 
   26  cd 64Bit/
   27  ls
   28  cd ..
   29  ls
   30  ./VBoxLinuxAdditions.run 
   31  ls
   32  cd ..
   33  umount /dev/cdrom 
   34  ls
   35  mount /dev/cdrom /media
   36  cd /media/
   37  ls
   38  ./VBoxLinuxAdditions.run 
   39  more /var/log/vboxadd-install.log 
   40  yum update
   41  yum install dkms
   42  yum install gcc
   43  yum install kernel-devel
   44  yum install kernel-uek-devel
   45  ls
   46  vi /etc/selinux/config 
   47  reboot
   48  cd /media/
   49  ls
   50  cd ..
   51  mount /dev/cdrom /media/
   52  cd /media/
   53  ls
   54  ./VBoxLinuxAdditions.run 
   55  tail -100 /var/log/vboxadd-install.log 
   56  poweroff
   57  ls
   58  mount /dev/cdrom /media/
   59  cd /media/
   60  ls
   61  ./VBoxLinuxAdditions.run 
   62  more /var/log/vboxadd-install.log 
   63  poweroff
   64  mount /dev/cdrom /media/
   65  ls
   66  cd /media/
   67  ./VBoxLinuxAdditions.run 
   68  cd
   69  umount /dev/cdrom 
   70  yum clean all
   71  poweroff
   72  yum install scrapy
   73  yum install python
   74  yum install pyum -y install python-pip
   75  yum -y install python-pip
   76  exit
   77  yum -y install python-pip
   78  pip install Scrapy
   79  python get-pip.py
   80  sudo yum upgrade python-setuptools
   81  sudo yum install python-wheel
   82  yum upgrade python-setuptools
   83  pip install Scrapy
   84  yum repolist
   85  wget https://bootstrap.pypa.io/ez_setup.py -O - | python
   86  pip install Scrapy
   87  python setup.py install --prefix=/opt/setuptools
   88  easy_install -U Scrapy
   89  yum easy_install lxml
   90  easy_install lxml
   91  yum install python-dev
   92  yum groupinstall -y 'development tools'
   93  easy_install -U Scrapy
   94  pip install Scrapy
   95  yum install libxslt-devel libxml2-devel
   96  pip install Scrapy
   97  yum install python-devel libxml2-devel libxslt-devel
   98  pip install Scrapy
   99  yum install pyOpenSSL
  100  pip install Scrapy
  101  yum install gcc
  102  pip install -U setuptools
  103  pip install --upgrade pip
  104  pip install Scrapy
  105  yum install libffi-dev
  106  sudo rpm --import http://apt.sw.be/RPM-GPG-KEY.dag.txt
  107  yum install libffi-devel
  108  yum install libssl-dev
  109  yum install openssl-devel
  110  ls -la
  111  pip install Scrapy
  112  ls -la
  113  history
