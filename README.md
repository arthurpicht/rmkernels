# rmkernels
Simple bash script for selectively removing unused APT kernel packages. Tested for Ubuntu 16.04.

## Installation

Download *rmkernels* and copy it to */usr/local/sbin* or some other place on your path.

## Usage

1. Call 

        $ rmkernel -determine
    
    to create a list of old kernel related packages.
    
2. Edit file *~/.obsolteKernels*. Remove package names that should be kept untouched.

3. Call 

        $ rmkernel -exec
        
    with super user privileges to remove selected kernel related packages
    
## Disclaimer

No warranty! Use it on your own risk.