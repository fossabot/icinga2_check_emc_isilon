# check\_emc\_isilon.py
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fl13t%2Ficinga2_check_emc_isilon.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fl13t%2Ficinga2_check_emc_isilon?ref=badge_shield)


Plugin to check some status information about EMC Isilon storage system over snmp.

```bash
usage: check_emc_isilon.py [-h] [--host HOST] [--comm COMM] [--check CHECK]
                           [--warn WARN] [--crit CRIT]

Utility to check EMC Isilon storage status

optional arguments:
  -h, --help     show this help message and exit
  --host HOST    Enter host ip address or domain name
  --comm COMM    SNMP community
  --check CHECK  prefered check: check_emc_isilon_clusterhealth,
                 check_emc_isilon_nodehealth, check_emc_isilon_diskusage,
                 check_emc_isilon_diskstatus
  --warn WARN    Exit with WARNING status if less than INTEGER units of disk
                 are free
  --crit CRIT    Exit with CRITICAL status if less than PERCENT of disk space
                 is free

Written 2015, Dmytro Prokhorenkov
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fl13t%2Ficinga2_check_emc_isilon.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fl13t%2Ficinga2_check_emc_isilon?ref=badge_large)