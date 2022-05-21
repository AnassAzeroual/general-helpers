# maps-helper
## Map destination itinéraire  
https://www.google.com/maps/dir/?api=1&destination=33.57715,-7.70516


# Cridit card helper
## hide cedit card middle numbers
const hideCard = (str) => str.replace(
/\b(?:\d{4}[ -]?){3}(?=\d{4}\b)/gm,
'#### #### #### '
);

hideCard('visa 1234 3846 3947 0971');
// visa #### #### #### 0971
