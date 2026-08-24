---
layout: default
comments: false
keywords:

title: Schedule
description: Course schedule and assignment deadlines for the semester. 
buttons:
micro_nav: false
---


## Schedule

**_NOTE: Topics and dates are tentative and subject to change during the semester._**

<div id="myskedj"></div>

<link href="https://unpkg.com/skedj@4.1.0/build/bootstrap-table.css" rel="stylesheet">
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/skedj.js"></script>
<script type="text/javascript">
var url = "https://docs.google.com/spreadsheets/d/e/2PACX-1vTxDhuEFe4jamNT8IGhTn97dpdr_tE3cGM1PKLMRn2PC13nNqh4Cl1HBu3BsCwaPNZHEaos-ggOCmZa/pub?gid=1377680680&single=true&output=csv";

var rowcols = [
                {
                  sheet_row_txt: "First Midterm Exam",
                  color: "#ffe59a"
                },
                {
                  // sheet_row: 26,
                  sheet_row_txt: "Thanksgiving",
                  color: "#d9ebd3"
                },		
                {
                  sheet_row_txt: "Fall Break",
                  color: "#d9ebd3"
                },		      
                {
                  sheet_row_txt: "Election",
                  color: "#d9ebd3"
                },     
                {
                  sheet_row_txt: "No Class",
                  color: "#d9ebd3"
                },                                       
                {
                  sheet_row_txt: "Second Midterm Exam",
                  color: "#ffe59a"
                },
                {
                  sheet_row_txt: "Recitation",
                  color: "#e8f2fc"
                }                			
              ];
console.log(rowcols);
Skedj(url, "myskedj", {
    columns_to_skip: ["Recitation Lead", "Recitation", "Travel Schedule"],
    special_row_colors: rowcols
});
</script>
