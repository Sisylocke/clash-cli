你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
## clash-cli
Use command line to manage clash proxy settings. 

## Installation
Windows platform is not supported yet.

#### Manual
Download from [release](https://github.com/Sisylocke/clash-cli/releases), then extract it to you PATH.

#### Use GO
```
go get github.com/Sisylocke/clash-cli
```
## Usage

```
clash-cli [flags]

Flags:
  -a, --add      add a new piece of rule
  -d, --delete   delete an existed piece of rule
  -f, --find     find a specific piece of rule
  -h, --help     help for clash-cli
  -m, --mode     change the proxy mode: GLOBAL, Rule or Direct
  -n, --node     switch to another proxy node
  -s, --status   show the current clash status
```
