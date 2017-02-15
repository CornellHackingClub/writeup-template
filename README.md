# CHC (very temporary) Writeup Template Guide


## Neccesssary components to start any writeup

#### Start each writeup with the challenge title in an ```<h1>``` tag:

```html
<h1>Web100</h1>
```

#### Add the date you are completing the writeup in the format below:

```html
<p><i class="fa fa-clock-o"></i> Posted on February 13, 2017 at 9:45 AM</p>
```

#### Place the challenge hint in a ```<P>``` with ```class='lead'```:

```html
 <p class="lead">I know these guys are up to something. Just not sure what.</p>
```

## Now, switch off between any of the following as necessary

#### Adding explanation text:

```html
 <p>The site is just a simple username and password protected login. One can assume that proper authentication will lead to the flag.</p>
```

#### Adding basic, non-styled code:

```html
<pre><code>
MmI0YjAzN2ZkMWYzMDM3NWU1Y2Q4NzE0NDhiNWI5NWM=
Decoded: 2b4b037fd1f30375e5cd871448b5b95c
</code></pre>
```

NOTE: Indentation matters, see examples. Please DO NOT autoformat the html because it will mess up the code indentation.

#### Adding styled code (python):

```html
<pre class="prettyprint">
<code class="language-python">
  A="python"
  print A[1:2]
</code>
</pre>
```

#### Adding an image:

* First add your image to the img folder (its in the static folder).
* Yes you are correct, this is super janky lol

```html
<img src="../../static/img/irc_wireshark.png"  alt="First View" style="width: 100%"/>
```



#### Once finished, add the flag in a ```<h3>``` tag:

```html
<pre><code>
<h3><b>Flag:</b> flag{0mgth4tsaniceflag}</h3>
</code></pre>
```


## Additional Styling notes

Seperate the above sections with ```<br/>``` tags
