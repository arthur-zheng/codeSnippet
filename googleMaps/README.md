# How to run
Simply drag index.html into your browser, and search something such as "in n out in us".

# How was it developed
1. This code snippet was developed based on official Google maps examples: 
-Original places search: https://developers.google.com/maps/documentation/javascript/examples/places-searchbox
-Places detail search: https://developers.google.com/maps/documentation/javascript/examples/place-details
2. Based on the two examples. Script first retrieve list of nearby list of places, then retrieve details of each places by using reference-key, calling place-detail API.
3. Using template lib (I used handelerbar.js because it seems to be easy to pick up.) to show data. I wrote mainly this part.

# Difficulties
1. Pickup Google API documents.(spent some time on getUrl() function to get image urls, please see comments)
2. Trying to be looked same to Google existing UI using css styles.

# Guide on review
1. I wrote new scripts/styles inside 3 files: index.html, script.js and style.css.
2. please ignore lib/ since it's third party libs.

Thanks.