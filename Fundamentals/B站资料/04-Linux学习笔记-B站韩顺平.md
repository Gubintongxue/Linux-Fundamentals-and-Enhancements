**目录**

[1.网络连接三种方式](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t0)

[1.1 桥接模式：虚拟系统可以和外部系统通讯，但是容易造成IP冲突【1-225】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t1)

[1.2 NAT模式：网络地址转换模式。虚拟系统可以和外部系统通讯，不造成IP冲突。](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t2)

[1.3 主机模式：独立的系统。](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t3)

[2.虚拟机克隆](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t4)

[3.虚拟机快照](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t5)

[4.虚拟机的迁移和删除](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t6)

[5.安装vmtools](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t7)

[5.1 安装步骤](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t8)

[打开一个终端](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t9)

[进入opt目录：cd/opt](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#%E8%BF%9B%E5%85%A5opt%E7%9B%AE%E5%BD%95%EF%BC%9Acd%2Fopt)

[解压文件：tar -zxvf VM【文件名】：tab键补全](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#%E8%A7%A3%E5%8E%8B%E6%96%87%E4%BB%B6%EF%BC%9Atar%20-zxvf%20VM%E3%80%90%E6%96%87%E4%BB%B6%E5%90%8D%E3%80%91%EF%BC%9Atab%E9%94%AE%E8%A1%A5%E5%85%A8)

[进入该vm解压的目录，/opt目录下](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#%E8%BF%9B%E5%85%A5%E8%AF%A5vm%E8%A7%A3%E5%8E%8B%E7%9A%84%E7%9B%AE%E5%BD%95%EF%BC%8C%2Fopt%E7%9B%AE%E5%BD%95%E4%B8%8B)

[5.2 共享文件夹](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t10)

[5.Linux的目录结构](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t11)

[5.1 基本介绍](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t12)

[5\. 2 具体的目录结构](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t13)

[6.远程登录到服务器](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t14)

[6.1 为什么](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t15)

[6.2 远程登录--Xshell](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t16)

[6.3 文件上传下载--Xftp](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t17)

[出现乱码](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t18)

[7.Vi和Vim编辑器](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t19)

[7.1 基本介绍](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t20)

[7.2 三种模式](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t21)

[7.3 vi和vim各种模式的切换](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t22)

[拷贝当前行，拷贝n行：yy / nyy](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t23)

[删除当前行，删除n行 :dd/ ndd](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t24)

[8.开机和重启](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t25)

[9\. 登陆和注销](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t26)

[10.用户管理](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t27)

[10.1 添加用户：useradd 用户名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t28)

[指定路径设置用户：](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t29)

[指定/修改密码：passwd 用户名/passwd](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t30)

[10.2 删除用户：userdel 用户名/userdel -r 用户名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t31)

[10.3 查询用户信息：id 用户名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t32)

[10.4 切换用户 ：su - 切换用户名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t33)

[10.5 查看当前用户/登录用户：who am i/whomi](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t34)

[10.6 用户组](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t35)

[1.新增组：groupadd 用户组名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t36)

[2.删除组:groupdel 用户组名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t37)

[3.增加用户时直接加上组：useradd -g 用户组 用户名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t38)

[4.修改用户的组：usermod -g 用户组 用户名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t39)

[5.用户和组相关文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t40)

[11.运行级别](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t41)

[11.1 基本](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t42)

[11.2 指定运行级别](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t43)

[12.找回root密码](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t44)

[13.帮助指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t45)

[1\. man 获得帮助信息](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t46)

[2.help指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t47)

[3.总结](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t48)

[14.文件目录指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t49)

[1.pwd:显示当前工作的绝对路径](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t50)

[2.ls：显示当前目录所有的文件和目录，包括隐藏](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t51)

[3.cd：切换到指定目录【可以指定绝对路径或者相对路径】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t52)

[cd ~:回到家目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t53)

[编辑](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t54)

[cd ..:回到当前目录的上一级目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t55)

[4.mkdir指令：创建目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t56)

[创建一个目录：mkdir /home/dog](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t57)

[创建多级目录：mkdir -p /home/animal/tiger](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t58)

[5.rmdir:删除空目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t59)

[删除空目录：rmdir /home/dog](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t60)

[删除非空目录：rm -rf /home/animal/tiger](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t61)

[6.touch指令：创建空文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t62)

[创建一个空文件：touch hello.txt](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t63)

[7.cp指令：拷贝文件到指定目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t64)

[将/home/hello.txt拷贝到/home/bbb目录下：cp hello.txt bbb/](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t65)

[递归复制整个文件夹：将/home/bbb整个目录，拷贝到/opt:cp -r  /home/bbb /opt](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t66)

[强制覆盖不提示：\\cp -r /home/bbb /opt](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t67)

[8.rm指令：移除文件或目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t68)

[删除一个文件/目录：rm /home/hello.txt](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t69)

[删除整个文件夹【不提醒】：rm -rf /home/hello.txt](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t70)

[9.mv指令：移动文件与目录或者重命名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t71)

[重命名：mv oldNameFile newNameFile](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t72)

[移动文件：mv /temp/movefile /targetFoloder](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t73) 

[10.cat指令：查看文件内容](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t74)

[11.more指令：要查看的文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t75)

[12.less指令：分屏查看文件内容](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t76)

[13.echo指令：输出内容到控制台](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t77)

[14.head指令:显示文件的开头部分内容](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t78)

[查看文件头10行内容:head 文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t79)

[查看文件头5行内容：head -n 5 文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t80)

[15.tail指令：输出文件中尾部的内容](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t81)

[19.“>”指令：表示将原来文件内容进行覆盖](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t82)

[列表的内容写入文件a.txt中（覆盖写）：ls -l > 文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t83)

[20.">>"指令：将原来文件内容进行追加](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t84)

[列表的内容追加到文件aa.txt末尾：ls -al >> 文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t85)

[将文件1的内容覆盖到文件2：cat 文件1 >> 文件2](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t86)

[追加：echo "内容” >> 文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t87)

[21.ln指令：软连接，主要存放了链接其他文件的路径](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t88)

[22.history指令：查看已经执行的历史命令，也可以执行历史指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t89)

[15.时间日期类](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t90)

[1.date指令:显示当前日期](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t91)

[2.date指令：设置日期](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t92)

[设置时间:date -s 字符串时间](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t93)

[3.cal指令：查看日历](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t94)

[查看某年日历：cal 2022](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t95)

[16.搜索查找类](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t96)

[1.find指令：从指定目录向下递归地遍历其各个子目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t97)

[2.locate指令：快速定位文件路径](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t98)

[3.which指令：查看某一个指令在哪一个目录下](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t99)

[4.grep指令和管道指令：|](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t100)

[17.解压和压缩类](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t101)

[1.gzip/gunzip指令:gzip:压缩文件，gunzip解压文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t102)

[2.zip/unzip指令：zip压缩文件夹，unzip解压文件夹【打包】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t103)

[压缩文件夹;zip 要压缩到的地方.zip 要进行压缩的地方](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t104)

[解压文件夹：unzip 要解压到的地方 要解压的地方.zip](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t105)

[3.tar指令：打包指令。最后打包的文件是.tar.gz文件](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t106)

[压缩多个文件，将/home/pig.txt 和/ home/cat.txt压缩为pc.tar.gz](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t107)

[将/home的文件夹压缩为myhome.tar.gz](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t108)

[将pc.tar.gz解压到当前目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t109)

[将myhome.tar.gz 解压到/opt/tmp2目录下【-C 切换到指定目录】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t110)

[18.Linux组管理](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t111)

[1.基本介绍](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t112)

[2.所有者](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t113)

[2.1 查看文件所有者;ls -ahl](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t114)

[2.2 修改文件所有者：chown 用户名 文件名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t115)

[3.所在组](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t116)

[3.1 组的创建：groupadd 组名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t117)

[3.2 查看文件/目录所在组：ls -ahl](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t118)

[3.3 修改文件所在的组：chgrp 组名 文件名](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t119)

[4.其他组](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t120)

[4.1 改变用户所在组](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t121)

[5.权限的基本介绍](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t122)

[6.rwx权限](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t123)

[对于目录来说：](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t124)

[案例说明：](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t125)

[7.修改权限-chmod](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t126)

[方式一：o+w【给other赋予write权限】 a-x【给all去除execute】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t127)

[方式二：通过数字变更权限【r=4 w=2 x=1】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t128)

 [8.修改文件所有者-chown](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t129)

[9.修改文件所在组-chgrp](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t130)

[10.权限管理案例：](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t131)

[19.定时任务调度](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t132)

[1.crond任务调度：crontab -e【周而复始执行】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t133)

[2.crond特殊符号](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t134)

[3.crond特殊时间执行任务](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t135)

[4.crond应用实例](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t136)

[5.crond相关指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t137)

[6.at定时任务:at【选项】【时间】：对每一个作业60秒执行一次](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t138)

[命令选项](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t139)

[时间定义](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t140)

[7.at任务调度实例：](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t141)

[20.磁盘分区](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t142)

[1.基本介绍](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t143)

[2.硬盘分区说明：](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t144)

[3.查看所有设备挂载情况：lsblk【list block】 或者 lsblk -f](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t145)

[4.增加硬盘应用实例](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t146)

[1.挂载硬盘【记得重启】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t147)

[2.在硬盘中创建分区：fdisk /dev/sdb](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t148)

[3.格式化硬盘：mkfs -t ext4 /dev/sdb1](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t149)

[4.挂载mount：mount /dev/sdb1 /newdisk](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t150)

[5.取消挂载unmount](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t151)

[6.自动挂载【永久挂载】：/etc/fstab](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t152)

[5.磁盘情况查询：df -h](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t153)

[6.查询指定目录的磁盘占用情况：du -ha /目录](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t154)

[7.磁盘工作实用指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t155)

[21.网络配置](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t156)

[1.Linux网络配置原理图【NAT网络配置】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t157)

[2.网络配置指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t158)

[查看window环境中的VMnet8网络配置--ipconfig](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t159)

[查看linux的网络配置---ifconfig](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t160)

[ping测试主机之间网络连通性](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t161)

[3.linux网络环境配置](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t162)

[方法一：自动获取](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t163)

[方法二：指定ip](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t164)

[3.设置主机名和hosts映射](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t165)

[a. 设置主机名--vim /etc/hostname](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t166)

[b. 设置hosts映射--vim /etc/hosts](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t167)

[4.主机名解析过程分析（Hosts,DNS)](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t168)

[1.Hosts是什么](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t169)

[2.DNS：分布式数据库](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t170)

[3.图示](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t171)

[22.Linux进程管理](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t172)

[1.基本介绍](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t173)

[2.显示系统指向的进程--ps -aux | more/ ps -ef【全格式显示】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t174)

[3.应用](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t175)

[4.终止进程kill和killall](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t176)

[5.查看进程数pstree](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t177)

[6.服务（service)的管理命令【本质-进程】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t178)

[查看服务名：setup](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t179)

[7.服务的运行级别：7个级别](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t180)

[开机流程](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t181)

[运行级别的修改](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t182)

[8.服务（chkconfig指令）：chkconfig --level3 network off\[on\]](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t183)

[9.服务管理systemctl管理指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t184)

[10.服务管理fillwall指令--打开或者关闭指定端口](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t185)

[11.动态监控进程:top【与ps相似】](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t186)

[12.动态监控进程交换操作](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t187)

[13.监控网络状态：netstat -anp | more xx](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t188)

[23.RPM和YUM](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t189)

[1.rmp包管理](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t190)

[2.rmp查询指令---rpm -qa | grep xxx](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t191)

[3.rmp包名基本格式](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t192)

[4.rmp其他查询指令](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t193)

[5.rpm卸载:rpm -e xxx](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t194)

[6.rpm安装：rpm -ivh RPM包全路径名称](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t195)

[7.yum【基于RPM】：yum install xxx](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t196)

[24.搭建JavaEE环境](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t197)

[1.安装配置JDK1.8](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t198)

[1.mkdir /opt/jdk](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t199)

[2.cd /opt/jdk](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t200)

[3.解压：tar -zxvf jdk-.zip](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t201)

[4.创建一个文件夹进行存放:/usr/local/java/jdk](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t202)

[5.配置环境变量的配置文件：vim /etc/profile](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t203)

[6.让新的环境变量生效：source /etc/profile](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t204)

[2.安装tomcat](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t205)

[1.创建目录：mkdir /opt/tomcat](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t206)

[2解压：tar -zxvf -tomcat](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t207)

[3.安装：startup](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t208)

[4.打开防火墙中预防的8080](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t209)

[5.重载一下：firewall-cmd --reload](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522172257936116800184168400%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=%E9%9F%A9%E9%A1%BA%E5%B9%B3linux%E7%AC%94%E8%AE%B0&spm=1018.2226.3001.4187#t210)

* * *

## 1.[网络连接](https://so.csdn.net/so/search?q=%E7%BD%91%E7%BB%9C%E8%BF%9E%E6%8E%A5&spm=1001.2101.3001.7020)三种方式

#### 1.1 [桥接模式](https://so.csdn.net/so/search?q=%E6%A1%A5%E6%8E%A5%E6%A8%A1%E5%BC%8F&spm=1001.2101.3001.7020)：虚拟系统可以和外部系统通讯，但是容易造成IP冲突【1-225】

![](image/af41442ffec07e44166a0cb2ec735a45.png)

#### 1.2 NAT模式：[网络地址转换](https://so.csdn.net/so/search?q=%E7%BD%91%E7%BB%9C%E5%9C%B0%E5%9D%80%E8%BD%AC%E6%8D%A2&spm=1001.2101.3001.7020)模式。虚拟系统可以和外部系统通讯，不造成IP冲突。

![](image/9d201d44cbdf52bffaa0245bcfc23372.png)

#### 1.3 主机模式：独立的系统。

## 2.虚拟机克隆

![](image/54de034d0994ead0caacbe433933a10e.png)

## 3.虚拟机快照

![](image/b3dafada3d9bed98e284a076d3068a3e.png)

![](image/d74392c3da1a5768e14c963f958128a6.png)

![](image/3e1f6b53061cd6e7d2c458ef364d0cfb.png)

![](image/316b058942ed549f0777e86c90b9f74e.png)

![](image/e47c775edc9b47926464ad7cfa327f7e.png)

## 4.虚拟机的迁移和删除

剪切或者删除

![](image/4e0fc43dc33cabec396defc3b7b4a7cc.png)

## 5.安装vmtools

> **可以设置windows和centos的共享文件夹**

![](image/0f67cb808432779671b2d3b21e835983.png)

### 5.1 安装步骤

![](image/0f12cd8f24ba0fb02839f296d3166726.png)

> 重新安装为灰色，可能是已经安装好了。可以试试从windows桌面拉到虚拟机桌面上一个文件，如果可以，证明已经安装好了，可以直接用就好了

**如果无法出现“安装VM tool”则将虚拟器重启** 

![](image/22d1a34de0ccec3e177a93361f5d2eed.png)

![](image/32a13d47abe121f21e6539b77533ba9c.png)

![](image/be0ae8ba38751bb590e729219c8eeba7.png)

![](image/68aa8d1b49ab3830369b9066706ecfc9.png)

![](image/f9c84e7e662c21dc267343a5b062b3b8.png)

![](image/4be377d6c21ed1f89de49c32db5fd460.png)

#### 打开一个终端

##### 进入opt目录：cd/opt

![](image/6e41f673f4cfe482f58a306b04a5ab0c.png)

##### 解压文件：tar -zxvf VM【文件名】：tab键补全

> tar -zxvf VMwareTools-10.3.23-16594550.tar.gz 

![](image/9129bdf20cef35f77fcfaf934fedf246.png)

##### 进入该vm解压的目录，/opt目录下

> cd vmware-tools-distrib/

![](image/c65e0f55bab4c6d1edf26cc31d0137a6.png)

![](image/ec72ec72d3e25fb07b389a87b26fe68e.png)

安装

> ./vmware-install.pl 

![](image/948e3b773a676a9699121067b8b08380.png)

### 5.2 共享文件夹

![](image/3b56a8beb5e116662cd0c1b18cb25c71.png)

先在主机上新建一个文件夹

![](image/a73939084f50436e2b34b415c0352339.png)

在虚拟机上选择“设置”

![](image/265ff8ea444419c200f35e443e2a75a5.png)

在虚拟机上查看主机上的文件

![](image/a49a74b26a5d600ec4be95714ac94599.png)

![](image/201bb0f140c0430c87113e04c6e1add7.png)

![](image/5509100698ed13871ac1141a840e3fba.png)

![](image/b450575185b67c1733a3595628d5c99d.png)

## 5.Linux的目录结构

### 5.1 基本介绍

![](image/3f11fc25c4b306e9f80ebde33fa1a343.png)

> 把硬件当作一个文件来看

![](image/2e731f5818e5fb66194b19131b943d06.png)

### 5\. 2 具体的目录结构

![](image/6acc0508b5269f837029017477e1bdb8.png)

![](image/aa88061ae55c8e9ee784bf894006a845.png)

![](image/6da7be8fe4db569d9b020fa74bd9625d.png)

> opt是安装包目录【安装包】，usrlocal是程序安装目录【APP】

![](image/8b3d42ef8614539d24a2459447bf07aa.png)

## 6.远程登录到服务器

### 6.1 为什么

![](image/ebbe5ce0c2c3fd4997b6c024eba42b4b.png)

![](image/32ba26346f0bb52cb28d4ca95e4e3b3f.png)

### 6.2 远程登录--Xshell

[阿里云盘分享 (aliyundrive.com)](https://www.aliyundrive.com/s/5KDWaC5kwSx "阿里云盘分享 (aliyundrive.com)")

![](image/7e7468099c2e5f56f8829d5376dae71f.png)

 ![](image/a4446a8d8f7ab25cad14cd14dad84b03.png)

![](image/8c69bed9d80059a40bc8c205dd07e942.png)

 ![](image/4130f2b25364ac195313040de234da6c.png)

![](image/b50ec817cb2384461a9401df9a48960f.png)

### 6.3 文件上传下载--Xftp

![](image/89e9294bce04b04de7e68d90686c83be.png)

![](image/1853ffd139a28d96dd68a55afb2c7e4b.png)

![](image/56ccd3644ee33cd4f1fc78a14ce8ac60.png)

#### 出现乱码

![](image/212a52b74cfe2182d68fd41edee5ab7d.png)

![](image/8fa6862979702d8ac9501ee0112060c1.png)

![](image/8034d468a3b21ed31f400526ad307d29.png)

## 7.Vi和Vim编辑器

### 7.1 基本介绍

> vi：相当于windows中的文本编辑器
>
> vim：vi max

![](image/7652c3ac5a052be760ef673b66f47b00.png)

### 7.2 三种模式

![](image/e1c9cc87ac0ed4b23122c5b48793ce34.png)

> **使用“i”进入编辑模式**
>
> ![](image/6a7587ac29c9815a2001e5a3305ada5b.png)
>
> **进入命令行：先“esc”在“：”，最后“输入wq“**
>
> ![](image/6f367d16920665b7d72338066d750807.png)

### 7.3 vi和vim各种模式的切换

![](image/29d990054b9dbcae7ce864abd715d519.png)

#### 拷贝当前行，拷贝n行：yy / nyy

![](image/6094b7d34ac0a8afc0eb1fb96c3cdec0.png)

#### 删除当前行，删除n行 :dd/ ndd

在文件中查找某一个单词【命令行下/关键字】，回车查找，输入n就是查找下一个

设置文件的行号，取消文件的行号：【命令行下：set nu 和 set nonu】

![](image/8a35df7cbfc578bf812f3f8a3482426f.png)

## 8.开机和重启

![](image/d49e5ed32b67e5bc2d8fc33198f4e4b4.png)

## 9\. 登陆和注销

#### 从普通用户切换到root用户：su 

    [tom@xiaolin ~]$ su密码：[root@xiaolin tom]# 

![](image/bb737aae9b7fc5b00ce672d22162907e.png)

#### 从管理员到普通用户:su tom

    [root@xiaolin tom]# su tom[tom@xiaolin ~]$ 

![](image/87b56097606824e9b1ab932272466abe.png)

![](image/46f519c67ba4825cde70c8ff08155b62.png)

#### 注销登录

> 1.$ logout
>
> 2\. $ exit
>
> 3.ctrl+d

## 10.用户管理

![](image/9ed9882f97506c1d5ecaec62354f35ca.png)

![](image/f575775bd9a6d781b4d14037748c6642.png)

### 10.1 添加用户：useradd 用户名

![](image/2645687eb3e1667569e5224d913bd8f4.png)

![](image/5b13711815e382748bea8b0d1383c8e6.png)

#### 指定路径设置用户：

> 指定目录下创建：**useradd -d 指定目录 新用户名**

![](image/a888141629f1dd8870690ce3bf6629b8.png)

![](image/674b5fb63039a736f476d1f1cbb4dbde.png)

#### 指定/修改密码：passwd 用户名/passwd

> 如果没有指定用户名，表示对当前登录的账号进行修改
>
> **如果用户无法修改密码，则让root修改**

![](image/ca6c13c7ce15cdf9e689aebfdf979264.png)

![](image/971228909582d7c0ec52629a72d12b96.png)

> **显示当前用户所在的目录：pwd**

### 10.2 删除用户：userdel 用户名/userdel -r 用户名

> **删除用户只能在root登录状态下进删除。**
>
> **删除该用户后，其家目录还在，但是无法登录**
>
> ![](image/24f3bc8737e4284e8e25c8689b5f4b13.png)

删除用户milan，但是要保留家目录

    userdel milan

删除用户以及用户主目录

    userdel -r tom

![](image/c3f40bd1176475ebdd52cdaddbc00cdc.png)

### 10.3 查询用户信息：id 用户名

    id tom

![](image/f3799cdf43b5361f2bcd60691ac46ae3.png)

### 10.4 切换用户 ：su - 切换用户名

    su - tom # 从root到tomsu # 从普通用户到root

![](image/50d36c3c7e522ba3b85633797e981aaa.png)

    返回原来的用户logout或者exit

### 10.5 查看当前用户/登录用户：who am i/whomi

> 注意点：
>
> **查看的是当前最开始登录的用户**。如果是以root登录进来，无论切换多少用户，结果都是root

![](image/b51ff7ded52155cfa31a586647dfe3e6.png)

### 10.6 用户组

> 系统可以对有共性/权限的多个用户进行统一的管理

#### 1.新增组：groupadd 用户组名

    groupadd wudang

> 添加成功，则下面不会显示任何东西

![](image/0f852e8727207b42a8805d057f2dab38.png)

#### 2.删除组:groupdel 用户组名

    groupdel wudang

![](image/3d8b8c920c1a8e7613a0052e66d4b934.png)

#### 3.增加用户时直接加上组：useradd -g 用户组 用户名

> 新增一个用户时，如果没有指定，则直接新增一个组和该用户名一致

![](image/61c8c78218872d8505f91ce9cc0d2644.png)

    groupadd wudang//新增一个用户组useradd -g wudang zwj

![](image/f888e8ba4f5b73f93471f636f5cb2da9.png)

#### 4.修改用户的组：usermod -g 用户组 用户名

![](image/5721bb738c1125058a4bc129670b81f5.png)

![](image/2e0340f18eb943cdb71f9443afc55391.png)

    [root@hspEd01 ~]# groupadd wudang[root@hspEd01 ~]# useradd -g wudang zwj[root@hspEd01 ~]# id zwjuid=1004(zwj) gid=1004(wudang) 组=1004(wudang)[root@hspEd01 ~]# groupadd mojiao[root@hspEd01 ~]# usermod -g mojiao zwj[root@hspEd01 ~]# id zwjuid=1004(zwj) gid=1005(mojiao) 组=1005(mojiao)

#### 5.用户和组相关文件

Shell

![](image/584ddad16bceb3254e3bd4bfe2ff821b.png)

![](image/081bfc4b6997073d36f29238cefa3751.png)

### 7.查询用户历史登录信息

> $last
>
> $last -5:查询最后5条
>
> $last jsj
>
> $last -5 jsj

## 11.运行级别

### 11.1 基本

> **1.从图像转换到文本：ctrl+alt+f3**
>
> **2.从文本到图像：ctrl+alt+f1**

![](image/b334d04aa252c3606f025140b7794c39.png)

### 11.2 指定运行级别

![](image/033ff2f7d89aa437f89e070ec1129f08.png)

## 12.找回root密码

1.启动系统，进入开机界面，在界面中按“e”进入编辑界面

![](image/d21703cf14e4b7d10b23a541538d08d3.png)

2.进入编辑界面，使用键盘上的上下键把光标往下移动，找到“Linux16"开头所在的行数

在最后输入：init=/bin/sh

![](image/12a0dfca04afdf44ddada13a7213f189.png)

3.输入完成后，直接按快捷键：Ctrl+x 进入单用户模式

4.接着，在光标闪烁的位置输入：mount -o remount,rw/ (注意：各个单词之间有空格),完成后按键盘间的回车。如图

![](image/c60de70cdb980e3d73f02ed35b96215a.png)

 5.在新的一行最后面输入：passwd,完成后按键盘的回车键。输入密码，然后再次确认密码即可（密码最好是8位以上，但不是必须的），密码修改完成后，会电视passwd.....的样式，说明密码修改成功

![](image/f1382dd6e2780941b41acd4d5b752887.png)

 6.接着，在鼠标闪烁的位置，输入：touch / .autorelabel（注意：touch与 /后面有一个空格），完成后按键盘的回车键

7.继续在光标闪烁的位置中，输入：exec/sbin/init（注意：exec与/之间有一个空格），完成后按键盘的回车键，等待系统自动修改密码（时间可能有点长），完成后，系统会自动重启，新的密码生效。

![](image/3469b5c02dcf8f0d058368433a739502.png)

## 13.帮助指令

### 1\. man 获得帮助信息

> **使用“q”退出**

![](image/9b615f7fcbdef31b3d0025b40c6cc976.png)

    //查看root目录下的所有文件，并且以单例的形式展示ls -al/root

![](image/9a4c4225ccf4ac12552b0b7ccae9a67a.png)

### 2.help指令

![](image/3a292946c8e65dad1a2bd7fb4f1f4ab0.png)

### 3.ls/ll:查看当前目录信息

> ls -l【list】:查看详细信息
>
> ls -h【human】：显示大小单位
>
> ls -a【all】：全部展示--包含隐藏文件

### 4.总结

![](image/d45e1e3209393e340d0c11b0e48172eb.png)

## 14.文件目录指令

### 家目录：

![](image/db711f37fc78b7e707b5eaf80d01af1b.png)

> 管理员的主目录：/root
>
> 普通用户的主目录：/home/tom

### 命令格式

> command \[options\]\[arguments\]
>
> 命令【--选项】【参数】

    suls -lls -l /home

### 1.pwd:显示当前工作的绝对路径

![](image/2569430bb859c192ef59702e6357bac5.png)

![](image/78a6cd863b50d353bb30df0ab3231ed5.png)

    [root@hspEd01 ~]# cd /home/[root@hspEd01 home]# lsjack  milan  test  tom  zwj[root@hspEd01 home]# cd tom[root@hspEd01 tom]# vim a.txt[root@hspEd01 tom]# lsa.txt[root@hspEd01 tom]# pwd/home/tom

### 2.ls：显示当前目录所有的文件和目录，包括隐藏

![](image/feee3f25a4c1a5e217c94107c514d8a6.png)

### 3.cd：切换到指定目录【可以指定绝对路径或者相对路径】

#### cd ~:回到家目录

> 【如果是root，则返回/root】
>
> **【如果是tom，则返回/home/tom】**
>
> **如果未指定路径，默认到家路径下**

#### ![](image/41ec76ac2973d957d80882b045fa133c.png)

#### cd ..:回到当前目录的上一级目录

![](image/c44c930cf223d98767888c900c120e53.png)

![](image/ff7f6823a2b22647b31a66e4ecbb03e1.png)

### 4.mkdir指令：创建目录

#### 创建一个目录：mkdir /home/dog

#### 创建多级目录：mkdir -p /home/animal/tiger

![](image/b81df7e8eec3ab1b4365d0cf0e11cd10.png)

![](image/a3b6c3de76c6e25b31f097af7b9cb392.png)

![](image/e7d150943fb369194562ae264392beca.png)

### 5.rmdir:删除空目录

#### 删除空目录：rmdir /home/dog

#### 删除非空目录：rm -rf /home/animal/tiger

![](image/13ac07851daa72a85a4f21d99ff78a2b.png)

### 6.touch指令：创建空文件

#### 创建一个空文件：touch hello.txt

![](image/612e26f6a58389f329d9a338bb77a987.png)

### 7.cp指令：拷贝文件到指定目录

#### 将/home/hello.txt拷贝到/home/bbb目录下：cp hello.txt bbb/

![](image/28a6cd049c3ad5aaf25aa348031cffeb.png)

    [root@hspEd01 home]# mkdir bbb[root@hspEd01 home]# lsanimal  bbb  hello.txt  jack  milan  test  tom  zwj[root@hspEd01 home]# cp hello.txt bbb/[root@hspEd01 home]# cd bbb/[root@hspEd01 bbb]# lshello.txt

![](image/528a29bf0daae9a73c79f3af585e7891.png)

#### 递归复制整个文件夹：将/home/bbb整个目录，拷贝到/opt:cp -r  /home/bbb /opt

![](image/ef95e93cc3be79d0de9d950bafd8014e.png)

    [root@hspEd01 bbb]# lshello2.txt  hello.txt[root@hspEd01 bbb]# cp -r /home/bbb /opt/[root@hspEd01 bbb]# cd /opt/[root@hspEd01 opt]# lsbbb  rh  VMwareTools-10.3.23-16594550.tar.gz  vmware-tools-distrib

> 如果再一次执行”cp -r  /home/bbb /opt“，表示将前面的进行覆盖

#### 强制覆盖不提示：**\\cp** -r /home/bbb /opt

![](image/7f6318a8d348cb0ea532de30cc3b18e5.png)

### 8.rm指令：移除文件或目录

#### 删除一个文件/目录：rm /home/hello.txt

#### 删除整个文件夹【不提醒】：rm -rf /home/hello.txt

![](image/35d22124bce974d96f41cbd3a3a089fd.png)

### 9.mv指令：移动文件与目录或者重命名

#### 重命名：mv oldNameFile newNameFile

#### 移动文件：mv /temp/movefile /targetFoloder 

![](image/c20afa1b630c681326da6c51ecdc2384.png)

### 10.cat指令：查看文件内容

**将结果交给下一个指令：cat -n /etc/profile | more**

**【按“Enter”表示显示下一行，“空格”表示翻一页】**

  ![](image/7c19f0bc3de69fa960920ab1d1baef68.png)

### 11.more指令：要查看的文件

> **more可以根其他一起使用，也可以自己使用。**

![](image/c50fc331a71a72fd6facad7bb85e93d7.png)

### 12.less指令：分屏查看文件内容

> **根据显示需要加载内容，对应显示大型文件具有较高效率**

![](image/849cf5684a6ccf67918654231bbc79ec.png)

### 13.echo指令：输出内容到控制台

![](image/ec14b777bdd5bf95fe1ceb157afcd73f.png)

### 14.head指令:显示文件的开头部分内容

#### 查看文件头10行内容:head 文件

#### 查看文件头5行内容：head -n 5 文件

![](image/752495c099fb1bebce199f6242a70e5e.png)

### 15.tail指令：输出文件中尾部的内容

![](image/8a0ff8126cd7b1941590b0b7576b0d75.png)

### 19.“>”指令：表示将原来文件内容进行覆盖

#### 列表的内容写入文件a.txt中（覆盖写）：ls -l > 文件

![](image/34c7667c3db25dcdd8f5943e4ee2e843.png)

### 20.">>"指令：将原来文件内容进行追加

#### 列表的内容追加到文件aa.txt末尾：ls -al >> 文件

#### 将文件1的内容覆盖到文件2：cat 文件1 >> 文件2

#### 追加：echo "内容” >> 文件

![](image/9a4934f0dc94d9d29099656eaa4d4236.png)

![](image/c7b3bfb022ad1c1a638bb624e5148a2c.png)

![](image/faf947354b5ade6251e90e4f08fcbd7c.png)

### 21.ln指令：软连接，主要存放了链接其他文件的路径

![](image/1294f14b2203f217bf15fec2447b9c12.png)

> ln -s /root /home/myroot  
> 相当于复制root，**点击myroot实际上跳转到/root下**

![](image/114bb8cf2a3047c65d590caccf90f652.png)

### 22.history指令：查看已经执行的历史命令，也可以执行历史指令

![](image/da50ca0587fd3b28f75e646c72511f33.png)

## 15.时间日期类

### 1.date指令:显示当前日期

![](image/cc3c2e38785999fa4b605fc5ba9fefe3.png)

### 2.date指令：设置日期

#### 设置时间:date -s 字符串时间

![](image/df5fcd38429f302f3886d6385f5fb923.png)

### 3.cal指令：查看日历

#### 查看某年日历：cal 2022

![](image/d6feb589ba419bdca31750d846b2f7a0.png)

## 16.搜索查找类

### 1.find指令：从指定目录向下递归地遍历其各个子目录

![](image/2f39107d17b8ce5c4bbe1d99aa3d7538.png)

### 2.locate指令：快速定位文件路径

> **因为locate有自己的查找数据库，所以速度快。但是我们第一次执行时，要先更新数据库**
>
> **updatedb**

![](image/24e228c64710ca824f36f07dd727b1c9.png)

![](image/d50f4bb0b551704a702009f93b052b4f.png)

![](image/c45ff010c225947ba2f0bbf604ae87d1.png)

### 3.which指令：查看某一个指令在哪一个目录下

![](image/1ab93dbf0cfa5a2a7ec6a178e2609bdc.png)

### 4.grep指令和管道指令：|

![](image/09fcb1ed07e304024fd9043f1cb37266.png)

![](image/cc1e35b8664709b6459ae48edde2b43f.png)

## 17.解压和压缩类

### 1.gzip/gunzip指令:gzip:压缩文件，gunzip解压文件

![](image/aba9cb88e33778825bf87f4ed207c6bb.png)

### 2.zip/unzip指令：zip压缩文件夹，unzip解压文件夹【打包】

![](image/50bf1666f15ae3d0cc725e42ba474621.png)

#### 压缩文件夹;zip 要压缩到的地方.zip 要进行压缩的地方

#### 解压文件夹：unzip 要解压到的地方 要解压的地方.zip

![](image/21198484c8f58b0ffeda8f7b87e13127.png)

### 3.tar指令：打包指令。最后打包的文件是.tar.gz文件

> 可以打包压缩文件或者文件夹

![](image/514f2fe5cebdc96578185d758cec768d.png)

#### 压缩多个文件，将/home/pig.txt 和/ home/cat.txt压缩为pc.tar.gz

> tar -zcvf pc.tar.gz /home/pig.txt /home/cat.txt

#### 将/home的文件夹压缩为myhome.tar.gz

> tar -zcvf myhome.tar.gz /home

#### 将pc.tar.gz解压到当前目录

> tar -zcvf pc.tar.gz

#### 将myhome.tar.gz 解压到/opt/tmp2目录下【-C 切换到指定目录】

> mkdir /opt/tmp2
>
> tar -zxvf /home/myhome.tar.gz -C /opt/tmp2 

## 18.Linux组管理

### alias命令：起别名

    alias【别名='标准命令'】 alias ch='cd/home/hong'//起别名

> **alia la='ls -a'**

    //取消别名unalias ch;

### 1.基本介绍

![](image/36d433af4d602d4dcc254ea612d36fe9.png)

![](image/7f7be6c5ef38cb53960b21f8de019a89.png)

### 2.所有者

![](image/4ad59d554913b868f29ce2b05567a2ca.png)

#### 2.1 查看文件所有者;ls -ahl

> a隐藏 h可视化大小 l 列显示

![](image/098f0bbd19a2cdc40e38ecd566aff848.png)

#### 2.2 修改文件所有者：chown 用户名 文件名

> chown:change own

![](image/aa4aaf71225a7b5c065d2c1d8c4af807.png)

### 3.所在组

#### 3.1 组的创建：groupadd 组名

![](image/26780178f164beba9612de21c2fa2ff1.png)

#### 3.2 查看文件/目录所在组：ls -ahl

![](image/8524713ffcaac31e326e59c5e882eac3.png)

#### 3.3 修改文件所在的组：chgrp 组名 文件名

![](image/c167d2ad7e2451bad1b3679f3530154b.png)

### 4.其他组

除去文件的所有者和所在组的有户外，系统的其他用户都是文件的其他组

#### 4.1 改变用户所在组

![](image/2158f3d1f55dcf8f82bbada8339e8a48.png)

### 5.权限的基本介绍

> I链接、d文件夹、c设备、b块

![](image/62ecc883d5a91d3867a09b9ec7f0de1f.png)

### 6.rwx权限

![](image/c96f6e27c7ccdf20e63903785175176c.png)

> #### 对于目录来说：
>
> x:表示可以进入该目录，比如cd
>
> r:表示可以ls，将目录的内容显示
>
> w：表示可以在该目录，**删除或者创建文件**

#### 案例说明：

![](image/1a810250c6cd3aa21ae1a037029ea019.png)

### 7.修改权限-chmod

> 通过chmod指令，可以修改文件或者目录的权限

#### 方式一：o+w【给other赋予write权限】 a-x【给all去除execute】

![](image/413ac09a76ccf96679fe29021a63fae7.png)

#### 方式二：通过数字变更权限【r=4 w=2 x=1】

![](image/045fc46f961333a13ff783790ebdc545.png)

###  8.修改文件所有者-chown

![](image/52bdf816f6134b2a652866c7055b0fb1.png)

### 9.修改文件所在组-chgrp

![](image/719fe3674c6f4c8b3e4f8e03c7e744d5.png)

### 10.权限管理案例：

![](image/75ff7c608e7000b0fcf477579f740841.png)

![](image/d0a9dd4a1b438c578c8b1356818fbc00.png)

* * *

* * *

![](image/d1aa2d9eadf805218956b4480e7bf30a.png)

## 19.定时任务调度

### 1.crond任务调度：crontab -e【周而复始执行】

![](image/dbcb6baf62c53904b0da09226142ae19.png)

![](image/174244792f0e40ef343e333fd9e078ef.png)

![](image/c099abb17a4d91a189aa9aabe2e0d751.png)

![](image/4b94c3bbe2378069cfaaa283e256403e.png)

### 2.crond特殊符号

![](image/e6cccbc8bad6952e8af34efacab0cc58.png)

### 3.crond特殊时间执行任务

![](image/57bfb68d13f58677f83bb26263713355.png)

### 4.crond应用实例

![](image/c283b7bdf28f5a00d67f38aa705486f7.png)

![](image/c4e6a131232105a7317475a4822d1595.png)

### 5.crond相关指令

![](image/0d3d8cdd5745717ed99515b82da0246f.png)

### 6.at定时任务:at【选项】【时间】：对每一个作业60秒执行一次

![](image/37c92ec07ce1de4da297d68d88684f8d.png)

![](image/1c6267a1552830580e7d4a546f8f85be.png)

#### 命令选项

![](image/b9f1cbf33d4b478731e82a75c60e56ff.png)

#### 时间定义

![](image/e9aa35f05ec33c47e30866c61d418554.png)

### 7.at任务调度实例：

![](image/ea0a27516ff419cd2e73f3c004633fa5.png)

## 20.磁盘分区

### 1.基本介绍

> 块设备：dev

![](image/6288ea7b41097e30af657af0d1d88b82.png)

![](image/3f5d68c071b41b74afb4b673167f51af.png)

![](image/e0d8bf331aef2ca820ec56b7658d8df1.png)

### 2.硬盘分区说明：

> sda：sd表示磁盘类型
>
> 绝对路径：/dev/sda

![](image/ed407c1281108fdfa1b08b7fa0b25483.png)

![](image/ca1225d065544b0859ae96d393ef0206.png)

### 3.查看所有设备挂载情况：lsblk【list block】 或者 lsblk -f

![](image/42c2652c2d5137608cb7dbd1a1c8428f.png)

### 4.增加硬盘应用实例

![](image/5ab9f07fd926f9ffc0bcfaa7b3641386.png)

#### 1.挂载硬盘【记得重启】

![](image/1a6825264a11dc9726db0ae58849c00e.png)

![](image/0286d3cbe0f91f67a83e4d3d9313fd8e.png)

![](image/8ffc8b38d5db7f1d21eee22f1615dc35.png)

![](image/5b4c05b9b894b02a85982b7742164a33.png)

![](image/2767adf87bdb8b38816250d2fba86fd5.png)

![](image/102381c751c80b5f1703f24c1c71b066.png)

 ![](image/2a312fc2597547ff92e97509832a2213.png)

#### 2.在硬盘中创建分区：fdisk /dev/sdb

![](image/eb300ff4941cde7ad242f064a3e92921.png)

![](image/7dfac3b1a1949951e66129bce212141a.png)

![](image/76d9304a5111b0a25efe68a93ca03234.png)

![](image/28e3f03acd19bfd6acdc8eeefe7b4247.png)

#### 3.格式化硬盘：mkfs -t ext4 /dev/sdb1

![](image/83a4f4af7c1e50475f2549ce0d9b25d5.png)

![](image/1f695c68ab0a082029204f50761d0083.png)

#### 4.挂载mount：mount /dev/sdb1 /newdisk

![](image/fe44d14a3ebefdf98a047df8c6099365.png)

![](image/24c0d53789af21305c8137ea98e6259f.png)

![](image/ee3556e4a884825a212f2b5998663243.png)

#### 5.取消挂载unmount

#### 6.自动挂载【永久挂载】：/etc/fstab

![](image/f123799167a924aa48dc8e8b57f75be4.png)

![](image/3cded573fee18ec2c44df6960764a724.png)

### 5.磁盘情况查询：df -h

![](image/32f99c990d19695b466e9acf91ae4763.png)

![](image/5c0839c58c1670047c564060fde083af.png)

### 6.查询指定目录的磁盘占用情况：du -ha /目录

![](image/7e03de9e851cdb9921f99e25da7430f0.png)

> 如果没有指定目录，则表示当前目录

![](image/efa70bea90a45a908320605d2579ffe1.png)

### 7.磁盘工作实用指令

![](image/a520f1b1c8e5b12512981be98a3a14a7.png)

## 21.网络配置

### 1.Linux网络配置原理图【NAT网络配置】

![](image/0041e09f88c6a578d42b09d83e57e615.png)

### 2.网络配置指令

![](image/01d744f9adbf7441b81a6bc52247a817.png)

#### 查看window环境中的VMnet8网络配置--**ipconfig**

#### **查看linux的网络配置---ifconfig**

> **IP要在同一个网段才可以进行通信**

![](image/da9ec2019abb6edd6a30222319017bc2.png)

#### ping测试主机之间网络连通性

![](image/8d2e744f905190fbc85c41e99a37f88b.png)

### 3.linux网络环境配置

#### 方法一：自动获取

![](image/05074875059ea239117ca68ba6f1cfd0.png)

#### 方法二：指定ip

![](image/c8972db9b55f67802406f001421f61d7.png)

    vim /etc/sysconfig/network-scripts/ifcfg-ens33

![](image/d40fc10083c00e1347d81817871fc1f2.png)

    BOOTPROTO=static#IP地址IPADDR=192.168.200.130#网关GATEWAY=192.168.200.2#域名解析器DNS=192.168.200.2"

![](image/82aee07e6f6df45860719263e44f4e9d.png)

### 3.设置主机名和hosts映射

#### a. 设置主机名--vim /etc/hostname

#### b. 设置hosts映射--vim /etc/hosts

![](image/7cd74e1575872a4833bc89d44ddc2a46.png)

### 4.主机名解析过程分析（Hosts,DNS)

#### 1.Hosts是什么

![](image/b2d6f8d1c2213925c75096e6843dd280.png)

#### 2.DNS：分布式数据库

![](image/2a40060d5db51d09203c99c1a6c59cb2.png)

#### 3.图示

![](image/f2c81c83cb840dc12878b274d0860bb2.png)

![](image/ce8276971b26da2d2f6904b9caa62684.png)

## 22.Linux进程管理

### 1.基本介绍

![](image/e961e00fe375743d7444a54bf3bcbfa2.png)

### 2.显示系统指向的进程--ps -aux | more/ ps -ef【全格式显示】

> \-e是显示所有进程，不管有没有被执行。-a是显示当前终端执行的所有进程

![](image/091a517e81783c7f9c525194e06063a7.png)

![](image/226c087a58ad49ed782d950c557cd816.png)![](image/14043a9bb2537e3a91c73c51fa88c03c.png)

### 3.应用

![](image/0511199fd84dffc9c15bd27931402006.png)

![](image/14ace63b1ddd2f9fd37cde40fb280587.png)

### 4.终止进程kill和killall

> 消除远端的进程：killall sshd
>
> 消除本机的进程:killall bash

![](image/25a9cf18f4a32aa16c3a1614a00677a3.png)

### 5.查看进程数pstree

> 显示进程号;pstree -p

![](image/85862d2ef90761a138c0db47986778ab.png)

### 6.服务（service)的管理命令【本质-进程】

![](image/1c3838bb0fff5bbb684cabc4025e0b64.png)

![](image/b92f7e72fc6913fa30cac759c72c6969.png)

#### 查看服务名：setup

![](image/d583c67d49dcf96185db6c2c5e4c12d1.png)

![](image/7def0a309785ff0272248d2a97c39f4c.png)

> **使用【tab】可以选择退出**

### 7.服务的运行级别：7个级别

![](image/eab7a5d68d8987be346ffcaa3de3ecaa.png)

#### 开机流程

![](image/fa537b2218402786cc0123a4efcb8ef5.png)

#### 运行级别的修改

![](image/e238999f0895eeb11b9d8966e4571ed8.png)

### 8.服务（chkconfig指令）：chkconfig --level3 network off\[on\]

> 管理服务在每个级别的自启动
>
> **注意点：如果使用chkconfig设置后，需要reboot才能生效**

![](image/e96f111363044b6aba8a326c77985b57.png)

![](image/fff3a6349b75e037060adbbd7348f258.png)

![](image/6d50e63ee22bb7b09cc767baf970b2b7.png)

### 9.服务管理systemctl管理指令

> **systemctl stop firewalld--->临时关闭防火墙**
>
> **systemctl enable/disable firewalld--->永久设置防火墙**

![](image/5cd2cc54b3b00506b991a3d851c5b77d.png)

![](image/d51bf30e8dfb8534eb2982461f72b89b.png)

### 10.服务管理fillwall指令--打开或者关闭指定端口

> **打开或者关闭防火墙后要重新载入开生效**

![](image/573fe8189114e355935b512729433b7c.png)

> 打开端口：firewall-cmd --permanent --add-port=端口号/协议

### 11.动态监控进程:top【与ps相似】

> **top -->默认每3秒更新**

![](image/ff631d8b3ba28104680e661f75589e4b.png)

![](image/a46acfaf5a20f81557729a0ff8dd5a17.png)

### 12.动态监控进程交换操作

![](image/b430ffc7c63addcbfa8c9f77b7c401f2.png)

### 13.监控网络状态：netstat -anp | more xx

![](image/b0f74f8b970d342257475e502d0d568a.png)

![](image/4e017935155b1f30422649cb2d99eb84.png)

## 23.RPM和YUM

### 1.rmp包管理

![](image/31de1bdcb074dba51e996a19559c55d0.png)

### 2.rmp查询指令---rpm -qa | grep xxx

![](image/d23748e5c1db15cb669b0741c928c07e.png)

### 3.rmp包名基本格式

![](image/e93da186e9648286cc447b2ae032cb11.png)

### 4.rmp其他查询指令

![](image/390fe209d94298efa2f4ca8dd972381d.png)

### 5.rpm卸载:rpm -e xxx

![](image/87afed8d49e84b462f2a1b752686a27e.png)

### 6.rpm安装：rpm -ivh RPM包全路径名称

> **rpm安装包都放在CentOS中**

![](image/7f75f6c68da63acdabc7032280c90a8a.png)

### 7.yum【基于RPM】：yum install xxx

![](image/c0b1c48b1095d8eec2fee62490f9eabf.png)

## 24.搭建JavaEE环境

### 1.安装配置JDK1.8

![](image/85500de075e1274452898589b2332c73.png)

#### 1.mkdir /opt/jdk

![](image/270d93d09a55f3ca5964151b3493af2a.png)

![](image/cb5a2ce979680c82b7fab7121c97fdfb.png)

![](image/eb87c2e03170112be7eaea8b89661bb8.png)

#### 2.cd /opt/jdk

![](image/7d2e6132acaea23fb288a0922acdc842.png)

#### 3.解压：tar -zxvf jdk-.zip

![](image/a5fe710b58330296f6d6046228845136.png)

![](image/ae3a0e4531aa39774597b55b036a7cb6.png)

#### 4.创建一个文件夹进行存放:/usr/local/java/jdk

![](image/3e96d23570ea0f26625f20224bc5293b.png)

#### 5.配置环境变量的配置文件：vim /etc/profile

![](image/ef5bfa5e7c938f6705ede77aace08e8b.png)

![](image/2b89f52dcdf5e46099e95e2338599f9b.png)

![](image/d3ce139fdf738a99784487e7e63029d4.png)

> **export JAVA\_HOME=/usr/local/java/jdk...**
>
> **export PATH=$JAVA\_HOME/bin:$PATH**

#### 6.让新的环境变量生效：source /etc/profile

> 查看版本：javac -version
>
>              java -version

### 2.安装tomcat

#### 1.创建目录：mkdir /opt/tomcat

![](image/edf147b3c9e35ebdc21e97bbb7a28314.png)

![](image/6b124ca9296c3b3e3a4b09ecff8f27ce.png)

#### 2解压：tar -zxvf -tomcat

![](image/bd7bbc894b039623b34a9c369cefa3cf.png)

![](image/64c5fca6473ed1aca2ee36f558fb7c84.png)

#### 3.安装：startup

![](image/fba70fb38ae6f74cc3ee42fd7d4a9381.png)

#### 4.打开防火墙中预防的8080

> firewall-cmd --permanent --add-port=8080/tcp

![](image/016f0e98c2ffcdf15a3e162871b5bee5.png)

#### 5.重载一下：firewall-cmd --reload

![](image/29d3db554d5cdfe2cdff57fbe3508786.png)

![](image/12f17f685398f8533cfebcd51eecf0a8.png)

![](image/9b07ed80bbb653b199ddfbd8fa266cab.png)

## 参考

[【韩顺平】Linux基础_韩顺平linux-CSDN博客](https://blog.csdn.net/m0_63077733/article/details/132579223?ops_request_misc=%7B%22request%5Fid%22%3A%22172257936116800184168400%22%2C%22scm%22%3A%2220140713.130102334.pc%5Fall.%22%7D&request_id=172257936116800184168400&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-132579223-null-null.142^v100^pc_search_result_base5&utm_term=韩顺平linux笔记&spm=1018.2226.3001.4187)