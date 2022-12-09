# Zerocash: Decentralized Anonymous Payments from Bitcoin

[Original PDF](http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf)

There are two repositories that contain code to reproduce figures and results in the paper.

## Figures 7.1 - 7.2

Repository: https://github.com/Zerocash/libzerocash

libzerocash contains the core protocol (SNARKs, key-private note encryption, etc).

## Figures 7.3

Repository: https://github.com/Zerocash/Zerocashd

Zerocashd depends on libzerocash and integrates it in Bitcoin's codebase. The numbers in 7.3 are from large-scale simulation of Zerocashd nodes.
