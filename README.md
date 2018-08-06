## chapter.site.template 
![:octocat:](https://assets-cdn.github.com/images/icons/emoji/octocat.png ":octocat:")The Project has been started by [Juuso (jeukku)](https://github.com/jeukku) in order to form a template example   
that could be used across The Zeitgeist Movement Chapters' websites hosted on any GitHub Repository.

## Understanding the Jekyll project structure.

First of all when you fork this repository and enable <b>GitHub Pages Sources</b> for <b>Master branch</b>
<ol> 
 <li>the <b>📄/_config.yml</b> will be initialized, all the configurations will be applied that were written in <b>📄/_config.yml</b></li>
 <li>then it (GitHub Pages) will start looking for <b>📄 /index.md</b> file which is the first page of the whole repository.<br> 
      <blockquote>Inside this file there is only a single most important line of Jekyll settings: <code><b>layout:</b></code>
     <br><img src="https://cdn.pbrd.co/images/HxTVVUB.png" alt="foo" title="title" />
     <br><b> <code>layout: home</code></b> line tells Jekyll to look for a layout (<b>📄 home.html</b>) inside <b>📂/_layouts</b> folder
      </blockquote>
</li>
<li>the layout (<b>📄 home.html</b>) will be applied (wraped around with html) to  <b>📄 /index.md</b>
 <blockquote>The layout (<b>📄 _layouts/home.html</b>) generaly consist of </blockquote>
 </li>
 
 
 
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
| 📄_config.yml | Stores configuration data. Many of these options can be specified from the command line executable but it’s easier to specify them here so you don’t have to remember them.
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
