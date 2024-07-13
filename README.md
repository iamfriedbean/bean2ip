# bean2ip
Reconnaissance tool designed to read a list of URLs from standard input, resolve their IP addresses, and group URLs by their associated IP addresses

## How it works
Reads a list of URLs from standard input, performs DNS lookups to capture their IP addresses, and outputs the IP addresses along with the corresponding URLs. URLs sharing the same IP address are grouped together in the output. This can be particularly useful for reconnaissance tasks in large scale penetration testing, where understanding the IP addresses associated with a set of domains is critical.

## Basic Usage

```
cat URL_list.txt | bean2ip

```
## Installation
Part of the Bean Suite of Tools. See beanscan repository for installation.
