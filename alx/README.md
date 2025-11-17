## Custom Turbowarp

Το έργο αυτό είναι ένα τροποποιημένο Turbowarp το οποίο επιτρέπει συνδέσεις μέσω Serial ώστε να υπάρχει **online επικοινωνία** με μια σειρά από μικροεπεξεργαστές όπως Arduino, Microbit κλπ.

# Χρήση

0. Κατεβάζεις από τα [releases](https://github.com/ale3andro/turbowarp_alx/releases) την τελευταία έκδοση της εφαρμογής για το λειτουργικό σου σύστημα.

1. Παίρνεις το αρχείο [userscript.js](./userscript.js) (περιέχει το πρόσθετο για το κιτ S1) και το αντιγράφεις μέσα στον κατάλληλο φάκελο για το ΛΣ σου.

πχ για **Ubuntu/Linux** το αρχείο πρέπει να μπει μέσα στον φάκελο

```
~/.config/turbowarp-desktop/
```

για Windows το παραπάνω αρχείο πρέπει να μπει μέσα στον φάκελο

```
%APPDATA%/turbowarp-desktop
```

Για να βρεις με σιγουριά τον φάκελο, μπορείς να κάνεις κλικ στο εικονίδιο "?" στην πάνω δεξιά γωνία της εφαρμογής, 

![questionmark_image](./img/questionmark_image.png)

και μετά να επιλέξεις το "Desktop Settings" 

![desktop_settings_image](./img/desktop_settings_image.png)

και τέλος το "Open User Data"

![open_user_data_image](./img/pen_user_data_image.png)

Ξεκινάς την εφαρμογή turbowarp και το πρόσθετο / τα πρόσθετα πρέπει να είναι ήδη φορτωμένα!

![extension_loaded](./img/extension_loaded.png)

Όταν γίνει κάποια αναβάθμιση στο πρόσθετο / στα πρόσθετα, αρκεί να ενημερωθεί το αρχείο [userscript.js](./userscript.js) και όχι ολόκληρη η εφαρμογή.

2. Φλασάρισμα του S1 με [αυτόν τον Arduino κώδικα](https://github.com/ale3andro/turbowarp_alx/blob/main/alx/s1-arduino.ino) από το Arduino IDE. Το φλασάρισμα γίνεται μόνο μια φορά, εφόσον δεν φορτωθεί κάτι άλλο στο Arduino. (ΣΗΜΕΙΩΣΗ: Πριν το φλασάρισμα πρέπει να εγκατασταθούν οι βιβλιοθήκες **DHT11** και **Adafruit_NeoPixel** μέσα από το Arduino IDE).

Καλή διασκέδαση!

## Χρήσιμος σύνδεσμος

<a href="https://base64.guru/converter/encode/text" target="_blank">Base64 encode</a>