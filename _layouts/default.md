---
layout: default
---

{% include head.md %}
{% include header.md %}
         <div class="section-timeline">
            <div class="container">
               <div class="timeline_component">
                  <div class="timeline_progress">
                  <div data-w-id="jan2012" class="timeline_progress-bar"></div>
                  </div>   
 {% for post in site.posts %}
                    <div data-w-id="scroll-2" class="timeline_item">
                     <div id="june16-t" class="timeline_left">
                        <div class="timeline_date-text">{{ post.year }}
                             <p> {{post.title}}</p>
                        </div>
                     </div>
                     <div id="june2016" class="timeline_centre">
                        <div class="timeline_circle"></div>
                     </div>
                     {{post.content}}
                  </div>
{% endfor %}
				  <div class="overlay-fade-bottom"></div>
                  <div class="overlay-fade-top"></div>
               </div>
            </div>
         </div>					
{% include footer-widget.md %}
{% include footer.md %}