### This Repo usage:   Periodic renewing source codes for JD auto checkin .
  

#### Repo url:
> Github: https://github.com/HiJohnDoe/jd_actions.git  
> Gitee(backup): https://gitee.com/whiteeyes/jd_actions.git  

Detail:
|    Project   | branch               |                 usage               |
| ------------ | -------------------------------------- | ---------------   |
|  jd_actions  | main   (default)     |              Do github action for repo synchronic and backup          |
|              | LXK9301_docker           |             sync from: https://gitee.com/lxk0301/jd_docker.git           |
|              | ~~LXK9301~~              |             ~~sync from: https://gitee.com/lxk0301/jd_scripts.git~~           |
|              | ~~MrRight~~              |             ~~sync from: https://gitlab.com/MrRight/Scripts.git~~          |
|              | ~~lifeishard4me~~        |             ~~sync from: https://github.com/lifeishard4me/Actions.git~~          |

Time schedule:
|    Type  |        Time               |
|--------------| --------------------------|
|     Sync     | cron:  '5 0,8,16 * * *'  every 0:05 8:05 16:05 utc |
|     Backup   | cron:  '20 0,8,16 * * *' every 0:20 8:20 16:20 utc   |

> Just in case some source repo getting banned , I will release source codes regularly.  
> Release page: https://github.com/HiJohnDoe/jd_actions/releases
