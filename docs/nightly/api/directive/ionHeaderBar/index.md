---
layout: "docs_api"
version: "nightly"
versionHref: "/docs/nightly"
path: "api/directive/ionHeaderBar/"

title: "ion-header-bar"
header_sub_title: "Directive in module ionic"
doc: "ionHeaderBar"
docType: "directive"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/angular/directive/headerFooterBar.js#L6'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ion-header-bar



</h1>





Adds a fixed header bar above some content.

Can also be a subheader (lower down) if the 'bar-subheader' class is applied.
See [the header CSS docs](/docs/components/#subheader).

Note: If you use ionHeaderBar in combination with ng-if, the surrounding content
will not align correctly.  This will be fixed soon.








  
<h2 id="usage">Usage</h2>
  
```html
<ion-header-bar align-title="left" class="bar-positive">
  <div class="buttons">
    <button class="button" ng-click="doSomething()">Left Button</button>
  </div>
  <h1 class="title">Title!</h1>
  <div class="buttons">
    <button class="button">Right Button</button>
  </div>
</ion-header-bar>
<ion-content>
  Some content!
</ion-content>
```
  
  
<h2 id="api" style="clear:both;">API</h2>

<table class="table" style="margin:0;">
  <thead>
    <tr>
      <th>Attr</th>
      <th>Type</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    
    <tr>
      <td>
        align-title
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>Where to align the title.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        no-tap-scroll
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>By default, the header bar will scroll the
content to the top when tapped.  Set no-tap-scroll to true to disable this 
behavior.
Avaialble: &#39;left&#39;, &#39;right&#39;, or &#39;center&#39;.  Defaults to &#39;center&#39;.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>

  

  





