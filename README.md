# Meteors
## IoT Μετεωρολογικός Σταθμός με τη χρήση Arduino.
<p>Η Συμμετοχή των μαθητών του 1ου Λυκείου Σερρών στο Διαγωνισμό Ανοιχτών Τεχνολογιών της ΕΛΛΑΚ.</p>
<p>Μπορείτε να παρακολουθείτε την πορεία της ομάδας στο <a href="https://github.com/ntsepelis/Meteors/wiki/%CE%97%CE%BC%CE%B5%CF%81%CE%BF%CE%BB%CF%8C%CE%B3%CE%B9%CE%BF">wiki</a>, όπου διατηρούμε <a href="https://github.com/ntsepelis/Meteors/wiki/%CE%97%CE%BC%CE%B5%CF%81%CE%BF%CE%BB%CF%8C%CE%B3%CE%B9%CE%BF">ημερολόγιο</a>.</p>
<br>

### ΕΙΣΑΓΩΓΗ
<p>Το Arduino είναι ο μικροελεγκτής που έδωσε το έναυσμα για να ξεκινήσει το “κίνημα” του open hardware (ανοιχτό υλικό, συνέχεια του open software – ανοιχτό λογισμικό). Χρησιμοποιώντας μια σειρά από αισθητήρες, ένα εύχρηστο και εύκολο περιβάλλον προγραμματισμού και χαμηλή τιμή, εισάγει του μαθητές στις έννοιες του προγραμματισμού, του αυτοματισμού, της επίλυσης πρακτικών προβλημάτων και της κατασκευής διατάξεων. Οι μαθητές χρησιμοποιώντας τις γνώσεις του σχολείου θα κατασκευάσουν έναν μετεωρολογικό σταθμό με αισθητήρες θερμοκρασίας, υγρασίας, ατμοσφαιρικής πίεσης, βροχόπτωσης. Τα δεδομένα αυτά
<ul>
    <li>θα καταγραφονται σε μονάδα αποθήκευσης</li>
    <li>θα μεταδίδονται μέσω ιστοσελίδας που θα τρέχει στο τοπικό δίκτυο του σχολείου.<br>
        Στη σελίδα αυτή θα μπορεί να συνδεθεί οποιοσδήποτε υπολογιστής αλλά και οποιοδήποτε κινητό.
    </li>
    <li>θα μεταδίδονται στο twitter στο λογιαριασμό: https://twitter.com/MeteorsSerres</li>
</ul>
Οι δύο τελευταίες δυνατότητες εισάγουν τους μαθητές και στην έννοια του ΙοΤ (Internet of Things).</p>
<br>

### ΣΤΟΧΟΙ
<p>Στόχοι του προγράμματος είναι
<ol>
    <li>Η ευαισθητοποίηση των μαθητών σε θέματα</li>
    <ol>
        <li>Περιβάλλοντος</li>
        <li>Ανοιχτού λογισμικού (Open Software)</li>
        <li>Ανοιχτού υλικού (Open Hardware)</li>
    </ol>
    <li>η καλλιέργεια δεξιοτήτων</li>
    <ol>
        <li>επίλυσης προβλημάτων </li>
        <li>υλοποίησης διατάξεων</li>
        <li>προγραμματισμού Η/Υ και μικροελεγκτών</li>
    </ol>
    <li>η καλλιέργεια των μεταξύ τους σχέσεων, μέσω της λειτουργίας σε ομάδες, με διακριτούς, ωστόσο, ρόλους.</li>
</ol>
</p>
<br>

### ΜΕΘΟΔΟΛΟΓΙΑ
<p>Οι στόχοι αυτοί θα υλοποιηθούν με τρίωρες συναντήσεις, μία φορά την εβδομάδα, εκτός σχολικού ωραρίου. Η μέθοδος που θα ακολουθηθεί είναι η ομαδοσυνεργατική.</p>
<p>Οι μαθητές θα χωριστούν σε ομάδας των πέντε ατόμων και θα αναλάβουν την ανάπτυξη ενός τμήματος της διάταξης. Η ενασχόληση αυτή δεν θα περιορίζεται στον προγραμματισμό και την κατασκευή του αλλά και στην ανάδειξη του αντίστοιχου περιβαλλοντικού θέματος που προάγει ή το περιβαλλοντικού προβλήματος που καλείται να λύσει. Με την ολοκλήρωση του έργου της, κάθε ομάδα θα πρέπει να εκπαιδεύσει τις υπόλοιπες στο αντικείμενό της.</p>
<p>Ξεχωριστό ρόλο στην όλη διαδικασία θα έχει η Ομάδα Συντονισμού, που καλείται να οργανώσει και να συντονίσει όλες τις επιμέρους ομάδες για να είναι πετυχημένο το αποτέλεσμα.</p>
<br>

### HARDWARE ΥΛΟΠΟΙΗΣΗΣ
<p>Για την υλοποίηση του έργου θα προμηθευτούμε
    <ul>
    <li>Μικροελεγκτές Arduino (Πιθανότατα 2 μικροελεγτές μιας και ο κώδικας του προγράμματος είναι αρκετά μεγάλος και δεν μπορεί να υπολτηριχθεί από τη μνήμη ενός μόνο μ/Ε)</li>
    <li>Αισθητήρα ΒMP280 (για την μέτρηση Θερμοκρασίας και Ατμοσφαιρικής Πίεσης)</li>
    <li>Αισθητήρα DHT11 (για μέτρηση Υγρασίας)</li>
    <li>0.96" 128X64 LED Οθόνη (για εμφάνιση αποτελεσμάτων)</li>
    <li>Breakout for Micro SD (Μονάδα Αποθήκευσης Μετρήσεων)</li>
    <li>Ehternet Module (για σύνδεση στο δίκτυο και το διαδίκτυο) </li>
    <li>Παρελκόμενα</li>
    </ul>
</p>
<br>

### ΠΑΡΑΔΟΤΕΑ
<p>Τα παραδοτέα του έργου είναι 
    <ul>
    <li>Ο μετεωρολογικός σταθμός</li>
    <li>Αναλυτικός οδηγός λειτουργίας του</li>
    <li>Υλικό από τις εργασίες σύνθεσης / κατασκευής</li>
    <li>Υλικό παρουσίασης</li>
    <li>Ψηφιακό αρχείο καταγραφής μετρήσεων</li>
    <li>Κώδικας προγράμματος</li>
    </ul>
</p>
