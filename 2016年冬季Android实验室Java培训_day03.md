# 2016年冬季Android实验室Java培训_day03
---
<br/>

## 补充内容：泛型在集合中的应用
### 1. 确定元素类型
### 2. 通配符和上下限 

<br/>

## 第一部分：异常处理
### 1. 异常概述
### 2. Java内置异常
### 3. 抛出异常
### 4. try和catch（多重catch）
### 5. finally
### 6. 自定义异常（throws）
### 7. e.g.

<br/>

## 第二部分：I/O体系（输入／输出）

### 1. I/O基本概念
### 2. 流的介绍
<table style="float: left; background-color: #ffffff; border: 0px solid #000000;" border="0">
<tbody>
<tr>
<td style="text-align: left;">流分类</td>
<td>使用分类</td>
<td>字节输入流</td>
<td>字节输出流</td>
<td>字符输入流</td>
<td>字符输出流</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>抽象基类</td>
<td><span style="text-decoration: underline;"><em>InputStream</em></span></td>
<td>
<p><span style="text-decoration: underline;"><em>OutputStream</em></span></p>
</td>
<td><span style="text-decoration: underline;"><em>Reader</em></span></td>
<td><span style="text-decoration: underline;"><em>Writer</em></span></td>
</tr>
<tr>
<td rowspan="4"><span style="background-color: #ffffff;">节点流</span></td>
<td><span style="background-color: #ffffff;">访问文件</span></td>
<td><strong>FileInputStream</strong></td>
<td><strong>FileOutStream</strong></td>
<td><strong>FileReader</strong></td>
<td><strong>FileWriter</strong></td>
</tr>
<tr>
<td><span style="background-color: #ffffff;">访问数值</span></td>
<td><strong>ByteArrayInputStream</strong></td>
<td><strong>ByteArrayOutStream</strong></td>
<td><strong>CharArrayReader</strong></td>
<td><strong>CharArrayWriter</strong></td>
</tr>
<tr>
<td><span style="background-color: #ffffff;">访问管道</span></td>
<td><strong>PipedInputStream</strong></td>
<td><strong>PipedOutStream</strong></td>
<td><strong>PipedReader</strong></td>
<td><strong>PipedWriter</strong></td>
</tr>
<tr>
<td><span style="background-color: #ffffff;">访问字符串</span></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td><strong>StringReader</strong></td>
<td><strong>StringWriter</strong></td>
</tr>
<tr>
<td rowspan="7">处理流</td>
<td>缓冲流</td>
<td>BufferedInputStream</td>
<td>BufferedOutputStream</td>
<td>BufferedReader</td>
<td>BufferedWriter</td>
</tr>
<tr>
<td>转换流</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>InputStreamReader</td>
<td>OutputStreamWriter</td>
</tr>
<tr>
<td>对象流</td>
<td>ObjectInputStream</td>
<td>ObjectOutputStream</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>抽象基类（过滤）</td>
<td><span style="text-decoration: underline;"><em>FilterInputStream</em></span></td>
<td><span style="text-decoration: underline;"><em>FilterOutputStream</em></span></td>
<td><span style="text-decoration: underline;"><em>FilterReader</em></span></td>
<td><span style="text-decoration: underline;"><em>FilterWriter</em></span></td>
</tr>
<tr>
<td>打印流</td>
<td>&nbsp;</td>
<td>PrintStream</td>
<td>&nbsp;</td>
<td>PrintWriter</td>
</tr>
<tr>
<td>推回输入流</td>
<td>PushbackInputStream</td>
<td>&nbsp;</td>
<td>PushbackReader</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>特殊流</td>
<td>DataInputStream</td>
<td>DataOutputStream</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>

### 3. 介绍常用API

