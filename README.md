# GUET1024-Homepage
GUET1024 official websi

# install
```
git clone git@github.com:guet1024/GUET1024-Homepage.git
cd GUET1024-Homepage
yarn install
```

# run
```
yarn docs:dev
```

# build
```
yarn docs:build
```

# develop
see [VuePress](https://vuepress.vuejs.org/)


# Actions CI/CD key point

1. ssh config `/etc/ssh/sshd_config`
```
...
# Authentication:

#LoginGraceTime 2m
PermitRootLogin yes
StrictModes yes
#MaxAuthTries 6
#MaxSessions 10

PubkeyAuthentication yes
...
```
2. echo ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys

3. chmod
```
chmod 600 ~/.ssh/id_rsa
chmod 700 ~/.ssh/
```
