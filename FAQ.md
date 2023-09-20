### FAQ


1. **May be need administrative privileges** : use 'sudo' .


2. **Segmentation Fault**: reinstall vm with larger memory.

3. **No space left when downloading boost file**

   ```
   $ sudo lvextend -l +100%FREE -n /dev/ubuntu-vg/ubuntu-lv
   $ sudo resize2fs /dev/mapper/ubuntu--vg-ubuntu--lv
   ```

 4. **No libreadline7 package**: Install "libreadline-dev"

5. **openssl error**: The version of openssl should be 1.x.x

6. **CMake Errors**: Please check if `1. you installed the prerequisite packages completely`, and `2. you have a sufficient capacity`.

7. **We recommend you to use sufficient disk/memory capacity for the virtual machine. (i.e, disk: 20 GB, memory: Minimum 4 GB ).**

8. **When you want to remove tpcc database and reload it**:
   ```bash
   $ cd /path/to/base/directory
   $ ./mysql -uroot -p


   > drop database tpcc;
   > quit;
   ```
   start from step 3 in [tpcc installation guide](https://github.com/kyongs/MySQL-TPCC-Installation/blob/main/3_tpcc-mysql-installation.md).
