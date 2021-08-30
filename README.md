# Twig snippet for manipulate numbers

Manipulate field number to add price format depending on the number.
In Euro we need a dot instead of comma for the thousands, depending on the value
we should replace the dots and commas and give the proper format.

Format can come from Drupal (editor) or from API/DB. That's why we need to format
the number. Number shown in the front end differs from the number format in the DB.
