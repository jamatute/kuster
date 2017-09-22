# Kuster

`kuster` is a program to extract in an easy way information of a kubernetes cluster.

# Installation

Clone the repository

```bash
git clone https://github.com/jamatute/kuster
```

Give executable permissions and move it into your path
```bash
chmod +x kuster/kuster
mv kuster/kuster {{ somewhere_in_your_path }}
```

# Configuration

Kuster executes `kubectl` commands, therefore you should have it configured
first.

# Use

Right now we have the following available commands

* `resources` : gives the number of pods, the requests and limit resources in
  each node.
* `pods`      : gives the name of the pods of each node
* `limits`    : gives the limits and requests of
  deployments/statefulsets/daemonsets
