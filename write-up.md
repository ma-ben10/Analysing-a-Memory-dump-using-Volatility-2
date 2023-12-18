We possess a 'ch2.dmp' memory file with a size of 537 MB, indicating substantial RAM capacity. Initially, we will confirm the profile of this memory using Volatility 2
```bash
python2 ~/volatility/vol.py -f ch2.dmp imageinfo
```
we get this output here :
Suggested Profile(s) : Win7SP1x86_23418, Win7SP0x86, Win7SP1x86_24000, Win7SP1x86
                     AS Layer1 : IA32PagedMemoryPae (Kernel AS)
                     AS Layer2 : FileAddressSpace (/home/beng/ctf/rootme/forensics/comandandcontrol/ch2.dmp)
                      PAE type : PAE
                           DTB : 0x185000L
                          KDBG : 0x82929be8L
          Number of Processors : 1
     Image Type (Service Pack) : 0
                KPCR for CPU 0 : 0x8292ac00L
             KUSER_SHARED_DATA : 0xffdf0000L
           Image date and time : 2013-01-12 16:59:18 UTC+0000
     Image local date and time : 2013-01-12 17:59:18 +0100
     
**so we confirmed that the profile is:** "--profile=Win7SP1x86_23418"


