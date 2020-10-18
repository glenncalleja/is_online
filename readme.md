is_online
=====================================================

**Is Online** is a Python module meant for cli use which checks whether you are connected to the Internet. By default it creates a request to Cloudflare's DNS at 1.1.1.1

How to use
=====================================================

To use, simply run: 

```shell
$ is_online
You are Online!

$ is_online --host 4.4.4.4 --port 53 --timeout 53
You are Online!

```

By default, this checks connectivity against Cloudflare's 1.1.1.1 DNS Server