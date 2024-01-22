
<style>
	@import url("/utils/css/red.css");
	@import url("/utils/css/bootstrap-grid.css");
	@import url("/utils/css/iframe-youtube.css");
</style>


# markdown
markdown

[http://andrewalevin.github.io/markdown/](http://andrewalevin.github.io/markdown/)


### Grid


<div class="row g-4">
	<div class="col-12 col-md-6 col-lg-4">
		
		<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/TUJmSgViGoM?si=bnU2Pig1iCSsUYWu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
		# Title
  
    </div>
    <div class="col-12 col-md-6 col-lg-4">

  		<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Z4e3x6Y1HCY?si=ROldCH_0VvNbNPAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

  		# Title
 
    </div>
	<div class="col-12 col-md-6 col-lg-4">

  		<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/8182J3T5Z9k?si=cM5x-MNpGFGyFjff" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

 
    </div>
	<div class="col-12 col-md-6 col-lg-4">

  		<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/URWa0rbB1Kw?si=o6O1kgJwXaqJs71x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

 
    </div>
	<div class="col-12 col-md-6 col-lg-4">

  		<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/H_f70qm5HPE?si=Kv5tK4ITn7PBRflC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

 
    </div>
	<div class="col-12 col-md-6 col-lg-4">
		Column
    </div>
</div>

# Include

{% raw %}{% include part.md %}{% endraw %}

@@include[part.md](part.md)

# Other


<div class="row">
	<div class="span5 red-box">
		<p>First column contains couple of paragraphs. Lorem ipsum dolor sit
		amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt
		ut labore et dolore magna aliqua.</p>
		<p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
		nisi ut aliquip ex ea commodo consequat.</p>
	</div>
	<div class="span2">
		<p>Some images in the middle column:</p>
		<p><img alt="One" src="image-1.png" /></p>
		<p><img alt="One" src="image-1.png" /></p>
	</div>
	<div class="span5">
		<p>And some <strong>more</strong> text in the <em>third</em> column.
		Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
		dolore eu fugiat nulla pariatur.</p>
		<p><a href="http://excepteur.org">Excepteur</a> sint occaecat
		cupidatat non proident, sunt in culpa qui officia deserunt mollit
		anim id est laborum.</p>
	</div>
</div>





# Sample 3

<div style="text-align: center; display: grid; grid-template-columns: 1fr 1fr 1fr;">
	<div>
		block-1
		<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/ULybPQrDStk?si=BixbyRMf8cHIqVfZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
	</div>
	<div>
		block-2
	</div>

 <div class="box-1"> A </div>
  <div class="box-2"> B </div>
  <div class="box-3"> C </div>

   <div class="box-1"> D </div>
  <div class="box-2"> E </div>
  <div class="box-3"> F </div>
</div>

# Sample Bootstrap

<div class="container text-center">
  <div class="row">
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
  </div>
</div>

# Sample Embded

# Analytic data

The following data is available at: **`/n/dominici_nsaph_l3/projects/analytic/`**

```{include} part.md
```

````{warning}
The space of FASSE is limited, so do not copy analytic data to your own folder! Create symlinks to the data in your `data` folder.
Symbolic links (or symlinks) are special files that point to files or directories in other locations on your system.
You will be able to use data with symlinks as normal.

Create the symlink in your `data` folder in the following way:
```
cd data
ln -s /n/dominici_nsaph_l3/projects/analytic/fasse_location .
```
````

```{note}
You need data that is not here, but exists on RCE? 
If so, fill in the form [here](https://gist.github.com/atrisovic/93d379dd84e31f0d63b965de8d529777) to get it transfered to FASSE.
```

## Data questions

1. What data sources (MedPar, MBSF, other) were used to create this data file? How many different data sources went into it? 
2. What, if any, processing was done to the data sources? Were there any selections (cuts) done, data quality checks and aggregations? 
3. Was this data used in any publication (add a link)? 
4. Is there any git repository (or subfolder) related to it? (add git location)? 
5. What is the RCE source location? 
6. When was the data created and by who?
7. What is the spatial, temporal resolution? 






# Sample etc

# Sample etc

# Sample etc

# Sample etc


# Sample etc














