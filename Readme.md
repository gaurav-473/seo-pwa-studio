How to setup SEO in Pwa-Studio ?

1. You need to setup pwa studio using upward connector below are the useful links

https://magento.github.io/pwa-studio/tutorials/cloud-deploy/#add-required-environment-variables
https://help.nexcess.net/magento-2/how-to-install-venia-storefront-pwa
https://github.com/magento/magento2-upward-connector


2. For crawling of your site you can use https://prerender.io/ or https://github.com/GoogleChrome/rendertron 
   You can setup renderton or prerender on your server. 
   You will get node app url like 
   For renderton https://render-tron.appspot.com/ 
   For prerender.io https://service.prerender.io/
   Now you need to enter this url in magento backend configuration.
   Below are the useful links
   https://github.com/GoogleChrome/rendertron
   https://github.com/prerender/prerender
   https://github.com/GoogleChrome/rendertron/blob/main/docs/deploy.md

Note: 
1. This one will work perfect with magento 2.4 version if you are using below version then you need to made some changes in curl request of upward connector controller.
2. You can also setup this rendered service url in your server configution in that case you have no need to setup upward connector on your server.

For testing the crawler you can use below tools
https://search.google.com/search-console
For testing in chrome you can set googlebot as useragent
https://developers.google.com/web/tools/chrome-devtools/device-mode/override-user-agent
