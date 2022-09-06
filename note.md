topping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
hzw@ubuntu:/mnt/hgfs/MIPS_CPU/hzw/git_start/aa$ git remote add origin ssh://git@github.com:coolhou/github_first_day.git
fatal: Not a git repository (or any parent up to mount point /mnt/hgfs)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
hzw@ubuntu:/mnt/hgfs/MIPS_CPU/hzw/git_start/aa$ git clone git@github.com:coolhou/github_first_day.git
Cloning into 'github_first_day'...
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
hzw@ubuntu:/mnt/hgfs/MIPS_CPU/hzw/git_start/aa$ pwd
/mnt/hgfs/MIPS_CPU/hzw/git_start/aa









git push is ok,but git clone occur error,i am not finding reason. finally I try to operate git in my home directroy,that is ok
