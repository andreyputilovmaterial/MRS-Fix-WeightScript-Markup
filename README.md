# MRS-Fix-WeightScript-Markup
The purpose of this script is to provide code that modifies WeightReports from weight scripts and fixes layout issues.

Why do we need it? The layout is very broken, it makes it hard to work with reports in automnated way.

The code here is super simple. It's not a program, it is rather a code snippet. But I'll keep it as a repository to have things organized my way.

Basically, the code here is doing minimal simple replacements with regexps changeing &lt;body&gt; and &lt;html&gt; tags to a different way, because they do randomly appear in the middle of the page.