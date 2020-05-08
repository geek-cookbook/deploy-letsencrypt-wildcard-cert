
[cookbookurl]: https://geek-cookbook.funkypenguin.co.nz
[kitchenurl]: https://discourse.kitchen.funkypenguin.co.nz
[discordurl]: http://chat.funkypenguin.co.nz
[patreonurl]: https://patreon.com/funkypenguin
[blogurl]: https://www.funkypenguin.co.nz
[hub]: https://hub.docker.com/r/funkypenguin/munin-node/

[![geek-cookbook](https://raw.githubusercontent.com/funkypenguin/www.funkypenguin.co.nz/master/images/geek-kitchen-banner.png)][cookbookurl]

 
# Contents

1. [What is this?](#what-is-this)
2. [How to use it?](#how-to-use-it)
3. [Why it exists?](#why-it-exists)



# What is this?

This is a simple template to create a &#34;deploy repository&#34;, which will use GitHub Action to deploy a helm chart into a Kubernetes cluster.

Features include:

:checkbox: Deployment uses RBAC to provide a per-service, per-namespace kubeconfig

# How to use it?

Make a new repository from this template

# Why it exists?

To make deployment / update of a helm-deployed app as easy as making a GitHub commit

