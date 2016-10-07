# vmware_tool
A tool to manipulate VMware resources

## Usage
```
$ ./vmware_tool -h
usage: vmware_tool [-h] [-v] -H VC_HOST -u VC_USER [-p VC_PASS] [-d]
                   {list_vms,list_ss} ...

A tool to manipulate VMware resources

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         show program's version number and exit
  -H VC_HOST, --host VC_HOST
                        VMware hostname
  -u VC_USER, --user VC_USER
                        VMware username
  -p VC_PASS, --pass VC_PASS
                        VMware password
  -d, --debug           debug mode

commands:
  {list_vms,list_ss}
    list_vms            list VMs
    list_ss             list snapshots
```
