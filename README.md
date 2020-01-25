# Storage Scripts

This is a collection of scripts to condense the high-text-volume output of SMART and btrfs commands into a condense, actionable report. [See this article for a detailed walkthrough](https://markmcb.com/2020/01/25/simplified-smart-and-btrfs-reporting/).

## Example Output

```
CORE up 2 days, 4 hours, 4 minutes on 5.4.12-200.fc31.x86_64

DEV  CAPAC  AT  TMP  AGE  SLFTEST  PREFAIL
sda  466Gi  8   24C  1.8  6/043/.  ....
sdh  466Gi  15  27C  1.8  6/104/.  ....
sdd  932Gi  3   33C  1.6  3/012/.  ....

BTRFS_PATH  SIZE  AVAIL  USE%  SCB  ERR
/mnt/ops    932G  356G   54%   28   .

BTRFS_PATH  MAP        DEVICE   WRFCG
/mnt/ops    luks-a4aa  sda      .....
/mnt/ops    luks-fd8b  sdh      .....
/mnt/ops    luks-0b9c  sdd      .....
```
