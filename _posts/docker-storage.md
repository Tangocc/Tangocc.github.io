http://dockone.io/article/1513

Deployment：工作在ReplicaSet之上，用于管理无状态应用，目前来说最好的控制器。支持滚动更新和回滚功能，还提供声明式配置。
DaemonSet：用于确保集群中的每一个节点只运行特定的pod副本，通常用于实现系统级后台任务。比如ELK服务
Job：只要完成就立即退出，不需要重启或重建。
Cronjob：周期性任务控制，不需要持续后台运行，
StatefulSet：管理有状态应用

ReplicaSet: 代用户创建指定数量的pod副本数量，确保pod副本数量符合预期状态，并且支持滚动式自动扩容和缩容功能。
