# spring_cloud_config_hello_world
* 使用spring cloud config的好处  
1，分布式机器很多，统一的配置中心是必要的，不然改一个配置，需要该n个节点，是灾难  
2，可以实现不停服修改配置，对于高可用的产品是有很大实际意义的  
3，config server可以实现自动刷新  

* 使用注意事项  
1，对于server端，必须的配置是@EnableConfigServer，spring.cloud.config.server.git.uri  
2，特别需要注意的是配置文件.properties或者.yml文件编码格式必须是UTF-8


