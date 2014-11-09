[19:05:18] [pool-12-thread-1/INFO]: GroupManager - INFO -  Data files refreshed.
[19:06:03] [Spigot Watchdog Thread/ERROR]: The server has stopped responding!
[19:06:03] [Spigot Watchdog Thread/ERROR]: Please report this to http://www.spigotmc.org/
[19:06:03] [Spigot Watchdog Thread/ERROR]: Be sure to include ALL relevant console errors and Minecraft crash reports
[19:06:03] [Spigot Watchdog Thread/ERROR]: Spigot version: git-Spigot-1.7.9-R0.2-204-g534549b (MC: 1.7.10)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Server thread dump (Look for plugins here before reporting to Spigot!):
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Server thread
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 14 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.WinNTFileSystem.getBooleanAttributes(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.File.exists(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.WorldNBTStorage.getPlayerData(WorldNBTStorage.java:247)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.CraftOfflinePlayer.getData(CraftOfflinePlayer.java:179)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.CraftOfflinePlayer.getBukkitData(CraftOfflinePlayer.java:183)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.CraftOfflinePlayer.getLastPlayed(CraftOfflinePlayer.java:221)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.mixin.PlayedMixinDefault.getLastPlayed(PlayedMixinDefault.java:49)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.mixin.Mixin.getLastPlayed(Mixin.java:161)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.factions.entity.UPlayerColl.removePlayerDataAfterInactiveDaysRoutine(UPlayerColl.java:52)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.factions.task.TaskPlayerDataRemove.invoke(TaskPlayerDataRemove.java:43)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.ModuloRepeatTask.run(ModuloRepeatTask.java:76)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.scheduler.CraftTask.run(CraftTask.java:71)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.scheduler.CraftScheduler.mainThreadHeartbeat(CraftScheduler.java:350)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.MinecraftServer.v(MinecraftServer.java:641)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.DedicatedServer.v(DedicatedServer.java:289)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.MinecraftServer.u(MinecraftServer.java:584)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.MinecraftServer.run(MinecraftServer.java:490)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.ThreadServerApplication.run(SourceFile:628)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Entire Thread Dump:
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Thread-26
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 106 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.net.dns.ResolverConfigurationImpl.notifyAddrChange0(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.net.dns.ResolverConfigurationImpl$AddressChangeListener.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: pool-13-thread-1
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 84 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.getTask(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Chunk I/O Executor Thread-1
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 83 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.getTask(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: MV-Inv Profile Write Thread
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 82 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.onarandombox.multiverseinventories.util.data.FlatFilePlayerData$FileWriteThread.run(FlatFilePlayerData.java:208)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: File IO Thread
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 79 | Suspended: false | Native: false | State: TIMED_WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.sleep(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.FileIOThread.b(SourceFile:44)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.FileIOThread.run(SourceFile:23)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: pool-7-thread-4
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 68 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.getTask(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: pool-7-thread-3
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 67 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.getTask(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: RCON Listener #2
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 55 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Thread is waiting on monitor(s):
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:java.net.PlainSocketImpl.accept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.DualStackPlainSocketImpl.waitForNewConnection(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.DualStackPlainSocketImpl.socketAccept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.AbstractPlainSocketImpl.accept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.PlainSocketImpl.accept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.ServerSocket.implAccept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.ServerSocket.accept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.RemoteControlListener.run(SourceFile:69)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Query Listener #1
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 54 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Thread is waiting on monitor(s):
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:java.net.DualStackPlainDatagramSocketImpl.receive0(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:java.net.AbstractPlainDatagramSocketImpl.receive(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:java.net.DatagramSocket.receive(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:java.net.DatagramSocket.receive(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.DualStackPlainDatagramSocketImpl.socketReceiveOrPeekData(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.DualStackPlainDatagramSocketImpl.receive0(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.AbstractPlainDatagramSocketImpl.receive(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.DatagramSocket.receive(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.RemoteStatusListener.run(SourceFile:256)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Thread-16
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 45 | Suspended: false | Native: false | State: TIMED_WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.sleep(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.coreprotect.consumer.Consumer.run(Consumer.java:47)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Thread-15
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 44 | Suspended: false | Native: false | State: TIMED_WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.sleep(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.coreprotect.thread.CacheCleanUp.run(CacheCleanUp.java:14)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: ProtocolLib-StructureCompiler 0
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 42 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.getTask(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Thread-13
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 40 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Thread is waiting on monitor(s):
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:java.net.PlainSocketImpl.accept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.DualStackPlainSocketImpl.accept0(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.DualStackPlainSocketImpl.socketAccept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.AbstractPlainSocketImpl.accept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.PlainSocketImpl.accept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.ServerSocket.implAccept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.net.ServerSocket.accept(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.vexsoftware.votifier.net.VoteReceiver.run(VoteReceiver.java:114)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: pool-12-thread-1
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 38 | Suspended: false | Native: false | State: TIMED_WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.parkNanos(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.getTask(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: pool-7-thread-2
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 35 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.getTask(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: pool-7-thread-1
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 34 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.getTask(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Netty IO #2
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 26 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Thread is waiting on monitor(s):
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.poll0(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.poll(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.access$400(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl.doSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.SelectorImpl.select(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.channel.nio.NioEventLoop.select(NioEventLoop.java:591)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:301)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.util.concurrent.SingleThreadEventExecutor$2.run(SingleThreadEventExecutor.java:101)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: MStore ExamineThread
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 33 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.WinNTFileSystem.getBooleanAttributes(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.File.isDirectory(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.store.DriverFlatfile.getId2mtime(DriverFlatfile.java:99)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.store.Coll.findSuspects(Coll.java:775)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.store.ExamineThread.run(ExamineThread.java:46)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Netty IO #1
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 25 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Thread is waiting on monitor(s):
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.poll0(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.poll(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.access$400(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl.doSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.SelectorImpl.select(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.channel.nio.NioEventLoop.select(NioEventLoop.java:591)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:301)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.util.concurrent.SingleThreadEventExecutor$2.run(SingleThreadEventExecutor.java:101)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Netty IO #0
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 24 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Thread is waiting on monitor(s):
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.poll0(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.poll(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl$SubSelector.access$400(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.WindowsSelectorImpl.doSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.SelectorImpl.lockAndDoSelect(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.nio.ch.SelectorImpl.select(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.channel.nio.NioEventLoop.select(NioEventLoop.java:591)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:301)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.io.netty.util.concurrent.SingleThreadEventExecutor$2.run(SingleThreadEventExecutor.java:101)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Spigot Metrics Thread
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 23 | Suspended: false | Native: false | State: TIMED_WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Object.wait(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.TimerThread.mainLoop(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.TimerThread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Spigot Watchdog Thread
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 22 | Suspended: false | Native: false | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.management.ThreadImpl.dumpThreads0(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.management.ThreadImpl.dumpAllThreads(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.spigotmc.WatchdogThread.run(WatchdogThread.java:76)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Java2D Disposer
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 20 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Object.wait(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.ref.ReferenceQueue.remove(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.ref.ReferenceQueue.remove(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.java2d.Disposer.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Thread-5
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 18 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		sun.misc.Unsafe.park(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.LockSupport.park(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.concurrent.LinkedBlockingQueue.take(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.util.com.mojang.util.QueueLogAppender.getNextLogEvent(QueueLogAppender.java:73)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.util.TerminalConsoleWriterThread.run(TerminalConsoleWriterThread.java:25)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Server console handler
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 17 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Thread is waiting on monitor(s):
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:java.io.BufferedInputStream.read(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:org.bukkit.craftbukkit.libs.jline.internal.InputStreamReader.read(InputStreamReader.java:267)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		Locked on:org.bukkit.craftbukkit.libs.jline.internal.InputStreamReader.read(InputStreamReader.java:204)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.FileInputStream.readBytes(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.FileInputStream.read(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.BufferedInputStream.fill(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.BufferedInputStream.read(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.FilterInputStream.read(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.libs.jline.console.ConsoleReader$1.read(ConsoleReader.java:167)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.libs.jline.internal.InputStreamReader.read(InputStreamReader.java:267)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.libs.jline.internal.InputStreamReader.read(InputStreamReader.java:204)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.libs.jline.console.ConsoleReader.readCharacter(ConsoleReader.java:995)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.libs.jline.console.ConsoleReader.readLineSimple(ConsoleReader.java:1506)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.libs.jline.console.ConsoleReader.readLine(ConsoleReader.java:1153)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.libs.jline.console.ConsoleReader.readLine(ConsoleReader.java:1117)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.libs.jline.console.ConsoleReader.readLine(ConsoleReader.java:1105)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.ThreadCommandReader.run(ThreadCommandReader.java:34)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: DestroyJavaVM
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 16 | Suspended: false | Native: false | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Server thread
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 14 | Suspended: false | Native: true | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.FileInputStream.close0(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.FileInputStream.close(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.zip.InflaterInputStream.close(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.zip.GZIPInputStream.close(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.BufferedInputStream.close(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.io.FilterInputStream.close(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.NBTCompressedStreamTools.a(NBTCompressedStreamTools.java:28)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.WorldNBTStorage.getPlayerData(WorldNBTStorage.java:248)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.CraftOfflinePlayer.getData(CraftOfflinePlayer.java:179)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.CraftOfflinePlayer.getBukkitData(CraftOfflinePlayer.java:183)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.CraftOfflinePlayer.getLastPlayed(CraftOfflinePlayer.java:221)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.mixin.PlayedMixinDefault.getLastPlayed(PlayedMixinDefault.java:49)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.mixin.Mixin.getLastPlayed(Mixin.java:161)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.factions.entity.UPlayerColl.removePlayerDataAfterInactiveDaysRoutine(UPlayerColl.java:52)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.factions.task.TaskPlayerDataRemove.invoke(TaskPlayerDataRemove.java:43)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		com.massivecraft.massivecore.ModuloRepeatTask.run(ModuloRepeatTask.java:76)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.scheduler.CraftTask.run(CraftTask.java:71)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		org.bukkit.craftbukkit.v1_7_R4.scheduler.CraftScheduler.mainThreadHeartbeat(CraftScheduler.java:350)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.MinecraftServer.v(MinecraftServer.java:641)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.DedicatedServer.v(DedicatedServer.java:289)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.MinecraftServer.u(MinecraftServer.java:584)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.MinecraftServer.run(MinecraftServer.java:490)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.ThreadServerApplication.run(SourceFile:628)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Server Infinisleeper
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 15 | Suspended: false | Native: false | State: TIMED_WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Thread.sleep(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		net.minecraft.server.v1_7_R4.ThreadSleepForever.run(SourceFile:63)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Snooper Timer
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 11 | Suspended: false | Native: false | State: TIMED_WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Object.wait(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.TimerThread.mainLoop(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.util.TimerThread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Attach Listener
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 5 | Suspended: false | Native: false | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Signal Dispatcher
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 4 | Suspended: false | Native: false | State: RUNNABLE
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Finalizer
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 3 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Object.wait(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.ref.ReferenceQueue.remove(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.ref.ReferenceQueue.remove(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.ref.Finalizer$FinalizerThread.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/ERROR]: Current Thread: Reference Handler
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	PID: 2 | Suspended: false | Native: false | State: WAITING
[19:06:03] [Spigot Watchdog Thread/ERROR]: 	Stack:
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Object.wait(Native Method)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.Object.wait(Object.java:503)
[19:06:03] [Spigot Watchdog Thread/ERROR]: 		java.lang.ref.Reference$ReferenceHandler.run(Unknown Source)
[19:06:03] [Spigot Watchdog Thread/ERROR]: ------------------------------
[19:06:03] [Spigot Watchdog Thread/INFO]: Startup script './start.sh' does not exist! Stopping server.
[19:06:03] [Thread-4/INFO]: Stopping server
