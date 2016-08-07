[![StackShare](http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](http://stackshare.io/grozip/grozip)

# configfiles

# How to Deploy OpenSearch
1. Put the opensearch.xml in your website's root directory or whereever you want, it must be accesible from browser. This XML Document is your OpenSearch description document. Ref: http://www.opensearch.org/Specifications/OpenSearch/1.1
2. Add this at the end of all meta tags in your `<head>` like this: 

`<link rel="search" type="application/opensearchdescription+xml" title="Search MyWebsiteName" href="https://MyWebsiteName.com/opensearch.xml" />`

# How to Deploy nginx_website_root.conf 

1. Copy the file to website's root directory
2. Rename the file to "nginx.conf"
3. Restart NGINX
