# MPower Robots

This module allows you to have a store-specific content of ´robots.txt´.  

Save a desired content of ´robots.txt´ as a config under the following path: ´'mpower_robots/robots/content'´.

If your webwerver is configured to serve static files first please make sure that there is no file ´robots.txt´ so Magento can serve the request. It is higly recommended to activate all kind of cache types supported by Magento  (e.g. config cache, block cache, FPC or Varnish). If possible please add additional layer of caching (e.g. Varnish) in a front of Magento, so an expensive Magento's application stack is not build on each request. 
