<h1>Eslint Setup</h1>

<p>You might like them - or you might not. Don't worry you can always change them.</p>

<h2>Local / Per Project Install</h2>
<ol>
<li>
<p>If you don't already have a <code>package.json</code> file, create one with <code>npm init</code>.</p>
</li>
<li>
<p>Then we need to install everything needed by the config:</p>
</li>
</ol>
<pre><code>npx install-peerdeps --dev eslint-config-halo-lab
</code></pre>
<ol start="3">
<li>
<p>You can see in your package.json there are now a big list of devDependencies.</p>
</li>
<li>
<p>Create a <code>.eslintrc</code> file in the root of your project's directory (it should live where package.json does). Your <code>.eslintrc</code> file should look like this:</p>
</li>
</ol>
<div class="highlight highlight-source-json"><pre>{
  <span class="pl-s"><span class="pl-pds">"</span>extends<span class="pl-pds">"</span></span>: [
    <span class="pl-s"><span class="pl-pds">"</span>halo-lab<span class="pl-pds">"</span></span>
  ]
}</pre></div>

## Status and contribution
The project is supported by Halo lab development team, we're not working on it regularly, but trying to invest in it when we have time between clients' project. <br />
Though, feel free to open issues and you're very welcome to contribute. 
 <br />
  <br />
<a href="https://www.halo-lab.com/?utm_source=github-brifinator-3000">
    <img src="http://api.halo-lab.com/wp-content/uploads/dev_halo.svg" alt="Developed in Halo lab" height="60">
</a>
