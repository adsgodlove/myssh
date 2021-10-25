### 安装依赖
```bash
npm install electron --save-dev
```
### 添加代理
```bash
npm config set proxy=http://proxy.picc.com.cn:3129
npm config set https-proxy=http://proxy.picc.com.cn:3129
```
### 删除代理
```bash
npm config delete proxy
npm config delete https-proxy
```