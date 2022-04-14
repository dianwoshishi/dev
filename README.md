# generate blacklist configuration for nerd

## usage

python3 gen_primary_blacklist_configuration_file.py

```yml

# [attacks]iblocklist_spamhaus_drop by iBlocklist.com.:Spamhaus.org DROP (Don't Route Or Peer)  list. . source url is http://list.iblocklist.com/?list=zbdlwrqkabxbcppvrnos&fileformat=p2p&archiveformat=gz 
# 2022-04-12 23:02:02 	 last_time_updated_by_its_maintainers
# 2022-04-12 23:20:31 	 last_time_processed_by_us 
# 2022-04-12 23:02:02 	 last_time_we_checked
# check_frequency 	12.0
# average_update_frequency 	63.95
# ips 	18068480
# ips_min 	8848384
# ips_max 	21181952
# ipv 	ipv4
# hash 	net
# errors 	0
- id: iblocklist_spamhaus_drop
  name: '[attacks]iblocklist_spamhaus_drop by iBlocklist.com.'
  descr: 'Spamhaus.org DROP (Dont Route Or Peer)  list. . source url is http://list.iblocklist.com/?list=zbdlwrqkabxbcppvrnos&fileformat=p2p&archiveformat=gz '
  firehol_link: http://iplists.firehol.org/?ipset=iblocklist_spamhaus_drop
  provider_link: https://www.iblocklist.com/
  url: https://iplists.firehol.org/files/iblocklist_spamhaus_drop.netset
  regex: "^(\\P)"
  time:
    hour: "5"
    minute: 3
```