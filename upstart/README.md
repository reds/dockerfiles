upstart
=======

Running upstart in a container allows multiple processes to be managed. A database and a web server would be a prime example. This Dockerfile uses upstart to manage sshd. Add your public key to authorized_keys and then:

```bash
ssh -p 2222 localhost
```
