# Website

**Table of Contents**

- [Current Tasks](#tasks)
- [Event List](#event-list)
- [Comparison Plots](#comparison-plots)

# Tasks
- [ ] Set up a script to reduce data files into easily readable formats for the bokeh script
  - [ ] Proton Flux
  - [ ] Xray Flux
  - [ ] Neutron Monitor
- [ ] Set up comparisons between event dates rather than data sets
- [ ] Translate bokeh figures into axes objects
- [ ] Generate event list in a table


# Event List

|			    | Event Start Datetime  | Flare Classification | Location |  CME Speed [km/s]
|:--------------|:----------------------|:--------------|:----------|:--------------|
|	1 			|	2011/06/07 06:16:00	|	M2.5    	|	S22W53	|				|
|	2 			|	2011/08/04 03:41:00	|	M9.3    	|	N16W38	|				|
|	3 			|	2011/08/09 07:48:00	|	X6.9    	|	N14W69	|				|
|	4 			|	2011/09/06 22:12:00	|	X2.1    	|	N14W18	|				|
|	5 			|	2011/09/22 10:29:00	|	X1.4    	|	N09E89	|				|
|	6 			|	2012/01/23 03:38:00	|	M8.7    	|	N33W21	|				|
|	7 			|	2012/01/27 17:37:00	|	X1.7    	|	N33W85	|				|
|	8 			|	2012/03/07 00:02:00	|	X5.4    	|	N18E31	|				|
|	  			|	2012/03/07 01:05:00	|	X1.3    	|	N15E26	|				|
|	9 			|	2012/03/13 17:12:00	|	M7.9    	|	N17W66	|				|
|	10			|	2012/05/17 01:25:00	|	M5.1    	|	N07W88	|				|
|	11			|	2012/07/06 23:01:00	|	X1.1    	|	S13W59	|				|
|	12			|	2012/07/08 16:23:00	|	M6.9    	|	S14W86	|				|
|	13			|	2012/07/19 04:17:00	|	M7.7    	|	S13W88	|				|
|	14			|	2012/07/23 01:50:00	|	BACKSIDE	|	      	|				|
|	15			|	2013/04/11 06:55:00	|	M6.5    	|	N07E13	|				|
|	16			|	2013/05/22 13:08:00	|	M5.0    	|	N14W87	|				|
|	17			|	2013/09/29 21:43:00	|	Filament	|	      	|				|
|	18			|	2013/10/28 04:32:00	|	M5.1    	|	N08W71	|				|
|	19			|	2013/11/02 04:40:00	|	C8.2 (B)	|	S21W03	|				|
|	20			|	2013/12/28 17:16:00	|	BACKSIDE	|	      	|				|
|	21			|	2014/01/06 08:00:00	|	BACKSIDE	|	      	|				|
|	22			|	2014/01/07 18:04:00	|	X1.2    	|	S12W08	|				|
|	23			|	2014/02/25 00:39:00	|	X4.9    	|	S12E77	|				|
|	24			|	2014/04/18 12:31:00	|	M7.3    	|	S20W34	|				|
|	25			|	2014/09/01 21:58:00	|	BACKSIDE	|	      	|				|
|	26			|	2014/09/10 17:21:00	|	X1.6    	|	N11E05	|				|
|	27			|	2015/10/29 n/a     	|	BACKSIDE	|	      	|				|
|	28			|	2017/09/06 11:53:00	|	X9.3    	|	S09W34	|				|
|	29			|	2017/09/10 15:35:00	|	X8.2    	|	S08W88	|				|



# Using Bokeh
<details><summary>Bokeh Instructions</summary>
<p>

In the "daily" directory, use the following command. The "main.py" file must be in the directory above the nested "daily" directory.

[Comparison Plot](/_includes/proton_plot.html)
[Individual Plot](/_includes/proton_plot_individual.html)

  
{% highlight ruby linenos %}
bokeh serve .
{% endhighlight %}

</p>
</details>

# Last Changed 20180306 4:52p

# Plots

### CDN Option
{% include proton_plot.html %}


---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](another-page).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## [](#header-2)Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```