# Task 4-1

<a id="e-start"></a>[__*Beginning -- "Learn the bash shell 3rd edition, O'REILLY (Chapter 4. Basic Shell Programming)"*__](#e-end)


You have a large album collection, and you want to write some soft ware to keep track of it. Assume that you have a file of data on how many albums you have by each artist. Lines in the file look like this:

```txt
5 Depeche Mode
2 Split Enz
3 Simple Minds
1 Vivaldi, Antonio
```

Write a program that prints the N highest lines, i.e., the N artist by whom you have the most albums. The default for N should be 10. The program should take one argument for the name of the input file and optional second argument for how many lines to print.

Output we're looking for:

<pre><code>
<b>$ cat album-count-by-artist.txt</b>
5 Depeche Mode
2 Split Enz
3 Simple Minds
1 Vivaldi, Anotonio

<b>$ bash script album-count-by-artist.txt</b>
5 Depeche Mode
3 Simple Minds
2 Split Enz
1 Vivaldi, Anotonio
</pre></code>

<a id="e-end"></a>  [__*End       -- "Learn the bash shell 3rd edition, O'REILLY (Chapter 4. Basic Shell Programming)"*__](#e-start)
