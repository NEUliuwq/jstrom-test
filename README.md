# jstrom-test
# jstrom-test
下载的wordcount的例子，通过在项目根目录（进入项目文件夹下）使用mvn打包（mvn clean package）。然后将target下的jar包上传到nimbus的storm安装目录下，执行：
storm jar com.jstorm.wd.TopologyWordCount stormtest 实现将任务提交至storm集群上。
注：该程序只是自己做提交任务的测试程序，仅供学习使用。
