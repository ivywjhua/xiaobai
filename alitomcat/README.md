-Shell command is in interactive mode.
-Script command is in non-interactive mode.
-"job control" is forbidden in non-interactive mode.
-SIGINT is ignored by shell for backend job.

-
Server
Connector(Protocol Handler), Processor(Service Handler)

Server/Service/Connector, Adapter, ServletContainer
Connector/Acceptor, Poller, Executor
Cotainer/Engine, Host, Context, Wrapper

Each app has its own classloader and thread must change classloader when entering or exit from webapp


-AsyncContext
LongRunningServlet

AppContextLister //Init threadpool in the servletContextListener
AppAsyncListener //Aync listener, implement timeout method and send time out message to client
AsyncRequestProcessor //Worker thread, using AsyncContext and asyncContext.complete()
AsyncLongRunningServlet // Using AsyncContext and ThreadPoolExecutor to execute logic

servlet thread is not blocked by long running job.......
(simple polling, ajax polling, long polling, long polling and timeout)
http://www.importnew.com/8864.html
http://www.ibm.com/developerworks/cn/java/j-lo-comet/#icomments
http://www.ibm.com/developerworks/cn/java/j-lo-servlet30/#ibm-pcon


-pandora.sar osgi
http://www.cnblogs.com/dongqingswt/archive/2013/01/22/2872186.html
http://www.ibm.com/developerworks/cn/opensource/os-ecl-osgids/index.html
-hsf
http://www.cnblogs.com/dongqingswt/archive/2013/01/22/2872068.html
http://www.cnblogs.com/dongqingswt/archive/2013/01/23/2873976.html
http://www.cnblogs.com/dongqingswt/archive/2013/01/28/2880624.html
http://iwinit.iteye.com/blog/1745132

