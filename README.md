Simprot
=======

Elisabeth Tillier, Andy Pang, Andrew Smith, Robert Charlebois, Paulo Nuin

Simprot1.04



// This program is free software: you can redistribute it and/or modify
// it under the terms of the GNU General Public License as published by
// the Free Software Foundation, either version 3 of the License, or
// (at your option) any later version.

// This program is distributed in the hope that it will be useful,
// but WITHOUT ANY WARRANTY; without even the implied warranty of
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// GNU General Public License for more details.


Please cite:

Nuin PAS., Wang Z., and ERM Tillier. (2006) The accuracy of several multiple sequence alignments for proteins. BMC Bioinformatics 7:471.

Pang, A., Smith, A. Nuin, PAS and ERM Tillier. (2005) SIMPROT: Using an empirically determined Indel distribution in simulations of protein evolution. BMC Bioinformatics:  6:236.


Usage: simprot1.04_mac [OPTION...]
  -a, --alignment=<string>               name of output alignment file, in fasta format (default: null)
  -b, --branch=<double>                  branch length scale multiplier (default: 1)
  -c, --eFactor=<double>                 Evolutionary Scale factor for the distribution of indel lengths
                                         (default: 3)
  -d, --debug                            debug mode
  -f, --tree=<string>                    name of tree file, only bifurcations are allowed (default: null)
  -g, --indelFrequency=<double>          the indel frequency for evolutionary time c (default: 0.03)
  -l, --maxIndel=<int>                   the maximum insertion/deletion length (default: 2048)
  -p, --subModel=<int>                   substitution model: 0 for PAM, 1 for JTT, 2 for PMB (default: 2)
  -r, --rootLength=<int>                 root sequence length (default: 50)
  -s, --sequence=<string>                name of output sequence file (default: null)
  -j, --phylip=<string>                  name of output phylip file (default: null)
  -x, --alpha=<double>                   gamma alpha. Set to -1 for equal evolutionary rates (default: 1)
  -i, --interleaved=<int>                interleaved output (default: 0)
  -y, --benner=<int>                     benner (default: 0)
  -v, --variableGamma=<int>              variable gamma (default: 0)
  -k, --bennerk=<int>                    benner k factor (default: -2)
  -w, --indelWeight=<double>             indel weighting parameter (default: 0)
  -t, --extraTerminalIndels=<double>     extra terminal indels parameter (default: 0)
  -z, --rootSequence=<string>            name of root sequence file (default: null)
  -u, --indel distribution=<string>      name of indel distribution file (default: null)
  -o, --indel output=<string>            file to output length of indels as created (default: null)
  -h, --correlation file=<string>        Correlated site pairs: i    j   correlation, only one site per.
                                         Indels are disabled for this option. (default: null)
  -e, --variableBranch=<double>          variable branch length scale multiplier (default: 0)
  -m, --branchExtinction=<double>        branch extinction probability (default: 0)
  -q, --InsDelRatio=<double>             prob of insertion (1 - prob of deletion) (would be 0.5 for equal
                                         frequencies) (default: 0.5)

Help options:
  -?, --help                             Show this help message
      --usage                            Display brief usage message
