## chapter.site.template 
![:octocat:](https://assets-cdn.github.com/images/icons/emoji/octocat.png ":octocat:")The Project has been started by [Juuso (jeukku)](https://github.com/jeukku) in order to form a template example   
that could be used across The Zeitgeist Movement Chapters' websites hosted on any GitHub Repository.

## Understanding the Jekyll Project structure.

<h3>Pro Tip:</h3>
<code>
<b>Folders</b> that begins <b>without</b> an <b>Underscore (_)</b> are directly copied into 
<code><b>📂/_site</b>(inaccessible for repository users)</code> and all its contents are sent to a browser.
</code>

<br>First of all when you fork this repository and enable <b>GitHub Pages Sources</b> for <b>Master branch</b>
<ol>
	<li>The <code><b>📄/_config.yml</b> file</code> will be initialized, all the configurations will be applied that were written inside.</li>
	<li>
		<details>
			<summary>Then it (GitHub Pages) will start looking for <code><b>📄 /index.md</b> file</code> which is the first page of the whole repository.<br></summary>
			<blockquote>Inside this file there is only a single most important line of Jekyll settings: <code><b>layout:</b></code>
				<br><img src="https://cdn.pbrd.co/images/HxTVVUB.png" alt="foo" title="title" />
				<br><b> <code>layout: home</code></b> line tells Jekyll to look for a layout (<code><b>📄 home.html</b> file</code>) inside <code><b>📂/_layouts</b> folder</code>
			</blockquote>
		</details>
	</li>
	<li>
		<details>
			<summary>The layout (<code><b>📄 _layouts/home.html</b></code>) will be wraped around <code><b>📄 /index.md</b> file</code> with html</summary>
			<blockquote>
				<img src="https://cdn.pbrd.co/images/HxUoxXl.png" alt="foo" title="title" />
				<br>The layout (<b>📄 _layouts/home.html</b>) generaly consist of another layout and a <code>{{ content }}</code> variable. 
				<ol>
					<li>Another declaration of <code>layout: default</code> at the top of the inside it. </li>
					<li>A special variable {{ content }}</li>
				</ol>
			</blockquote>
		<details>
	</li>
	<li>While <code><b>📄 _layouts/default.html</b></code> will be wrapped around <code><b>📄 _layouts/home.html</b></code></li>
	<li><code><b>📄 _layouts/home.html</b></code> and <code><b>📄 _layouts/default.html</b></code> linking all the stylesheets and images<br> to the resources inside <code><b>📂/assets</b> folder</code> and <code><b>📂/_includes</b> folder</code>
	</li>
	<li><code><b>📂/_includes</b></code> contains all reusable parts that contains embeded Jekyll interpretable code with html for <code><b>📂/_layouts</b></code></li>
	<li><code><b>📂/_posts</b> folder</code> contains your own written posts that are scanned by Jekyll and could be linked from html files in <br><code><b>📂/_includes</b></code>,  <code><b>📂/_layouts</b></code>, <code><b>📂/assets</b></code> or by <code><b>📄 index.md</b></code></li>
	<li>GitHub Pages forms index.html in <code><b>📂/_site</b>(inaccessible for repository users)</code> and serves it to your browser with resources from  <code><b>📂/assets</b> folder </code>.</li>
	<li>Your browser receives index.html, stylesheets, images and displays them.</li>
</ol>


## The Project's main structure

| [![Jekyll Logo](http://u.cubeupload.com/boqsc/jekyllsmall.png)](https://jekyllrb.com/docs/home/) | Yekyll structure description  | |
|:-:|-|-|
| 📂_includes | These are the partials that can be mixed and matched by your layouts and posts to facilitate reuse. <br> <blockquote>The liquid tag`{% include file.ext %}` can be used to include the partial in`_includes/file.ext`.</blockquote> |
| 📂_layouts | These are the templates that wrap posts. Layouts are chosen on a post-by-post basis in the [YAML Front Matter](https://jekyllrb.com/docs/frontmatter/), which is described in the next section. <br> <blockquote>The liquid tag `{{ content }}` is used to inject content into the web page.</blockquote> |
| 📂_posts | Your dynamic content, so to speak. <br> <blockquote>The naming convention of these files is important, and must follow the format: `YEAR-MONTH-DAY-title.MARKUP`.</blockquote> |
| 📂_sections | **Can someone take the quest** ❔ <br>We need to fill this interesting space. |
| 📂assets | The place where Images, Stylesheets are stored |
| 📂pages | These are the partials that can be mixed and matched by your layouts and posts to facilitate reuse.  |
| 📄_config.yml | Stores configuration data. Many of these options can be specifie the command line executable but it’s easier to specify them here so you don’t have to remember them.
| 📄 index.md | The main GitHub Pages serving file, this is the main file GitHub serves after _config.yml is finished rendering.
 

 <details> 
  <summary> 🐢 <code>yo bro where is my home.</code> https://jekyllrb.com/docs/structure/</summary>
🐢<code>sometimes I travel home from far away.</code><br>  
🐢<code>when I dream, I dream about a place I call home.</code><br>  
🐢<code>I wish I was home, I need to water those lovely flowers.</code><br>  
🐢<code>I'm sad knowing  that I'm far away from home.</code><br>  
🐢<code>They said It will be few more days and I'll be back home.</code><br>  
🐢<code>I'm studying household management, once I'm back home.</code><br>  
🐢<code>the coldest winters won't break my shell, homesick I'm.</code><br>  
🐢<code>I could smell the trees, they are familiar, coming home.</code><br>  
🐢<code>I hear, I tap I'm comming back home.</code><br>  
🐢<code>my feet is hurt, but i'll come back home.</code><br>  
🐢<code>saw a place to rest, soon to be home.</code><br>  
🐢<code>can we have something to eat, please take me home.</code><br>  
🐢<code>wouldn't that be great to visit some familiar place.</code><br>  
🐢<code>the grass is greener when we comeback.</code><br>  
🐢<code>could you tell me the direction of home.</code><br>  
🐢<code>the wisdom, it rests where I lived.</code><br>  
🐢<code>it was hard to leave home.</code><br>  
🐢<code>finally, a path to look forward home.</code><br>  
🐢<code>depressing, to be so far away from home.</code><br>  
🐢<code>I'm an old traveler, home I'm comming.</code><br>  
🐢<code>I felt great, until I realised how far from home I'm.</code><br>  
🐢<code>Hearing those stories, made me homesicked.</code><br>  
🐢<code>the temporal the life is, I'l better come home soon.</code><br>  
🐢<code>If the wisdom had a word, it would be near home.</code><br>  
🐢<code>once I fought and now I'm wiser as I get closer... home.</code><br>  
🐢<code>let's go home and find the truth of train of though.</code><br>  
🐢<code>It's here, it is near, near - it's home.</code><br>  
🐢<code>I'm turtle, but I know when to come home</code><br>  
</details>
