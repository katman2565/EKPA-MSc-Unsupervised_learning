## Μη επιβλεπόμενη μάθηση (unsupervised learning - συνάντηση 14/5/2026)

Αυτός ο φάκελος περιλαμβάνει βασικά notebooks για μη επιβλεπόμενη μάθηση.
Τα notebooks δείχνουν πώς προετοιμάζουμε τα δεδομένα και πώς προχωράμε σε ανάλυση με NLP, sentence embeddings και clustering.

---

### 1. Cleaning Le Monde Articles & Cleaning Le Monde Comments

Τα notebooks καθαρίζουν τα datasets με τα άρθρα και τα σχόλια της Le Monde.
Περιλαμβάνουν:
- βασικό έλεγχο του dataset
- επιλογή χρήσιμων στηλών
- ήπιο καθαρισμό κειμένου
- αφαίρεση τεχνικών artifacts
- προετοιμασία των άρθρων για επόμενα βήματα NLP

---
### 2. Sentencize

Αυτό το notebook χωρίζει τα κείμενα σε προτάσεις.

Περιλαμβάνει:
- sentence segmentation
- δημιουργία sentence-level dataset
- έλεγχο κενών ή προβληματικών προτάσεων
- προετοιμασία των προτάσεων για embeddings

Κάθε γραμμή του νέου dataset αντιστοιχεί σε μία πρόταση.

---
### 3. Clustering

Αυτό το notebook εφαρμόζει semantic clustering στις προτάσεις.

Περιλαμβάνει:
- δημιουργία sentence embeddings
- μείωση διαστάσεων με UMAP
- clustering με HDBSCAN
- έλεγχο outliers
- οπτικοποίηση clusters
- ερμηνεία και τίτλους για clusters

---
## Προτεινόμενη σειρά χρήσης

1. Cleaning Le Monde Articles  
2. Cleaning Le Monde Comments  
3. Sentencize  
4. Clustering
