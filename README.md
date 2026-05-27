### Μη επιβλεπόμενη μάθηση (unsupervised learning - συνάντηση 14/5/2026)

Αυτός ο φάκελος περιλαμβάνει βασικά notebooks για μη επιβλεπόμενη μάθηση σχετικά με: προετοιμασία και καθαρισμό δεδομένων, ανάλυση με NLP, sentence embeddings, clustering και topic modeling.

---

#### 1. Cleaning (με παραδειγματα από Le Monde Articles & Le Monde Comments)

"Καθαρισμός" datasets. 

- βασικό έλεγχο του dataset
- επιλογή χρήσιμων στηλών
- ήπιο καθαρισμό κειμένου
- αφαίρεση τεχνικών artifacts
- προετοιμασία των άρθρων για επόμενα βήματα NLP

---
#### 2. Sentencize

Αυτό το notebook χωρίζει τα κείμενα σε προτάσεις.

Περιλαμβάνει:
- sentence segmentation
- δημιουργία sentence-level dataset
- έλεγχο κενών ή προβληματικών προτάσεων
- προετοιμασία των προτάσεων για embeddings

Κάθε γραμμή του νέου dataset αντιστοιχεί σε μία πρόταση.

---
#### 3. Clustering

Δοκιμές με semantic clustering στις προτάσεις.

Περιλαμβάνει:
- δημιουργία sentence embeddings
- μείωση διαστάσεων με UMAP
- clustering με HDBSCAN
- έλεγχο outliers
- οπτικοποίηση clusters
- ερμηνεία και τίτλους για clusters

---
#### 4. Topic Modeling

Εδώ εφαρμόζουμε topic modeling σε συλλογή κειμένων με τη μέθοδο Latent Dirichlet Allocation (LDA).

Περιλαμβάνει:
- preprocessing και καθαρισμό κειμένων
- tokenization και αφαίρεση stopwords
- δημιουργία bigrams
- δημιουργία Bag-of-Words corpus
- εκπαίδευση μοντέλου LDA
- αξιολόγηση με coherence και perplexity
- επιλογή αριθμού topics
- οπτικοποιήσεις
