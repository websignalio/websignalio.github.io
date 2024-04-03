# FAQ
## Q. How do I prevent checking traffic showing in Google Analytics?

This one is pretty simple to setup but you need to follow a few steps.
1. All traffic from our system sends the requests using a HTTP Header User-Agent "websignal-checker".
2. Using this value you can exclude the traffic from Google Analytics by using a filter.
