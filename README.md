Terraform Provider for the Hetzner Cloud
==================

**This provider is still in development. It may and will change without notice.**

- Website: https://www.terraform.io
<img src="https://cdn.rawgit.com/hashicorp/terraform-website/master/content/source/assets/images/logo-hashicorp.svg" width="600px">

Maintainers
-----------

This provider plugin is maintained by:

* The Hetzner Cloud Team

Requirements
------------

-	[Terraform](https://www.terraform.io/downloads.html) 0.10.x
-	[Go](https://golang.org/doc/install) 1.8 (to build the provider plugin)

Building The Provider
---------------------

Clone repository to: `$GOPATH/src/github.com/hetznercloud/terraform-provider-hcloud`

```sh
$ mkdir -p $GOPATH/src/github.com/hetznercloud; cd $GOPATH/src/github.com/hetznercloud
$ git clone git@github.com:hetznercloud/terraform-provider-hcloud
```

Enter the provider directory and build the provider

```sh
$ cd $GOPATH/src/github.com/hetznercloud/terraform-provider-hcloud
$ make build
```

Using the provider
----------------------

Coming soon.

Upgrading the provider
----------------------

Coming soon.

Developing the Provider
---------------------------

If you wish to work on the provider, you'll first need [Go](http://www.golang.org) installed on your machine (version 1.8+ is *required*). You'll also need to correctly setup a [GOPATH](http://golang.org/doc/code.html#GOPATH), as well as adding `$GOPATH/bin` to your `$PATH`.

To compile the provider, run `make build`. This will build the provider and put the provider binary in the `$GOPATH/bin` directory.

```sh
$ make build
...
$ ./bin/terraform-provider-hcloud
...
```

In order to test the provider, you can simply run `make test`.

```sh
$ make test
```
