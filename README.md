# Pipeline-di-restauro-per-audio-MusicGen
L'obiettivo del progetto è quello di migliorare la qualità degli audio prodotti da MusicGen, rimuovendo artefatti e rumore e migliorandone la percezione. Le pipeline di restauro proposte sono due: una che prevede l'uso di Demucs + LUFS e un'altra che aggiunge un equalizzatore parametrico (Demucs + EQ + LUFS).
Nelle due cartelle (raw e processed) trovate, rispettivamente, sei campioni (uno per ogni categoria) originali e le loro versioni processate attraverso il secondo modello proposto (Demucs + EQ + LUFS).


La valutazione degli audio avviene in diversi modi: mediante le tre metriche adottate(l'iSNR (Improved Signal-to-Noise Ratio), che misura la riduzione del rumore, la HF ratio (High-Frequencies Ratio), che valuta il recupero di dettagli frequenziali alti, e il miglioramento del contrasto spettrale, che misura la chiarezza generale), mediante i grafici plottati durante l'esecuzione principale (Waveform, Spettrogrammi, Confronto Spettrale) e, infine, ascoltando direttamente i samples.
