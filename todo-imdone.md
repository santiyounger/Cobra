---
computed:
  date: (new Date()).toDateString()
  time: (new Date()).toLocaleTimeString()
  timestamp: (new Date()).toISOString()
template: | # This is the template for new cards that are created in imdone


  <!-- created:${timestamp} -->
  <!--[ Created: {{(new Date(created)).toLocaleString()}} ]-->
links:
  - pack: fab # Can be fab or fas https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use
    icon: fa-twitter # The font-awesome icon to use
    title: Tweet this card
    href: https://twitter.com/intent/tweet?text=${encodedText}%0ATweeted%20with%20@imdoneio
---

-  #TODO:15 fix external link symbol (it causes a space if hidden)
<!-- created:2021-02-17T01:39:09.394Z -->
<!--[ Created: {{(new Date(created)).toLocaleString()}} ]-->


-  #TODO:30 check error in cs code at the end (red arrow with message when clicked)
<!-- created:2021-02-20T16:51:33.830Z -->
<!--[ Created: {{(new Date(created)).toLocaleString()}} ]-->


-  #TODO:10 consider moving code to .org
<!-- created:2021-02-20T16:52:24.068Z -->
<!--[ Created: {{(new Date(created)).toLocaleString()}} ]-->


-  #TODO:40 change right sidebar in light mode
<!-- created:2021-02-20T17:45:08.368Z -->
<!--[ Created: {{(new Date(created)).toLocaleString()}} ]-->

