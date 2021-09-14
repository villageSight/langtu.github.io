# langtu.github.io
blog

## Project setup

### 1.First setup：install hexo-cli

```
> cnpm install hexo-cli -g /  npm install hexo-cli -g
```

### 2.Second setup：cd your blog subject， install node_moudles

```
> cnpm i / npm install
```

### 3.Third setup： run dev server

```
> hexo server / hexo s  （if this port is unavailable，change other port,  hexo s -p 8080）
```

### 4.Fourth setup： compile static resource (this step must be needed before deploy your blog!!!)

```
> hexo g
```

### 5.Fivth setup： deploy ，push publick resource to your remote resp (if your blog use jenkins deploy , this step can be omited and then login jenkins to deploy )

```
> hexo d
```

### Reference link
See [Hexo Official Docs](https://hexo.io/zh-cn/docs/one-command-deployment).
