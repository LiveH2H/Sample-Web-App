# LiveH2H Meeting Plugin
Included is a sample web application calling Instant Meeting and Join meeting API's that could be applied to any website :D

.meeting-container - The most outer container of the plugin defaults to a black background

.meeting-container ul.tab - Tabs switch “Instant” or “Join” tabs at the top of container

.meeting-container .tabcontent - Form styles for “Instant” and “Join” meeting

.meeting-container p - Styles of the paragraph text 

#widgetFailureMessage - Styles of the failure message

.meeting-container input - Styles of individual form elements 
 
.meeting-container button - Style of “Meet Now” button

p.meeting-containerline - The underline underneath the text “Instant”  

p.meeting-containerlinejoin - The underline underneath the text “Instant”  

.meeting-container ul.tab li a:hover - The style of the hover effect

.meeting-container p a - Style of the hyperlink 


.meeting-container button:hover - Styles for the button’s hover effect



This is the mobile styles 


@media only screen and (max-width: 768px){
    
    .meeting-container {
        width: 80%;
    }
    .meeting-container ul.tab {
        width: 70%;
    }
}

@media only screen and (max-width: 420px){
    .meeting-container ul.tab {
        width: 100%;
    }
    .meeting-container {
        width: 100%;
    }
    p.meeting-containerline {
        margin-left: 19px!important;
        margin-top: -10px!important;
        text-align: left;
    }
}






