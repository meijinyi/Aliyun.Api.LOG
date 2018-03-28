# Aliyun.Api.LOG .net standard 2.0
#重写阿里云日志sdk， standard 2.0
#里面的逻辑改了两处
1.HttpExtensions类中的AddInternal方法；2.HmacSHA1Signature类中的ComputeSignatureCore 原因都是standard 2.0中有新的写法了。
#注意: 改版后只在win平台跑过，linux平台未测试，如果有人测试过了，把结果告诉我。谢谢
