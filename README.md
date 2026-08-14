# Caveman for Claude Desktop

Claude Desktop-compatible marketplace for [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman).

The upstream marketplace points at the repository root, which contains a top-level bin directory. Claude Desktop's hosted validator rejects those executables. This repository exposes only the Desktop-safe plugin subtree and synchronizes it from upstream every day.

## Install

In Claude Desktop, open **Customize > Plugins > + > Add marketplace > Add from a repository**, then enter:

https://github.com/WeiZheng94/caveman-desktop-marketplace.git

Install **caveman** from the new marketplace.

## Updates

The Sync Caveman upstream workflow checks the official repository daily. It can also be run manually from the Actions tab.

## Attribution

Caveman is maintained by Julius Brussee. This repository is only a compatibility mirror and does not claim authorship of Caveman.
