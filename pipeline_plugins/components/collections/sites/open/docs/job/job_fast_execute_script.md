# 作业平台(JOB)-快速执行脚本

### 介绍

快速执行脚本

### 标签

`job` `execute` `task`

### 参数说明

#### 输入参数说明

- 业务ID: 当前操作所属的 CMDB 业务 ID

- 脚本来源:
    待执行的脚本来源，手动(manual)，业务脚本(general)，公共脚本(public)

- 脚本类型：
    待执行的脚本类型：shell(1) bat(2) perl(3) python(4) powershell(5)" "，仅在脚本来源为手动时生效

- 脚本内容:
    待执行的脚本内容，仅在脚本来源为手动时生效

- 公共脚本:
    待执行的公共脚本 ID，仅在脚本来源为公共脚本时生效

- 业务脚本:
    待执行的业务脚本 ID，仅在脚本来源为业务脚本时生效

- 脚本执行参数:
    脚本执行参数

- 目标 IP:
    执行脚本的目标机器 IP，多个用英文逗号 `,` 分隔

- 目标账户:
    执行脚本的目标机器账户

- IP 存在性校验:
    是否做 IP 存在性校验，如果ip校验开关打开，校验通过的ip数量若减少，即返回错误

#### 输出参数说明

- 执行结果：

  JOB全局变量 输出日志中提取的全局变量

### 样例

![](image/job_fast_execute_script.png)

### 注意事项
