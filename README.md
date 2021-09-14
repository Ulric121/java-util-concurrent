# java util concurrent

### Main:用户线程与守护线程
+ 如果用户线程不是守护线程，则主线程结束，用户线程不结束<br>
+ 如果用户线程是守护线程，则主线程结束，用户线程结束

### sync：synchronized代码实现
1. SaleTicket：synchronized示例代码
2. ThreadDemo1：线程间通信wait()与notify()示例代码
   + 注意要使用while循环判断，而不能使用if判断，否则会存在虚假唤醒问题

### lock：lock代码实现
1. LSaleTicket：ReentrantLock示例代码