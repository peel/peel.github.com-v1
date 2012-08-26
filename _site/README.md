# peel.github.com

This repository contains the source code for my personal website & blog based on jekyll.

## Additional features
---
* Accordion
    <ul class="toggle">
      <li class="opened">
        <a href="#">Title goes here</a>
        <a class="open" href="#">open</a>
        <div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean nisl orci, condimentum ultrices consequat eu. Aenean nisl orci, condimentum ultrices consequat eu consectetur conum ultrices.</p>
        </div>
      </li>
      <li>
        <a href="#">Title goes here</a>
        <a class="open" href="#">open</a>
        <div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean nisl orci, condimentum ultrices consequat eu.</p>
        </div>
       </li>
    </ul>

* Tabs
    <ul class="toggle">
      <li>
        <a href="#">Title goes here</a>
        <a class="open" href="#">open</a>
        <div>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean nisl orci, condimentum ultrices consequat eu. Aenean nisl orci, condimentum ultrices consequat eu consectetur conum ultrices.</p>
        </div>
      </li>
      <li>
        <a href="#">Title goes here</a>
        <a class="open" href="#">open</a>
        <div>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean nisl orci, condimentum ultrices consequat eu.</p>
        </div>
      </li>
      <li><a href="#">Title goes here</a>
        <a class="open" href="#">open</a>
        <div>
          <p>Aenean nisl orci, condimentum ultrices consequat eu consectetur conum ultrices.</p>
        </div>
      </li>
 </ul>

* Lists
    <ul class="contentList special">
      <li>Arrow List &#8211; Aenean nisl orci</li>
      <li>Arrow 2 List &#8211; Lorem ipsum dolor</li>
      <li>Circle List &#8211; Consecteteur adipiscing elit</li>
      <li>Arrow List &#8211; Aenean nisl orci</li>
      <li>Star List &#8211; Lorem ipsum dolor</li>
      <li>Plus List &#8211; Consecteteur adipiscing elit</li>
      <li>Dash List &#8211; Lorem ipsum dolor</li>
    </ul>

* Info box
    <div class="textBox">
      <h5>It’s an info box! Your title goes here.</h5>
      <a class="button headed light arrow" href="#" target="_self"><span>Learn More</span></a>
    </div>

* Alert boxes
    <p class="alertBox error">Error &#8211; Your message goes here</p>
    <p class="alertBox success">Success &#8211; Your message goes here</p>
    <p class="alertBox info">Info &#8211; Your message goes here</p>
    <p class="alertBox notice">Notice &#8211; Your message goes here</p>

* Buttons
    <div class="one_half child">
      <a class="button headed light arrow" href="#" target="_self"><span>Learn More</span></a><br /><br />
      <a class="button classic light arrow" href="#" target="_self"><span>Learn more</span></a>
    </div>
    <div class="one_half child">
      <a class="button headed dark arrow" href="#" target="_self"><span>Learn more</span></a><br /><br />
      <a class="button classic dark arrow" href="#" target="_self"><span>Learn more</span></a>
    </div>

* Dropcaps
    <p><span class="dropcap square">D</span>onec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet necvulputate eget, arcu. Donec pede justo.</p>
    <p><span class="dropcap circle">A</span>onec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet necvulputate eget, arcu. Donec pede justo.</p>

* Blockquotes
    <blockquote><span>quote</span>Oonec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet necvul putate eget, arcu. Donec pede justoonec quam felis.  Ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enimpede justo, fringilla vel, aliquet necvulputate. Oonec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.
    </blockquote>

## Rake 
---
rake draft->edit->rake post->rake server to preview->git commit->git push:)
