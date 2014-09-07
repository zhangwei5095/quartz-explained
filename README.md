### 1. 说明

- 对定时任务调度框架quartz的源码的分析和注释；

- quartz svn 源码的地址为：http://svn.terracotta.org/svn/quartz/trunk。

- 促使我有分析和注释源码的想法来自于@huangz1990同学对redis源码的注释，我觉得这是一种很好地学习和分享的方式，在此表示感谢！

- 欢迎来信交流：daniel5hbs dot gmail.com; (非常感谢insect liu同学的建议。)

### 2. 核心类的目录

### 2.1 Job相关

- [JobDetail.java](https://github.com/nkcoder/quartz-explained/blob/master/src%2Fmain%2Fjava%2Forg%2Fquartz%2FJobDetail.java)
- [JobBuilder.java](https://github.com/nkcoder/quartz-explained/blob/master/src%2Fmain%2Fjava%2Forg%2Fquartz%2FJobBuilder.java)
- Job.java
- JobDataMap.java
- JobKey.java
- JobListener.java
	

	
### 2.2 Trigger相关

- Trigger.java
- TriggerBuilder.java
- TriggerKey.java
- TriggerListener.java
- TriggerUtils.java
- SimpleTrigger.java
- CronTrigger.java
- TriggerListenerSupport.java
	
### 2.3 Scheduler相关

- Scheduler.java
- SchedulerBuilder.java
- SchedulerContext.java
- SchedulerFactory.java
- SchedulerListener.java
- SimpleSchedulerBuilder.java
