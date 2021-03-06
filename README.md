The [InterPlanetary FileSystem (IPFS)](https://github.com/ipfs/) is a way to publish and fetch data.
It resembles a cross-over of git and bittorrent.

Like git commit IDs, IPFS hashes reference immutable content.

Like bittorrent, hashes are fetched via DHT from peers.

This repo is about adding a simplified perl implementation to the available software. The first step is a FUSE-based filesystem/decoder for the on-disk blocks of cached or pinned IPFS data.

## Install

### openSUSE
```bash
zypper ar -p 200 --refresh http://download.opensuse.org/repositories/devel:/languages:/perl/openSUSE_Leap_15.1/ perl
zypper in perl-Google-ProtocolBuffers
```
