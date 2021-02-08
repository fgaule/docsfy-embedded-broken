# docsfy-embedded-broken
Repository used as example for issue reporting regarding embedded code not compiling

Using plugin [docsify-tabs](https://jhildenbiddle.github.io/docsify-tabs/#/) to create tabs. 
The following code sample will work. There will be 3 tabs, one for English, other for French and the last one for Italian.

  <!-- tabs:start -->

  #### ** English **

  Hello!

  #### ** French **

  Bonjour!

  #### ** Italian **

  Ciao!

  <!-- tabs:end -->

When you put the same piece of code inside a file and embedded it by using the `Embed files` features, it doesn't render the tabs: 

[filename](tabs.md ':include :type=markdown')

The expeected behaviour is the have the tabs rendered on both situations. 