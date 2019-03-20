# codeMachine
Utils to generate SSH code.

Mysql
1.修改mysql配置信息，在com.platform.tool.db.DbConn文件中修改url和password
2.修改表名和输出位置execute.RunEntrance的tableName和setGeneratePath
3.执行execute.RunEntrance类的mian方法即可

Orcal
1.修改orcal配置信息，在com.platform.tool.db.DbConn文件中将mysql注释并除去orcal注释，修改url和password
2.修改com.platform.tool.data.DataServiceImpl类的getDbTemplateData方法，37行注释掉38行取消注释
3.修改表名和输出位置execute.RunEntrance的tableName和setGeneratePath
4.执行execute.RunEntrance类的mian方法即可
