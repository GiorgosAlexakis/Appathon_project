# Appathon_project
Το project θα περιλαμβάνει τη χρήση του Data Stream που δίνεται από τον MQTT broker και ανάλογα την διαδρομή  των χρηστών (lat-lon) θα επιστρέφουμε την πιθανότητα(Probable,Not likely,None) να έχουν κολλήσει covid λόγω μεγάλης συνάθροισης χρηστών ή επειδή κάποιος χρήστης βρίσκεται θετικός σε covid σε διάστημα 14 ημερών.(πχ.κάποιος χρήστης βρίσκεται θετικός σε covid οπότε εμφανίζουμε σε χρήστες οτι ήρθαν σε πολυ κοντινή επαφή με κρούσμα οπότε πιθανότατα να κόλλησαν covid και οι ίδιοι).Eπίσης,Θα εμφανίζουμε σε εναν χαρτη( με την βοήθεια ενος framework:leafletjs) τις διαδρομές των χρηστών και αναλόγως την πιθανότητα του να έχουν κολλήσει covid θα αλλάζει το χρώμα με το οποίο θα επισημαίνονται(κόκκινο αν έχουν δηλώσει θετικοί στον covid,πράσινο αν δεν έχουν covid και δεν έρχονται πολύ κοντά σε άλλους,πορτοκαλί αν πιθανώς κόλλησαν covid).
