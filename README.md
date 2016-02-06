# scheduler
scheduler-js
html {
	overflow-y:scroll;
}
body {
  padding-top: 10px;
  padding-bottom: 30px;
}

body.hideIframeBodyStyle {
    background-color: #FFFFFF;
}

body.hideIframeBodyStyle .header {
    display: none;
}
/* Header & Navbar */
.header {
    margin-bottom: 80px;
}
.header .navbar {
    min-height: 70px;
    background: rgba(255, 255, 255, 0.9);
    border-bottom: 1px solid #ccc;
}
.header .navbar .navbar-header .navbar-brand {
    font-size: 0px;
    background: url(/img/logo.png) no-repeat left center;
    width: 150px;
    height: 70px;
    background-size: 150px auto;
    margin-left: 0px;
    border-bottom: 0px;
    position: relative;
    z-index: 0;
}
.header .navbar .navbar-right {
    margin-top: 20px;
}
.header .navbar .navbar-right > li > a {
    margin-bottom: -1px;
    color: rgba(60, 60, 60, 0.5);
    background-color: transparent;
    border-bottom: 2px solid transparent;
    transition: all 150ms ease-in-out;
    -webkit-transition: all 150ms ease-in-out;
    -moz-transition: all 150ms ease-in-out;
    -o-transition: all 150ms ease-in-out;
}
.header .navbar .navbar-right > li > a:hover {
    color: #3c3c3c;
    background-color: transparent;
    border-bottom: 2px solid #cebfbf;
}
.header .navbar .navbar-right > li.dropdown {
    margin-top: -1px;
    border: 1px solid transparent;
    border-bottom: 0px;
}
.header .navbar .navbar-right > li.dropdown > a .caret {
    border-top-color: rgba(60, 60, 60, 0.5);
    border-bottom-color: rgba(60, 60, 60, 0.5);
    margin-left: 5px;
}
.header .navbar .navbar-right > li.dropdown.open {
    background-color: #fcfcfc;
    border: 1px solid #dddddd;
    border-bottom: 0px;
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
}
.header .navbar .navbar-right > li.dropdown.open > a {
    color: #3c3c3c;
    border-bottom: 2px solid #cebfbf;
    transition: none;
    -webkit-transition: none;
    -moz-transition: none;
    -o-transition: color 0 ease-in;
}
.header .navbar .navbar-right > li.dropdown.open > a .caret {
    border-top-color: #3c3c3c;
    border-bottom-color: #3c3c3c;
    color: #3c3c3c;
    transition: none;
    -webkit-transition: none;
    -moz-transition: none;
    -o-transition: color 0 ease-in;
}
.header .navbar .navbar-right > li.dropdown .dropdown-menu {
    display: block;
    left: -1px;
    right: auto;
    background-color: #fff;
    border-top: 0px;
    padding: 0px;
    margin-top: 1px;
    padding-bottom: 10px;
}
.header .navbar .navbar-right > li.dropdown .dropdown-menu li a {
    font-size: 13px;
    padding: 4px 15px;
    border: 0px;
}
.header .navbar .navbar-right > li.dropdown .dropdown-menu li a:hover {
    border: 0px;
}
.header .navbar .navbar-right > li.dropdown .dropdown-menu li.dropdown-header {
    padding: 3px 15px;
    font-size: 14px;
    margin: 18px 0px 6px 0px;
    border-bottom: 1px solid #ddd;
}
.header .navbar .navbar-right > li.dropdown .dropdown-menu li.dropdown-header:first-child {
    margin-top: 23px;
}
.header .navbar .navbar-right > li.dropdown .dropdown-menu li:first-child {
    margin-top: 10px;
}
.header .navbar .navbar-right > li.dropdown[state=''] > a {
    cursor: default;
}
.header .navbar .navbar-right > .active > a {
    color: #222222;
    background-color: transparent;
    border-bottom: 2px solid #aa2222;
}
.header .navbar .navbar-right > .active > a:hover {
    color: #222222;
    border-bottom: 2px solid #aa2222;
}
.header .navbar .navbar-right > .active.dropdown > a .caret {
    border-top-color: #222222;
    border-bottom-color: #222222;
}
.header .navbar .navbar-right.dropdown-open > li > a {
    opacity: .5;
}
.header .navbar .navbar-right.dropdown-open > .open > a {
    opacity: .85;
}
.header .navbar .navbar-right.dropdown-open > .open > a:hover {
    opacity: 1;
    color: #000;
}
.header .navbar .navbar-right.dropdown-open > .open[state=''] > a:hover {
    opacity: .85;
    color: #3c3c3c;
}
.header .navbar .navbar-right.dropdown-open > .active > a {
    border-bottom: 2px solid #cebfbf;
}

.container > .navbar-header, .container > .navbar-collapse {
    margin-right: -15px;
    margin-left: 0px;
}


.anchor:before {
  display: block;
  content: "";
  height: 50px;
  margin: -50px 0 0; }

.biking_picture img {
    display: block;
    margin-left: auto;
    margin-right: auto; 
}

.left {
    text-align: left; 
}

.right {
    text-align: right;    
}

.center {
    text-align: center;
}

#chart-current-year {
    max-width: 640px;
    height: 300px;
    display: block;
}

#chart-monthly-average, #chart-history {
    max-width: 640px;
    height: 380px;
    display: block;
}

.row0, .row0 td {
    background-color: #ded7c9; 
}

body {background-color:rgb(224, 224, 224);}


tbody th.sum {
    border-left: 1px solid black; 
}

tfoot th.sum {
    border-top: 1px solid black;
}

table.trip_table {
    width: 100%;
    border-collapse: collapse;
    border: 1px solid #cccccc;
}

table.track_table {
    width: 100%;
}

th.period, td.period {
    width: 85px; 
}

table.trip_table td, table.track_table td {
    vertical-align: top;
}

div.map-wrapper div.olMap {
    width: 100%;
    height: 480px;
    border: 4px #fff solid;    
    box-shadow: 0 0 5px -1px rgba(0, 0, 0, 1);
    width:100%; 
    min-height:100%; border:1px solid black;
}

table.track_table a {
    background: none !important;
}

.datepicker-popup table {
    border-collapse: separate !important;
    border-spacing: 5px !important;
}

.highcharts-tooltip table {
    font-size: 12px;
    min-width: 150px;
    margin-bottom: 0px;
}

#chart-current-year {
    margin-bottom: 10px;
}

.organization-name-col {
	min-width: 250px;
	white-space: nowrap;
}


.organization-icon {
	cursor: pointer;
}

.holiday-download-icon {
	cursor: pointer;
}

.scheduler {
  background-color:#88B5C2 !important;
}

.levelOne {
    background-color: #006DCC;
    color: white;
}

.gridStyle {
    border: 1px solid rgb(212,212,212);
    width: 400px; 
    height: 400px;
}

.levelTwo {
    background-color: #FF8C00;
    color: black;
}

.table .levelOne + .levelTwo {
	display:none;
}

projecttable {
    border-collapse: separate;
    border-spacing: 0 5px;
    padding: 0px;
}
tr td:first-child,
tr th:first-child {
    border-top-left-radius: 6px;
    border-bottom-left-radius: 6px;
}

tr td:last-child,
tr th:last-child {
    border-top-right-radius: 6px;
    border-bottom-right-radius: 6px;
}


.data-table {
    border-collapse: separate;
    padding: 0px;
}

.data-table {
	margin-left: 0px;	
	margin-top:  0px;
}

.data-table thead {
	background-color: #006DCC;
    color: white;	
}

.data-table tbody {
	background-color: white;
}

.data-table th, .data-table td {
	font-size:11px;	
	white-space: nowrap;
}

.data-table th {
	color:#FFF;	
	text-align:left;
}

.data-table tr td:first-child, .data-table tr th:first-child {
	border-top-left-radius: 0px;
	border-bottom-left-radius: 0px;
}

.data-table tr td:last-child, .data-table tr th:last-child {
	border-top-right-radius: 0px;
	border-bottom-right-radius: 0px;
}

.data-table.loading {
	opacity: .5;
	transition: all 300ms ease-in-out;
	-webkit-transition: all 300ms ease-in-out;
  	-moz-transition: all 300ms ease-in-out;
  	-o-transition: all 300ms ease-in-out; 
}

.data-table-container {
  opacity: 1;
  transition: all 500ms ease-in-out;
  -webkit-transition: all 500ms ease-in-out;
  -moz-transition: all 500ms ease-in-out;
  -o-transition: all 500ms ease-in-out;
}

.data-table-container.loading2 {
  opacity: 0;
}


.data-table-container.ng-enter {
  opacity: 0;
}

.data-table-container.ng-enter.ng-enter-active {
  opacity: 1;
}

.data-table-container.ng-leave {
  opacity: 1;
}
.data-table-container.ng-leave.ng-leave-active {
  opacity: 0;
}

.project-table {
    border-collapse: separate;
    padding: 0px;
    width:100%;
    padding-top:20px;
}

 
 
.nested-requirement {
	width:100%;
	padding-left: 50px;
	margin-bottom: 0px;
}

.nested-requirement th{
	background-color:#006DCC;
	color: white;
	font-weight: normal;
}


.nested-requirement td{
	background-color:#EBE8ED; !important;
}

.nested-task-container {
	
}

.nested-task {
	width:100%;
	padding-left: 50px;
}

.nested-task th, .nested-task td {
	
}

.nested-task th {
	background-color:#006DCC;
	color: white;
	font-weight: normal;
}

.nested-task td{
	background-color:#EBE8ED; !important;
}

.nested-task thead {

}

.nested-task-td-cell-container {
	padding: 5px  0px !important ;
	background-color:rgb(224, 224, 224);
	
}


 .nested-requirement td.nested-task-td-cell-container{
	padding: 5px  0px !important ;
	background-color:white !important;
}

.clickableRow {
	cursor: pointer;
}

p, textarea {
    font-variant: small-caps !important;
}


body {
    font-family: Helvetica,Arial;
    font-size: 10pt;
}

ul {
    margin:0;
    padding:0;
}


.main {
    float: left;
    margin-top:5px;
    width:78px;
}

.sub {
    margin:0;
    width:120px;
    background-color: #220630;
    background-image: -webkit-gradient(linear, 0% 0%, 0% 100%, from(#6C1299), to(#220630));
    background-image: -moz-linear-gradient(19% 75% 90deg,#220630, #6C1299)
}

.sub:hover {
    background-color: #450C61;
    background-image: -webkit-gradient(linear, 0% 0%, 0% 100%, from(#8C17C7), to(#450C61));
    background-image: -moz-linear-gradient(19% 75% 90deg,#450C61, #8C17C7)
}

.sub:active {
    background-color: #111;
    background-image: -webkit-gradient(linear, 0% 0%, 0% 100%, from(#666666), to(#111111));
    background-image: -moz-linear-gradient(19% 75% 90deg,#111111, #666666)
}

.btn {
    color:black;
    font-family: Arial, Tahoma, Verdana, FreeSans, sans-serif;
    text-shadow:0 1px 1px rgba(0, 0, 0, 0.25);
    text-decoration: none;
}

.page-panel {
  border-color: #bbb;
}

.page-panel .panel-heading {
  font-size: 22px;
  padding: 15px 25px;
  color: #555;
  font-weight: bold;
  background-color: #E8E8E8;
  border-bottom-color:#bbb;
  margin-bottom:40px;
} 

.panel-body {

}

.stake-group-allocation-matrix .panel-body {
	overflow-x: scroll; 	
}

.project-table-scrollable .panel-body {
	overflow-x: scroll; 	
}

.data-table-project-scrollable  {
	overflow-x: scroll; 	
}

.data-table-project-scrollable .form-control  {
	height:18px;
	padding:2px;
	font-size: 11px;
}


.fullwidth {
    /* inline-block allows the anchor tag to fill
       the entire width of the list item */
    display:inline-block;
    width:100%;
}

.Three-Dee{
font-family: Garamond, serif;
line-height: 1em;
color: #fff9d6;
font-weight:bold;
font-size: 134px;
text-shadow:0px 0px 0 
rgb(231,231,231),1px 1px 0 
rgb(216,216,216),2px 2px 0 
rgb(202,202,202),3px 3px 0 
rgb(187,187,187),4px 4px 0 
rgb(173,173,173),5px 5px 0 
rgb(158,158,158), 6px 6px 0 
rgb(144,144,144),7px 7px 6px 
rgba(0,0,0,0.6),7px 7px 1px 
rgba(0,0,0,0.5),0px 0px 6px rgba(0,0,0,.2);
}

[ng-table-pagination] .ng-table-pager {
      margin-top: 28px;
} 

.spin {
  -webkit-animation: spin 1s infinite linear;
  -moz-animation: spin 1s infinite linear;
  -o-animation: spin 1s infinite linear;
  animation: spin 1s infinite linear;
}

@-moz-keyframes spin {
  from {
    -moz-transform: rotate(0deg);
  }
  to {
    -moz-transform: rotate(360deg);
  }
}

@-webkit-keyframes spin {
  from {
    -webkit-transform: rotate(0deg);
  }
  to {
    -webkit-transform: rotate(360deg);
  }
}

@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
} 

.date-filter .input-group {
	margin-right: 10px;
}

/* Show/Hide */
.show-hide-fade.ng-hide-add, .show-hide-fade.ng-hide-remove {
  -webkit-transition:all linear 0.2s;
  -moz-transition:all linear 0.2s;
  -o-transition:all linear 0.2s;
  transition:all linear 0.2s;
  display:block!important;
}

.show-hide-fade.ng-hide-add.ng-hide-add-active,
.show-hide-fade.ng-hide-remove {
  opacity:0;
}

.show-hide-fade.ng-hide-add,
.show-hide-fade.ng-hide-remove.ng-hide-remove-active {
  opacity:1;
} 

.grid-align {
    text-align: right;
}

.stake-group-allocation-matrix  input[type="text"] {  
      background-color: white;  
      text-align: right;
}  

.stake-group-allocation-matrix  input[type="text"].myFocus {  
     background-color: yellow;  
     text-align: left;
}  

.fielderror {
	background-color: red;
}

.highlight-enter-setup {
    background: red;
}
.highlight-enter-start {
    background: white;
}


.project-table-scrollable  input[type="text"] {  
      background-color: white;  
      text-align: right;
}  

.project-table-scrollable  input[type="text"].myFocus {  
     background-color: yellow;  
     text-align: left;
}  

.modal-dialog {
  width: 90%;
  height: 90%;

}

.modal-body {
  height: 100%;
}

.modal-content {
  height: 100%;
}

.modal-content .close {
position: absolute;
top: 0px;
right: 10px;
color: black;
opacity: 1;
font-size: 30px;
}

.project-treeview .selected {
   background-color: yellow;
}

.project-treeview .nested-task-td-cell-container {
    background-color: transparent;
}

.project-treeview .nested-requirement {
    padding-left:20px;
}

.project-treeview .project-table {
     padding-top:0px;
}

.summarychart {
    padding-left:20px;
    padding-right:10px;

}

.chart div {
  font: 10px sans-serif;
  background-color: steelblue;
  text-align: right;
  padding: 3px;
  margin: 1px;
  color: white;
}

.container-content {
    margin: 10px;
}

.top-buffer {
    margin-top: 8px;
}

.navbar-right-spacing {
    margin-right: 160px;
}

.btn:focus {
    color: #333;
    background-color: #fff;
    border-color: #ccc;
}

.btn.active:focus {
    color: #333;
    background-color: #ebebeb;
    border-color: #adadad;
}

[ng\:cloak], [ng-cloak], .ng-cloak {
    display: none !important;
}

.gantt-timeframe-holiday {
    border: solid 2px black;
    opacity: 0.6;
}

.gantt-row-milestone {
    font-weight: bold;
    vertical-align: middle;
    color: white;
}

div.live-table {
    display: table;
    width: 100%;
}

div.live-row {
    display: table-row;
}

div.live-cell {
    display: table-cell;
    padding: 5px;
    width: 50%;
}

textarea.live-task,
textarea.live-row {
    width: 100%;
    height: 300px;
    font-family: Consolas, "Liberation Mono", Menlo, Courier, monospace;
    font-size: 0.9em;
    color: #333;
}
