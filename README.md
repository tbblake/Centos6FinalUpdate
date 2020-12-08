# Centos6FinalUpdate
A gnu patch file so you can update your Centos 6 systems with the final available updates


    cd /etc/yum.repos.d
    cp CentOS-Base.repo CentOS-Base.repo.bkup
    curl -LO https://raw.githubusercontent.com/tbblake/Centos6FinalUpdate/main/CentOS-Base.repo
