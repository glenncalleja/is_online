is_online
=====================================================

**Is Online** is a Python module meant for cli use which checks whether you are connected to the Internet. By default it creates a request to Cloudflare's DNS at 1.1.1.1

## Note:
`Is Online` is only meant to be used as a CLI tool. If you need something to monitor online reachability in your own Python scripts, use [Reachability](https://pypi.org/project/reachability/)


Installation
=====================================================

You can install is_online from [PyPI](https://pypi.org/project/is-online/)
```shell
pip install is-online
```

How to use
=====================================================

To use, simply run: 

```
$ is_online
You are Online!

$ is_online --host 4.4.4.4 --port 53 --timeout 53
You are Online!

```

By default, this checks connectivity against Cloudflare's 1.1.1.1 DNS Server