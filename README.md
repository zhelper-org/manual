# manual

符合规范的 API 接口开发手册

## 说明

在进行 API 开发时，请遵循此手册，以便于前端以及 TGBOT 等服务的直接对接。

## 书籍数据规范 Book-A

Book-A 规范适用于信息比较详细的数据源。旨在提供所有必要的数据。



### 搜索接口

数据结构

```python
{'data': [{'title': '经典电动力学',
   'author': 'John David Jackson; 朱培豫',
   'publisher': '人民教育出版社',
   'isbn': None,
   'extension': 'pdf',
   'filesize': 13022438,
   'pages': '517',
   'year': '1979',
   'id': 3511906}],
 'hits': 47}
```

### 详情接口



```python
{'title': 'J.D.杰克逊经典电动力学解题指导 深圳大学学报（增刊）',
 'author': '奚定平',
 'publisher': '深圳大学学报编辑部',
 'isbn': None,
 'extension': 'pdf',
 'filesize': 6503584,
 'pages': '407',
 'year': '1988',
 'description': '',
 # 具体下载字段可以具体设置
 'md5': 'e8fe6cb0bcd91d98b8f34d0d9acdc279',
 'ipfs_cid': 'bafykbzacec4yvmt5szlf3ocwrc4lz4y57yeny5bweaqbd3pbev6d6276xac4m',
 'in_libgen': 0,
 'id': 21895906}
```

## 书籍数据规范 Book-B

Book-B 规范适用于比较粗略的搜索，只需要提供必要数据即可。

### 搜索界面

```

```