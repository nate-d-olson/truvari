```
████████╗██████╗ ██╗   ██╗██╗   ██╗ █████╗ ██████╗ ██╗
╚══██╔══╝██╔══██╗██║   ██║██║   ██║██╔══██╗██╔══██╗██║
   ██║   ██████╔╝██║   ██║██║   ██║███████║██████╔╝██║
   ██║   ██╔══██╗██║   ██║╚██╗ ██╔╝██╔══██║██╔══██╗██║
   ██║   ██║  ██║╚██████╔╝ ╚████╔╝ ██║  ██║██║  ██║██║
   ╚═╝   ╚═╝  ╚═╝ ╚═════╝   ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝
```
![pylint](imgs/pylint.svg)

Structural variant toolkit for benchmarking, annotating and more for VCFs

[WIKI page](https://github.com/spiralgenetics/truvari/wiki) has detailed documentation.
See [Updates](https://github.com/spiralgenetics/truvari/wiki/Updates) on new versions.

## Installation
Truvari uses Python 3.6+ and can be installed with pip:
```
  pip install Truvari 
```
[PyPi](https://pypi.org/project/Truvari/#history) has a history of all versions available. Pip installs all requirements EXCEPT external tools needed for running some annotations. See [anno](https://github.com/spiralgenetics/truvari/wiki/anno) for details. 

To build and install Truvari from scratch:
```
  python setup.py install
```
 
 See [tags/](https://github.com/spiralgenetics/truvari/tags/) for a list of all available versions.
 
## Quick Start

Each sub-command contains help documentation. Start with `truvari -h` to see available commands.

The current most common Truvari use case is for structural variation benchmarking:
```
  truvari bench -b base.vcf.gz -c comp.vcf.gz -f reference.fasta -o output_dir/
```
## Truvari Commands

 - [bench](https://github.com/spiralgenetics/truvari/wiki/bench) - Performance metrics from comparison of two VCFs
 - [collapse](https://github.com/spiralgenetics/truvari/wiki/collapse) - Collapse possibly redundant VCF entries
 - [anno](https://github.com/spiralgenetics/truvari/wiki/anno) - Add SV annotations to a VCF
 - [vcf2df](https://github.com/spiralgenetics/truvari/wiki/truv2df) - Turn a VCF into a pandas DataFrame
 - [consistency](https://github.com/spiralgenetics/truvari/wiki/consistency) - Consistency report between multiple VCFs

## More Information

Find more details and discussions about Truvari on the [WIKI page](https://github.com/spiralgenetics/truvari/wiki).

[https://www.spiralgenetics.com](https://www.spiralgenetics.com)
