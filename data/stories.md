## thanks
* thank
    - utter_noworries
    - utter_anything_else

## bye
* bye
    - utter_bye

## greet
* greet
    - utter_greet

## greet + sales form
* greet
    - utter_greet
* contact_sales
    - sales_form 
    - form{"name": "sales_form"}
    - form{"name": null}  


## sales form
* contact_sales
    - sales_form                   <!--Run the sales_form action-->
    - form{"name": "sales_form"}   <!--Activate the form-->
    - form{"name": null}           <!--Deactivate the form-->
