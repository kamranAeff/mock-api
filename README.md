# mock-api

> npm -v

> npm install -g json-server

<h2>Usage</h2>

<p>Create a <code>db.json</code> or <code>db.json5</code> file</p>

<div class="highlight highlight-source-json"><pre tabindex="0">{
  <span class="pl-ent">"posts"</span>: [
    { <span class="pl-ent">"id"</span>: <span class="pl-s"><span class="pl-pds">"</span>1<span class="pl-pds">"</span></span>, <span class="pl-ent">"title"</span>: <span class="pl-s"><span class="pl-pds">"</span>a title<span class="pl-pds">"</span></span>, <span class="pl-ent">"views"</span>: <span class="pl-c1">100</span> },
    { <span class="pl-ent">"id"</span>: <span class="pl-s"><span class="pl-pds">"</span>2<span class="pl-pds">"</span></span>, <span class="pl-ent">"title"</span>: <span class="pl-s"><span class="pl-pds">"</span>another title<span class="pl-pds">"</span></span>, <span class="pl-ent">"views"</span>: <span class="pl-c1">200</span> }
  ],
  <span class="pl-ent">"comments"</span>: [
    { <span class="pl-ent">"id"</span>: <span class="pl-s"><span class="pl-pds">"</span>1<span class="pl-pds">"</span></span>, <span class="pl-ent">"text"</span>: <span class="pl-s"><span class="pl-pds">"</span>a comment about post 1<span class="pl-pds">"</span></span>, <span class="pl-ent">"postId"</span>: <span class="pl-s"><span class="pl-pds">"</span>1<span class="pl-pds">"</span></span> },
    { <span class="pl-ent">"id"</span>: <span class="pl-s"><span class="pl-pds">"</span>2<span class="pl-pds">"</span></span>, <span class="pl-ent">"text"</span>: <span class="pl-s"><span class="pl-pds">"</span>another comment about post 1<span class="pl-pds">"</span></span>, <span class="pl-ent">"postId"</span>: <span class="pl-s"><span class="pl-pds">"</span>1<span class="pl-pds">"</span></span> }
  ],
  <span class="pl-ent">"profile"</span>: {
    <span class="pl-ent">"name"</span>: <span class="pl-s"><span class="pl-pds">"</span>typicode<span class="pl-pds">"</span></span>
  }
}</pre>
</div>

> npx json-server --watch db.json

