<div class="search-container">
  <input type="text" id="searchInput" placeholder="Search projects...">
  <button onclick="searchProjects()">Search</button>
</div>

<script>
function searchProjects() {
  const input = document.getElementById('searchInput').value.toLowerCase();
  const projects = document.getElementsByClassName('project');

  for (let i = 0; i < projects.length; i++) {
    const project = projects[i];
    const title = project.querySelector('h3').innerText.toLowerCase();

    if (title.includes(input)) {
      project.style.display = '';
    } else {
      project.style.display = 'none';
    }
  }
}
</script>



![Alt text](assets/images/front_page.jpg)


# Welcome to My Blog!

This is my new blog where I will write about **gaming, Fortnite, Minecraft, and tech**.

## Latest Posts

## 📖 Read My Blog
[Click here to see all posts](/blog.html)


Please comment and share my blog to all your friends


Please join our discord server! 

<a href="https://discord.gg/HS6TabVCnC" target="_blank" class="discord-button">Join our Discord</a>

    
    

    
    
    
    
    






    







    
    
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://https-dantheman0708-github-io.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
