# Solution?


# Luke Melia & Yapp Labs
<iframe width="560" height="315" src="//www.youtube.com/embed/QZVYP3cPcWQ" frameborder="0" allowfullscreen></iframe>


# Lightning Fast Deployments

1. Build On CI or Dev <!-- .element: class="fragment" data-fragment-index="2" -->
2. Fingerprint build files <!-- .element: class="fragment" data-fragment-index="3" -->
3. Upload to S3 or Flat File Host <!-- .element: class="fragment" data-fragment-index="4" -->
4. Tell server current index.html <!-- .element: class="fragment" data-fragment-index="5" -->
5. Server stashes index.html in Cache <!-- .element: class="fragment" data-fragment-index="6" -->


# In Action

1. User requests index page <!-- .element: class="fragment" data-fragment-index="2" -->
2. Server finds cached index.html <!-- .element: class="fragment" data-fragment-index="3" -->
3. Server inserts any template variables for the user <!-- .element: class="fragment" data-fragment-index="4" -->
4. Client is directed to assets on S3 <!-- .element: class="fragment" data-fragment-index="5" -->
