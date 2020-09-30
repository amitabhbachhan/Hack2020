# Hack2020

vim  /etc/sysconfig/shellinaboxd                                                                                                              
    2  vi  /etc/sysconfig/shellinaboxd                                                                                                               
    3  netstat -nap | grep shellinabox                                                                                                               
    4  passwd ec2-user                                                                                                                               
    5  setenforce 0                                                                                                                                  
    6  vi /etc/selinux/config                                                                                                                        
    7  service ssh restart                                                                                                                           
    8  vi /etc/ssh/sshd_config                                                                                                                       
    9  systemctl restart sshd                                                                                                                        
   10  gcc                                                                                                                                           
   11  dnf install gcc                                                                                                                               
   12  yum install python3*                                                                                                                          
   13  yum install python3                                                                                                                           
   14  yum install python3*                                                                                                                          
   15  rpm -ivf http://download-ib01.fedoraproject.org/pub/epel/7/x86_64/Packages/s/shellinabox-2.20-5.el7.x86_64.rpm                                
   16  rpm -ivf https://centos.pkgs.org/7/centos-x86_64/openssl-libs-1.0.2k-16.el7.x86_64.rpm.html                                                   
   17  rpm -ivf https://altlinux.pkgs.org/sisyphus/classic-x86_64/libcrypto10-1.0.2r-alt3.x86_64.rpm.html                                            
   18  rpm -ivf http://ftp.altlinux.org/pub/distributions/ALTLinux/Sisyphus/x86_64/RPMS.classic//libcrypto10-1.0.2r-alt3.x86_64.rpm                  
   19  rpm -ivf https://fedora.pkgs.org/30/fedora-x86_64/compat-openssl10-1.0.2o-5.fc30.x86_64.rpm.html                                              
   20  rpm -ivf http://download-ib01.fedoraproject.org/pub/fedora/linux/releases/30/Everything/x86_64/os/Packages/c/compat-openssl10-1.0.2o-5.fc30.x8
6_64.rpm                     
