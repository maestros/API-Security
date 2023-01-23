What's Next For Developers
==========================

Η εργασία δημιουργίας και συντήρησης ασφαλούς λογισμικού καθώς και η επιδιόρθωση αυτού είναι δύσκολη υπόθεση. 
Το ίδιο ισχύει και για τα APIs.

Πιστεύουμε ότι η εκπαίδευση και η ευαισθητοποίηση είναι βασικοί παράγοντες για τη δημιουργία ασφαλούς λογισμικού. 
Όλα τα άλλα που απαιτούνται για την επίτευξη του στόχου, εξαρτώνται από τη δημιουργία και τη χρήση επαναλαμβανόμενων
διαδικασιών ασφαλείας και τυπικών ελέγχων ασφαλείας.

Το OWASP διαθέτει πολλούς δωρεάν και ανοιχτούς πόρους για την αντιμετώπιση της ασφάλειας από την αρχή του έργου. 
Επισκεφτείτε τη σελίδα OWASP Projects [OWASP Projects page][1] για μια ολοκληρωμένη λίστα με τα διαθέσιμα έργα.

| | |
|-|-|
| **Εκπαίδευση** | Μπορείτε να ξεκινήσετε να διαβάζετε το [υλικό του OWASP Education Project][2] ανάλογα με το επάγγελμα και το ενδιαφέρον σας. Για πρακτική μάθηση, προσθέσαμε το **crAPI** - **C**ompletely **R**idiculous **API** στον [οδικό μας χάρτη (roadmap)][3]. Εν τω μεταξύ, μπορείτε να εξασκηθείτε στο WebAppSec χρησιμοποιώντας το [OWASP DevSlop Pixi Module][4], μια ευάλωτη υπηρεσία WebApp και API που έχει σκοπό να διδάξει στους χρήστες πώς να δοκιμάζουν σύγχρονες εφαρμογές ιστού και API για ζητήματα ασφάλειας και πώς να γράφουν πιο ασφαλή API στο μέλλον. Μπορείτε επίσης να παρακολουθήσετε εκπαιδευτικές συνεδρίες του [Συνεδρίου OWASP AppSec][5] ή να [εγγραφείτε στο τοπικό σας τμήμα][6].
| **Απαιτήσεις ασφαλείας** | Η ασφάλεια πρέπει να είναι μέρος κάθε έργου (project) από την αρχή. Όταν βρίσκεστε στο στάδιο της εξαγωγής απαιτήσεων (requirements elicitation), είναι σημαντικό να ορίσετε τι σημαίνει "ασφαλές" για το έργο σας. Το OWASP συνιστά να χρησιμοποιείτε το [Πρότυπο επαλήθευσης ασφάλειας εφαρμογών OWASP (ASVS)][7] ως οδηγό για τον καθορισμό των απαιτήσεων ασφαλείας. Εάν αναθέτετε σε εξωτερικού συνεργάτες (outsourcing), εξετάστε το [Παράρτημα σύμβασης ασφαλούς λογισμικού OWASP][8], το οποίο θα πρέπει να προσαρμοστεί σύμφωνα με την τοπική νομοθεσία και τους κανονισμούς της.|
| **Αρχιτεκτονική ασφαλείας** | Η ασφάλεια θα πρέπει να λαμβάνεται υπόψην σε όλα τα στάδια του έργου. Οι [καταγραφές Πρόληψης OWASP (OWASP Prevention Cheat Sheets)][9] είναι ένα καλό σημείο εκκίνησης για καθοδήγηση σχετικά με τον τρόπο σχεδιασμού ασφάλειας κατά τη φάση της αρχιτεκτονικής. Μεταξύ πολλών άλλων, θα βρείτε την καταγραφή [REST Security Cheat Sheet][10] και την καταγραφή [REST Assessment Cheat Sheet][11].|
| **Τυπικοί έλεγχοι ασφαλείας** | Adopting Standard Security Controls reduces the risk of introducing security weaknesses while writing your own logic. Despite the fact that many modern frameworks now come with built-in standard effective controls, [OWASP Proactive Controls][12] gives you a good overview of what security controls you should look to include in your project. OWASP also provides some libraries and tools you may find valuable, such as validation controls. |
| **Κύκλος ζωής ασφαλούς ανάπτυξης λογισμικού** | You can use the [OWASP Software Assurance Maturity Model (SAMM)][13] to improve the process when building APIs. Several other OWASP projects are available to help you during the different API development phases e.g., the [OWASP Code Review Project][14]. |

[1]: https://www.owasp.org/index.php/Category:OWASP_Project
[2]: https://www.owasp.org/index.php/OWASP_Education_Material_Categorized
[3]: https://www.owasp.org/index.php/OWASP_API_Security_Project#tab=Road_Map
[4]: https://devslop.co/Home/Pixi
[5]: https://www.owasp.org/index.php/Category:OWASP_AppSec_Conference
[6]: https://www.owasp.org/index.php/OWASP_Chapter
[7]: https://www.owasp.org/index.php/Category:OWASP_Application_Security_Verification_Standard_Project
[8]: https://www.owasp.org/index.php/OWASP_Secure_Software_Contract_Annex
[9]: https://www.owasp.org/index.php/OWASP_Cheat_Sheet_Series
[10]: https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/REST_Security_Cheat_Sheet.md
[11]: https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/REST_Assessment_Cheat_Sheet.md
[12]: https://www.owasp.org/index.php/OWASP_Proactive_Controls#tab=OWASP_Proactive_Controls_2018
[13]: https://www.owasp.org/index.php/OWASP_SAMM_Project
[14]: https://www.owasp.org/index.php/Category:OWASP_Code_Review_Project