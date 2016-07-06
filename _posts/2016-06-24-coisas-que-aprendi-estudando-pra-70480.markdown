---
layout: post
title:  "Coisas que aprendi estudando para 70-480 - Part 1"
date:   2016-06-24 01:00:22 -0300
categories: microsoft mcsd 70-480
tags: microsoft, mcsd, 70-480
---
<p>
Coisas interessantes acontecem quando se resolve estudar algo que você já faz todos os dias:
<ol>
  <li>antes de qualquer coisa: você não sabe tudo!</li>
  <li>existem coisas que ninguem usa (mas existem)!</li>
  <li>existem coisas que você poderia usar (mas nem sabia que existem)!</li>
</ol>
</p>

Seguem algumas dicas, truques e anotações feitas durante o percurso rumo a 70-482...

<h1>DOCTYPE</h1>
<p> DOCTYPEs do tipo transitional habilitam o uso elementos depreciados oriundos de versões anteriores do html.</p>
{% highlight html %}
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
{% endhighlight %}

<p> DOCTYPEs do tipo Frameset habilitam o uso de frames</p>
{% highlight html %}
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
{% endhighlight %}

<p> DOCTYPEs do tipo strict não permitem o uso de frames ou elementos depreciados de versoes anterioras do HTML</p>
{% highlight html %}
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/strict.dtd">
{% endhighlight %}

<h1>Tags, Elementos, Atributos e Conteudo</h1>
Uma lista completa pode ser consultada aqui:
<a href="https://dev.w3.org/html5/spec-author-view/global-attributes.html#global-attributes" target="_blank">https://dev.w3.org/html5/spec-author-view/global-attributes.html#global-attributes</a>

<h1>Enfase</h1>
<p>Use &lt;strong&gt; e &lt;em&gt; ao inves de &lt;b&gt; e &lt;i&gt;</p>

<h1>Listas</h1>
<p>Basicamente, existem três tipos: ordenadas (ol), não ordenadas (ul) e de definição: (dl)</p>
{% highlight html %}
<p>Here’s a small list of HTML editors</p>
<ul>
<li>Notepad</li>
<li>Textmate</li>
<li>Visual Studio</li>
</ul>
<p>Here’s how to write a web page</p>
<ol>
<li>Create a new text file</li>
<li>Add some HTML</li>
<li>Save the file to a website</li>
</ol>
<p>Here’s a small list of people in the Internet Hall of Fame and what they did</p>
<dl>
<dt>Sir Tim Berners Lee</dt>
<dd>Invented HTML and wrote WorldWideWeb</dd>
<dt>Linus Torvalds</dt>
<dd>Originator of Linux</dd>
<dt>Charles Herzfeld</dt>
<dd>Authorized the creation of ARPANET, the predecessor of the Internet</dd>
</dl>
{% endhighlight %}

<p>Resultado/:</p>

<p>Here’s a small list of HTML editors</p>
<ul>
<li>Notepad</li>
<li>Textmate</li>
<li>Visual Studio</li>
</ul>
<p>Here’s how to write a web page</p>
<ol>
<li>Create a new text file</li>
<li>Add some HTML</li>
<li>Save the file to a website</li>
</ol>
<p>Here’s a small list of people in the Internet Hall of Fame and what they did</p>
<dl>
<dt>Sir Tim Berners Lee</dt>
<dd>Invented HTML and wrote WorldWideWeb</dd>
<dt>Linus Torvalds</dt>
<dd>Originator of Linux</dd>
<dt>Charles Herzfeld</dt>
<dd>Authorized the creation of ARPANET, the predecessor of the Internet</dd>
</dl>

<h1>Imagens</h1>
Além dos atributos mais comuns (src, traget, alt, width e height), existem o title e o longdesc.

<h1>Hyperlinks</h1>
<p>Para o href, os atributos menos usados: o atributo rel (identifica o tipo de link esta sendo criado), hreflang (identifica o idioma do recurso linkado) e o type (identifica o MIME type do recurso linkado)</p>

<h1>FORMS</h1> 30
