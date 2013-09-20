from ubuntu
run apt-get install -y openssh-server
run rm /etc/init/*
run mkdir -p /var/run/sshd /root/.ssh
add authorized_keys /root/.ssh/
add sshd.conf /etc/init/
run chown -R root /root
expose 2222:22
cmd ["/sbin/init", "--session", "-v", "1", ">log", "2>err"]

