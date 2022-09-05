# 蒙古人ACG

https://www.mgracg.com 的源代码，欢迎大家访问

使用 [Jekyll](https://github.com/jekyll/jekyll) 生成

## 关于网站建设

参考的Jekyll 模板：[template-pintereso-bootstrap-jekyll](https://wowthemesnet.github.io/template-pintereso-bootstrap-jekyll/index.html)

## 运行测试

安装 bundler

```
sudo apt install bundler
```

升级库

```
bundle update github-pages
```

运行测试

```
bundle exec jekyll s
```

## Troubleshooting

`cannot load such file -- webrick`

solution:

`bundle add webrick`