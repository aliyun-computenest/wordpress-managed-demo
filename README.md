详细说明请查看 [index.md](docs%2Findex.md)

文件说明

| 文件路径                                | 说明                                                                                                                   |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| config.yaml                         | 构建服务的配置文件，服务构建过程中会使用计算巢命令行工具[computenest-cli](https://pypi.org/project/computenest-cli/)，computenest-cli会基于该配置文件构建服务 |
| parameters.yaml                     | 本服务为托管版单租，使用该文件渲染服务商需要配置的网络参数，包括VpcId，VSwitch等                                                                       |
| artifact/wordpress-6.2-zh_CN.tar.gz | wordpress，构建过程会将该包发布为计算巢部署物                                                                                          |
| icons/service_logo.jpg              | 构建服务默认的图标                                                                                                            |
| templates/parameters.yaml           | 本服务为托管版单租服务，所以只需要用户填写一部分参数，通过该文件指定用户所填参数                                                                             |
| templates/template.yaml             | ROS模板文件，ROS模板引擎根据该模板能够自动创建出所有的资源                                                                                     |