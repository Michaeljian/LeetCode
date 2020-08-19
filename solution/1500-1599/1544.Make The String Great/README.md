# [1544. 整理字符串](https://leetcode-cn.com/problems/make-the-string-great)

[English Version](/solution/1500-1599/1544.Make%20The%20String%20Great/README_EN.md)

## 题目描述

<!-- 这里写题目描述 -->
<p>给你一个由大小写英文字母组成的字符串 <code>s</code> 。</p>

<p>一个整理好的字符串中，<strong>两个相邻字符</strong> <code>s[i]</code> 和 <code>s[i + 1]</code> 不会同时满足下述条件：</p>

<ul>
	<li><code>0 &lt;= i &lt;= s.length - 2</code></li>
	<li><code>s[i]</code> 是小写字符，但 <code>s[i + 1]</code> 是相同的大写字符；<strong>反之亦然</strong> 。</li>
</ul>

<p>请你将字符串整理好，每次你都可以从字符串中选出满足上述条件的 <strong>两个相邻</strong> 字符并删除，直到字符串整理好为止。</p>

<p>请返回整理好的 <strong>字符串</strong> 。题目保证在给出的约束条件下，测试样例对应的答案是唯一的。</p>

<p><strong>注意：</strong>空字符串也属于整理好的字符串，尽管其中没有任何字符。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>s = &quot;leEeetcode&quot;
<strong>输出：</strong>&quot;leetcode&quot;
<strong>解释：</strong>无论你第一次选的是 i = 1 还是 i = 2，都会使 &quot;leEeetcode&quot; 缩减为 &quot;leetcode&quot; 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>s = &quot;abBAcC&quot;
<strong>输出：</strong>&quot;&quot;
<strong>解释：</strong>存在多种不同情况，但所有的情况都会导致相同的结果。例如：
&quot;abBAcC&quot; --&gt; &quot;aAcC&quot; --&gt; &quot;cC&quot; --&gt; &quot;&quot;
&quot;abBAcC&quot; --&gt; &quot;abBA&quot; --&gt; &quot;aA&quot; --&gt; &quot;&quot;
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>s = &quot;s&quot;
<strong>输出：</strong>&quot;s&quot;
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 100</code></li>
	<li><code>s</code> 只包含小写和大写英文字母</li>
</ul>


## 解法

<!-- 这里可写通用的实现逻辑 -->


<!-- tabs:start -->

### **Python3**

<!-- 这里可写当前语言的特殊实现逻辑 -->

```python

```

### **Java**

<!-- 这里可写当前语言的特殊实现逻辑 -->

```java

```

### **...**
```

```

<!-- tabs:end -->