# Kernel Rebaser Script
A script to rebase an OEM kernel to Code Linaro's Kernel

## How to use?
```bash
$ ./kernel-rebase.sh "<link to oem kernel source (git)>" "<ack-branch>"
```

### Example:
```bash
./kernel-rebase.sh "https://github.com/MiCode/Xiaomi_Kernel_OpenSource.git -b dandelion-q-oss" "android-4.9-q"
```
