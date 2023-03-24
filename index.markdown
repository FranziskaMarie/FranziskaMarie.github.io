---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
date: 2023-03-21 14:00:00 +0100
---

<style type="text/css">
       .model-box {
       position:   relative;
       width:      100%;
       height: 0;
       padding-top:   66.6%; /* This is your aspect ratio */ }

       .model {
       position: absolute;
       top:      0;
       left:     0;
       bottom:   0;
       right:    0;
       width:    100%;
       height:   100%
       }

       .center {
       display: block;
       margin-left: auto;
       margin-right: auto;
       width: 70%;
       height: 70%
}
</style>

<h1>Title</h1>
Little data story about vehicle thefts in San Francisco.

<img src="/assets/calender_plot.png" class='center' width="60%" height="60%" alt="Calender plot of vehicle thefts in San Francisco from 2003-2017">
<embed 
       type="text/html" 
       src="/assets/vehicle_thefts_ratio.html"
       width="1100"
       height="600"
/>

<embed 
       type="text/html" 
       src="/assets/vehicle_thefts_map.html"
       width="1100"
       height="600"
/>
