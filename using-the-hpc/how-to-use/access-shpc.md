# Access Your HPC Condo Allocation

After your [access request](request-access.md) has been approved and you have installed the [prerequisites](prerequisites.md), you can log in to the Open Protection Zone or the Moderate Protection Zone.

1. Open a Bash terminal (or see [here](prerequisites.md) if you need more help).

2. Execute `ssh username@tigris.doane.edu`.

3. When prompted, enter your password.

**By default, `/home` directories should be automatically created for you when logging into HPC Condos**.

You can run the following command on your terminal to see your files:

```bash
$ ls -lhtr /home/username
total 20K
drwxr-xr-x 2 username users 4 Apr 6 12:11 Test1
-rw-r--r-- 1 username users 982 Apr 6 12:11 setup.py
-rw-r--r-- 1 username users 1.5K Apr 6 12:11 readme.txt
-rw-r--r-- 1 username users 77 Apr 6 12:11 paralleltestpy2.py
```

- The `ls -lhtr /home/username` command will show the whole list and details of the files that the **username** has.
