<div align="center">
  <img src="images/title.png" width="80%"/>
</div>

<h1 align="center">用 Python 爬下杭电 OJ 部分题目</h1>

昨天在暑期实训的时候刚好介绍了使用 Python 来爬取部分学校的研究生官网的报录文件，头一次感受到 Python 的魅力，于是码瘾犯了，想着做个爬虫爬取 OJ 的题目（某些 OJ 网络不稳定，爬取下来方便刷题）

### 目录 {ignore=true}


<!-- code_chunk_output -->

- [环境配置](#环境配置)
- [库介绍](#库介绍)
- [如何使用](#如何使用)
- [结果展示](#结果展示)
- [未来计划](#未来计划)
- [致谢](#致谢)

<!-- /code_chunk_output -->



## 环境配置
- Python 3.8.10
- pip 21.1.1

## 库介绍

TODO：这里放个表格介绍

## 如何使用

0. 设置镜像源
```python
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```

1. 安装依赖
```python
pip install requests
```

```python
pip install requests
```

3. 在 `main.py` 中直接点击运行即可在 `hdu题库` 目录 找到几千份 `txt` 文件

## 结果展示


<table width="100%" cellspacing="0" cellpadding="0">
  <tr align="center" valign="middle">
    <td width="50%">
      <img src="images/test.png" width="100%"/>
    </td>
    <td width="50%">
      <img src="images/result.png" width="100%"/>
    </td>
  </tr>
</table>


## 未来计划

- [X] 实现 `txt` 文件分开保存每个题目
- [ ] 处理为 `csv` 格式文件，方便保存在 `Excel` 中，以便后续支持写入数据库
- [ ] 支持各大 OJ 网站爬取

## 致谢

感谢 [@edxuanlen](https://github.com/edxuanlen) 的博客文章提供的技术支持
[喜欢博客的可以点击这里🤩](https://blog.csdn.net/edxuanlen/article/details/80252135?spm=1001.2014.3001.5502)