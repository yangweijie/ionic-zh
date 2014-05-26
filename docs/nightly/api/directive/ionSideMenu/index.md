---
layout: "docs_api"
version: "nightly"
versionHref: "/docs/nightly"
path: "api/directive/ionSideMenu/"

title: "ion-side-menu"
header_sub_title: "Directive in module ionic"
doc: "ionSideMenu"
docType: "directive"
---

<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic/edit/master/js/angular/directive/sideMenu.js#L1'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  ion-side-menu



</h1>





A container for a side menu, sibling to an <a href="/docs/nightly/api/directive/ionSideMenuContent/"><code>ionSideMenuContent</code></a> directive.








  
<h2 id="usage">Usage</h2>
  
```html
<ion-side-menu
  side="left"
  width="myWidthValue + 20"
  is-enabled="shouldLeftSideMenuBeEnabled()">
</ion-side-menu>
```
For a complete side menu example, see the
<a href="/docs/nightly/api/directive/ionSideMenus/"><code>ionSideMenus</code></a> documentation.
  
  
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
        side
        
        
      </td>
      <td>
        
  <code>string</code>
      </td>
      <td>
        <p>Which side the side menu is currently on.  Allowed values: &#39;left&#39; or &#39;right&#39;.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        is-enabled
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>boolean</code>
      </td>
      <td>
        <p>Whether this side menu is enabled.</p>

        
      </td>
    </tr>
    
    <tr>
      <td>
        width
        
        <div><em>(optional)</em></div>
      </td>
      <td>
        
  <code>number</code>
      </td>
      <td>
        <p>How many pixels wide the side menu should be.  Defaults to 275.</p>

        
      </td>
    </tr>
    
  </tbody>
</table>

  

  





