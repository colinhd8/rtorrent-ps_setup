# Change Log

## [0.9.7-0.9.7](https://github.com/chros73/rtorrent-ps_setup/tree/0.9.7-0.9.7) (2017-05-16)
**Implemented enhancements:**

- Enable peer exchange, UDP tracker, DHT support [\#111](https://github.com/chros73/rtorrent-ps_setup/issues/111)
- Remove unneeded external getLimits.sh script [\#110](https://github.com/chros73/rtorrent-ps_setup/issues/110)
- Add an email report about public torrents [\#109](https://github.com/chros73/rtorrent-ps_setup/issues/109)
- Support public torrents [\#108](https://github.com/chros73/rtorrent-ps_setup/issues/108)
- Rename ui.status.throttle.up.name config entry to ui.status.throttle.up [\#107](https://github.com/chros73/rtorrent-ps_setup/issues/107)
- Use d.selected\_size\_bytes instead of d.size in reports [\#106](https://github.com/chros73/rtorrent-ps_setup/issues/106)
- Use default view of rtorrent to query data by default [\#105](https://github.com/chros73/rtorrent-ps_setup/issues/105)
- Small color config changes [\#103](https://github.com/chros73/rtorrent-ps_setup/issues/103)
- Add support for using magnet downloads in load watch directory [\#102](https://github.com/chros73/rtorrent-ps_setup/issues/102)

## [0.9.6-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.9.6-0.9.6) (2017-01-22)
**Implemented enhancements:**

- Modify queue script to handle bogus torrents [\#101](https://github.com/chros73/rtorrent-ps_setup/issues/101)

**Fixed bugs:**

- Fix error handling of external commands in shell scripts [\#100](https://github.com/chros73/rtorrent-ps_setup/issues/100)

## [0.9.5-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.9.5-0.9.6) (2017-01-21)
**Fixed bugs:**

- Fix value returned by rtgetTotalRotatingSize\(\) if both directories are empty [\#99](https://github.com/chros73/rtorrent-ps_setup/issues/99)

## [0.9.4-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.9.4-0.9.6) (2016-10-12)
**Implemented enhancements:**

- Modify rtorrent config files [\#98](https://github.com/chros73/rtorrent-ps_setup/issues/98)
- Modify queue script to handle broken \(already deleted\) symlinks in .delqueue dir [\#97](https://github.com/chros73/rtorrent-ps_setup/issues/97)
- Modify queue script to handle oversized torrents [\#96](https://github.com/chros73/rtorrent-ps_setup/issues/96)
- Add an email report about low rotating space [\#95](https://github.com/chros73/rtorrent-ps_setup/issues/95)

## [0.9.3-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.9.3-0.9.6) (2016-08-24)
**Implemented enhancements:**

- Create a new watch directory for only loading but not starting downloads [\#94](https://github.com/chros73/rtorrent-ps_setup/issues/94)
- Modify what priority is assigned to downloads [\#93](https://github.com/chros73/rtorrent-ps_setup/issues/93)
- Extend stop downloading of a torrent but still uploading it on Hints wiki page [\#92](https://github.com/chros73/rtorrent-ps_setup/issues/92)
- Add fast resume section onto Hints wiki page [\#91](https://github.com/chros73/rtorrent-ps_setup/issues/91)
- Add system.file.allocate.set=1 into rtorrent config [\#90](https://github.com/chros73/rtorrent-ps_setup/issues/90)
- Change ui.status.throttle\_up\_name entry in rtorrent config [\#89](https://github.com/chros73/rtorrent-ps_setup/issues/89)

## [0.9.2-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.9.2-0.9.6) (2016-07-30)
**Implemented enhancements:**

- Add sshd config to the setup [\#88](https://github.com/chros73/rtorrent-ps_setup/issues/88)
- Docs: Add Installation instructions WIKI page [\#87](https://github.com/chros73/rtorrent-ps_setup/issues/87)
- Docs: Add Email Reports WIKI page [\#86](https://github.com/chros73/rtorrent-ps_setup/issues/86)
- Docs: Add Auto-Scraping WIKI page [\#85](https://github.com/chros73/rtorrent-ps_setup/issues/85)
- Docs: Add Queue Manager WIKI page [\#84](https://github.com/chros73/rtorrent-ps_setup/issues/84)
- Docs: Add Hints and Magnet link WIKI pages [\#83](https://github.com/chros73/rtorrent-ps_setup/issues/83)
- Docs: Move all the docs files to WIKI and also include them in a docs dir [\#82](https://github.com/chros73/rtorrent-ps_setup/issues/82)
- Docs: Add separate FavoringGroupOfTorrents file [\#81](https://github.com/chros73/rtorrent-ps_setup/issues/81)
- Docs: Add Performance Tuning section into main readme file [\#80](https://github.com/chros73/rtorrent-ps_setup/issues/80)
- Docs: Add separate Additions file [\#79](https://github.com/chros73/rtorrent-ps_setup/issues/79)

## [0.9.1-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.9.1-0.9.6) (2016-07-23)
**Implemented enhancements:**

- Modify 2 default rtorrent config values and enable sorting on Started view by default [\#75](https://github.com/chros73/rtorrent-ps_setup/issues/75)
- Add limited magnet link support [\#74](https://github.com/chros73/rtorrent-ps_setup/issues/74)

**Fixed bugs:**

- Fix small reporting bugs [\#78](https://github.com/chros73/rtorrent-ps_setup/issues/78)

## [0.9-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.9-0.9.6) (2016-07-18)
**Implemented enhancements:**

- Add meaningful information into main readme file [\#73](https://github.com/chros73/rtorrent-ps_setup/issues/73)
- Add separate change log file [\#72](https://github.com/chros73/rtorrent-ps_setup/issues/72)
- Add on-the-road config instructions for using free apps on Android  [\#71](https://github.com/chros73/rtorrent-ps_setup/issues/71)
- Modify config instruction in Windows section [\#70](https://github.com/chros73/rtorrent-ps_setup/issues/70)
- Replace PuTTY with KiTTY in Windows config section [\#69](https://github.com/chros73/rtorrent-ps_setup/issues/69)
- Add sample download script to demonstrate usage of inclusion of queue script [\#68](https://github.com/chros73/rtorrent-ps_setup/issues/68)
- Add queue management script with rotating capability and category support [\#66](https://github.com/chros73/rtorrent-ps_setup/issues/66)
- Refactor getLimit script [\#65](https://github.com/chros73/rtorrent-ps_setup/issues/65)
- Modify cron related scripts and variables [\#64](https://github.com/chros73/rtorrent-ps_setup/issues/64)
- Add more useful email reports [\#63](https://github.com/chros73/rtorrent-ps_setup/issues/63)
- Add an email report about all orphaned data [\#62](https://github.com/chros73/rtorrent-ps_setup/issues/62)
- Add a backup script for session directory of rtorrent [\#61](https://github.com/chros73/rtorrent-ps_setup/issues/61)
- Add general script with helper functions [\#60](https://github.com/chros73/rtorrent-ps_setup/issues/60)
- Add external save session command into init script [\#59](https://github.com/chros73/rtorrent-ps_setup/issues/59)

**Fixed bugs:**

- Fix getUptime script in certain conditions [\#67](https://github.com/chros73/rtorrent-ps_setup/issues/67)

## [0.8.5-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.8.5-0.9.6) (2016-07-10)
**Implemented enhancements:**

- Modify type of method of d.tm\_downloaded in rtorrent-ps config [\#58](https://github.com/chros73/rtorrent-ps_setup/issues/58)
- Modify getUptime.sh script to be more efficient [\#57](https://github.com/chros73/rtorrent-ps_setup/issues/57)

## [0.8.4-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.8.4-0.9.6) (2016-07-10)
**Implemented enhancements:**

- Add uptime method in rtorrent-ps config [\#56](https://github.com/chros73/rtorrent-ps_setup/issues/56)

## [0.8.3-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.8.3-0.9.6) (2016-07-09)
**Implemented enhancements:**

- Add commented out sorting for started view in rtorrent-ps config [\#55](https://github.com/chros73/rtorrent-ps_setup/issues/55)

## [0.8.2-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.8.2-0.9.6) (2016-07-09)
**Implemented enhancements:**

- Modify sorting on started view in rtorrent-ps config [\#54](https://github.com/chros73/rtorrent-ps_setup/issues/54)

## [0.8.1-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.8.1-0.9.6) (2016-07-08)
**Implemented enhancements:**

- Refactor how sorting, filtering used in rtorrent-ps config [\#53](https://github.com/chros73/rtorrent-ps_setup/issues/53)

**Fixed bugs:**

- Fix newly added deletable torrents don't show up in deletable view [\#52](https://github.com/chros73/rtorrent-ps_setup/issues/52)

## [0.8.0-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.8.0-0.9.6) (2016-07-07)
**Implemented enhancements:**

- Finalize rtorrent config files [\#51](https://github.com/chros73/rtorrent-ps_setup/issues/51)
- Add new custom view for deletable data [\#50](https://github.com/chros73/rtorrent-ps_setup/issues/50)
- Bind key to toggle through selectable themes in rtorrent config [\#49](https://github.com/chros73/rtorrent-ps_setup/issues/49)
- Bind key to toggle unsafe\_data attribute [\#48](https://github.com/chros73/rtorrent-ps_setup/issues/48)
- Bind key to send scrape request manually [\#47](https://github.com/chros73/rtorrent-ps_setup/issues/47)
- Refactor rtorrent-ps config file and add new views into it [\#46](https://github.com/chros73/rtorrent-ps_setup/issues/46)
- Rename the pyro import method and modify type of cfg.slowup.d.\* methods in rtorrent configs [\#45](https://github.com/chros73/rtorrent-ps_setup/issues/45)
- Modify type of methods in main and config rtorrent files [\#44](https://github.com/chros73/rtorrent-ps_setup/issues/44)
- Modify comments and refactor 1 method [\#42](https://github.com/chros73/rtorrent-ps_setup/issues/42)
- Add networking tweaks to the setup [\#40](https://github.com/chros73/rtorrent-ps_setup/issues/40)
- Add initial config files for ssmtp.conf and sysctl.conf [\#39](https://github.com/chros73/rtorrent-ps_setup/issues/39)
- Add more config directives into rtorrent config file [\#38](https://github.com/chros73/rtorrent-ps_setup/issues/38)
- Add postfix config entry [\#37](https://github.com/chros73/rtorrent-ps_setup/issues/37)
- Refactor watch dir logic and separate config directives [\#36](https://github.com/chros73/rtorrent-ps_setup/issues/36)
- Apply the new scripting style at some places in main config [\#35](https://github.com/chros73/rtorrent-ps_setup/issues/35)
- Remove version number from PS config filename [\#34](https://github.com/chros73/rtorrent-ps_setup/issues/34)

**Fixed bugs:**

- Add modified pyrocore config file [\#43](https://github.com/chros73/rtorrent-ps_setup/issues/43)
- Fix issue with human readable time method [\#41](https://github.com/chros73/rtorrent-ps_setup/issues/41)

## [0.7.1-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.7.1-0.9.6) (2016-06-29)
**Implemented enhancements:**

- Add more checks before moving and deleting data [\#33](https://github.com/chros73/rtorrent-ps_setup/issues/33)

**Fixed bugs:**

- Fix bug in checking data full path [\#32](https://github.com/chros73/rtorrent-ps_setup/issues/32)

## [0.7-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.7-0.9.6) (2016-06-28)
**Implemented enhancements:**

- Add an extra check before moving data and meta files [\#31](https://github.com/chros73/rtorrent-ps_setup/issues/31)

**Fixed bugs:**

- Fix bug with modifying slots [\#30](https://github.com/chros73/rtorrent-ps_setup/issues/30)

## [0.6-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.6-0.9.6) (2016-06-26)
**Implemented enhancements:**

- Add an extra check before deleting data [\#29](https://github.com/chros73/rtorrent-ps_setup/issues/29)
- Add support for possibly missing d.base\_path attribute [\#28](https://github.com/chros73/rtorrent-ps_setup/issues/28)
- Modify moving torrent logic  [\#27](https://github.com/chros73/rtorrent-ps_setup/issues/27)
- Remove unused nginx config files [\#26](https://github.com/chros73/rtorrent-ps_setup/issues/26)

## [0.5-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.5-0.9.6) (2016-06-24)
**Implemented enhancements:**

- Modify how delete-queue is handled [\#25](https://github.com/chros73/rtorrent-ps_setup/issues/25)

## [0.4-0.9.6](https://github.com/chros73/rtorrent-ps_setup/tree/0.4-0.9.6) (2016-06-24)
**Implemented enhancements:**

- Modify sorting Started view [\#24](https://github.com/chros73/rtorrent-ps_setup/issues/24)
- Check for pyro command existence [\#23](https://github.com/chros73/rtorrent-ps_setup/issues/23)
- Add more color configs [\#22](https://github.com/chros73/rtorrent-ps_setup/issues/22)
- Add additional color configs [\#21](https://github.com/chros73/rtorrent-ps_setup/issues/21)
- Comment out unused pyroscope features [\#20](https://github.com/chros73/rtorrent-ps_setup/issues/20)
- Lower dns timeout and refactor network related commands [\#19](https://github.com/chros73/rtorrent-ps_setup/issues/19)
- Add support for rtorrent-ps-ch [\#18](https://github.com/chros73/rtorrent-ps_setup/issues/18)
- Modify views [\#17](https://github.com/chros73/rtorrent-ps_setup/issues/17)
- Add support for delete-queue [\#16](https://github.com/chros73/rtorrent-ps_setup/issues/16)
- Rename category directories to be able to have unique first letter [\#15](https://github.com/chros73/rtorrent-ps_setup/issues/15)
- Rename main directories of metafiles [\#14](https://github.com/chros73/rtorrent-ps_setup/issues/14)
- Dynamically adjusts the global download rate and refactor existing code [\#13](https://github.com/chros73/rtorrent-ps_setup/issues/13)
- Refactor delete data functionality [\#12](https://github.com/chros73/rtorrent-ps_setup/issues/12)
- Add disable peer exchange to config [\#10](https://github.com/chros73/rtorrent-ps_setup/issues/10)
- Make a comment on current implementation of d.move\_data method [\#9](https://github.com/chros73/rtorrent-ps_setup/issues/9)
- Polish code and modify update interval of scraping for non-transfarring torrents [\#8](https://github.com/chros73/rtorrent-ps_setup/issues/8)
- Replace multiple time formatting methods with a generalized one [\#7](https://github.com/chros73/rtorrent-ps_setup/issues/7)
- Support non-official SSL trackers [\#6](https://github.com/chros73/rtorrent-ps_setup/issues/6)
- Regularly send scrape request to trackers [\#5](https://github.com/chros73/rtorrent-ps_setup/issues/5)
- Fix type of some methods in rtorrent config files that can cause problems in later versions [\#4](https://github.com/chros73/rtorrent-ps_setup/issues/4)
- Handle leftover pid file upon crash in init script [\#3](https://github.com/chros73/rtorrent-ps_setup/issues/3)
- Rename a function to status in init script [\#2](https://github.com/chros73/rtorrent-ps_setup/issues/2)

**Fixed bugs:**

- Fix small bugs [\#11](https://github.com/chros73/rtorrent-ps_setup/issues/11)



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*