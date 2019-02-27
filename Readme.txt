step1:

 Copy all content from htmltoplace.html file.

step2:
 Login wordpress Quick Edit pricing page.

step3:
 Replace with this content.

step4:
 Select template pricing and save it.

step5:
Copy style.css from final folder and replace it into child theme.

thats it...


for changing values in table for future,navigation url,tooltip, avaibility 
Just change value in Array.

                              ****Structure of Array****
                avaibility == yes  no or custom. 
                       yes == right mark in table
                       no  == wrong mark in table
for simple text like unlimited put directly text like unlimited or single.


arr=[
futures value
[["futures name", "future url"],           ["futures name","future url"]],
[["lite availibility ","tooltip"],         ["lite availibility ","tooltip"]],
[["small business availibility","tooltip"],["small business availibility ","tooltip"]],
[["business availibility","tooltip"],      ["business availibility ","tooltip"]],
[["premium availibility","tooltip"],       ["premium availibility ","tooltip"]],
[["pro availibility","tooltip"],           ["pro availibility ","tooltip"]],

];


 
 
