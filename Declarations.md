---


---

<h1 id="declarations">Declarations</h1>
<p>There are four types of declaration. Constant constants can’t be changed in any way.</p>
<pre class=" language-java"><code class="prism  language-java"><span class="token keyword">const</span> <span class="token keyword">const</span> name <span class="token operator">=</span> <span class="token string">"Luke"</span><span class="token operator">!</span>
</code></pre>
<p>Constant variables can be edited, but not re-assigned.</p>
<pre class=" language-java"><code class="prism  language-java"><span class="token keyword">const</span> var name <span class="token operator">=</span> <span class="token string">"Luke"</span><span class="token operator">!</span>
name<span class="token punctuation">.</span><span class="token function">pop</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token operator">!</span>
name<span class="token punctuation">.</span><span class="token function">pop</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token operator">!</span>
</code></pre>
<p>Variable constants can be re-assigned, but not edited.</p>
<pre class=" language-java"><code class="prism  language-java">var <span class="token keyword">const</span> name <span class="token operator">=</span> <span class="token string">"Luke"</span><span class="token operator">!</span>
name <span class="token operator">=</span> <span class="token string">"Lu"</span><span class="token operator">!</span>
</code></pre>
<p>Variable variables can be re-assigned and edited.</p>
<pre class=" language-java"><code class="prism  language-java">var var name <span class="token operator">=</span> <span class="token string">"Luke"</span><span class="token operator">!</span>
name <span class="token operator">=</span> <span class="token string">"Lu"</span><span class="token operator">!</span>
name<span class="token punctuation">.</span><span class="token function">push</span><span class="token punctuation">(</span><span class="token string">"k"</span><span class="token punctuation">)</span><span class="token operator">!</span>
name<span class="token punctuation">.</span><span class="token function">push</span><span class="token punctuation">(</span><span class="token string">"e"</span><span class="token punctuation">)</span><span class="token operator">!</span>
</code></pre>

