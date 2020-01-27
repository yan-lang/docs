---
title: Function
weight: 4
---

# Function

<!-- ```swift
var a:int = 10
func add(a:int, b:int) -> int {
    return
}
``` -->

测试一下代码高亮

<div class="highlight"><pre><span></span><span class="k">func</span> <span class="nf">power</span><span class="p">(</span><span class="n">base</span><span class="p">:</span> <span class="kt">int</span><span class="p">,</span> <span class="n">e</span><span class="p">:</span> <span class="kt">int</span><span class="p">)</span> <span class="o">-&gt;</span> <span class="kt">int</span> <span class="p">{</span>
    <span class="k">var</span> <span class="n">i</span> <span class="o">=</span> <span class="mf">0</span><span class="p">;</span>
    <span class="k">var</span> <span class="n">result</span> <span class="o">=</span> <span class="mf">1</span><span class="p">;</span>
    <span class="k">while</span><span class="p">(</span><span class="n">i</span> <span class="o">&lt;</span> <span class="n">e</span><span class="p">)</span> <span class="p">{</span>
        <span class="n">result</span> <span class="o">*=</span> <span class="n">base</span><span class="p">;</span>
        <span class="n">i</span> <span class="o">+=</span> <span class="mf">1</span><span class="p">;</span>
    <span class="p">}</span>
    <span class="k">return</span> <span class="n">result</span><span class="p">;</span>
<span class="p">}</span>
</pre></div>
