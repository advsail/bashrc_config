# bashrc_config

The bashrc configuration files.

Append the script pieces to .bashrc to enable corresponding feature.

Don't forget to source the new script.

```shell
$ source .bashrc
```

## Notes for .bashrc and .profile

These two configuration files are obtained form the default .bashrc and .profile 
of Ubuntu 16.04 LTS and modified on top of that.

Refer to this [post](http://www.joshstaiger.org/archives/2005/07/bash_profile_vs.html)
for on different OS, `.bashrc` and `.bash_profile` which is prior.

## Using Vim on Mac

If you are using Vim on Mac and the `indentline` is not showing.
Add `make_usr_local_bin_prior` to `.bashrc` and refer to `vim_config` repo for fixes.
