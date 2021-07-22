---
layout: "lezione"
lang: "it"
title: "Che cos'è LaTeX e come funziona"
description: "Questa lezione spiega le basi di che cos'è LaTeX e come funziona in relazione ai comuni elaboratori di testo quali Microsoft Word e LibreOffice Writer."
toc-anchor-text: "Nozioni di base su LaTeX"
toc-description: "Che cos'è LaTeX e come funziona."
---

# Nozioni di base su LaTeX

<span
  class="summary">Questa lezione spiega le basi di che cos'è LaTeX e come funziona in relazione ai comuni elaboratori di testo quali Microsoft Word e LibreOffice Writer.</span>

A differenza dei comuni elaboratori di testo come Microsoft Word o LibreOffice Writer, LaTeX di solito non fornisce il concetto di WYSIWYG ('What You See Is What You Get') ossia 'Quello Che Vedi È Quello Che Ottieni'. Con LaTeX si prende del semplice testo e lo si arricchisce con del markup. Questo markup fornisce a LaTeX il significato logico di certi elementi del testo, in modo simile a come fa HTML.

Si consideri per esempio l'elemento `<h2>` che indica una nuova sezione in un documento HTML.
Anche LaTeX ha un comando apposito per soddisfare questa necessità; in questo caso si userebbe il comando `\section`.

## Il flusso di lavoro LaTeX

Siccome i file LaTeX non sono il documento stesso, ma piuttosto istruzioni che definiscono come dovrebbe essere ogni parte del documento, normalmente non devi consegnare al lettore il tuo file LaTeX. Invece, dopo aver scritto il tuo file _sorgente_ LaTeX, esegui LaTeX sul file (usando usando per esempio un programma chiamato `pdflatex`) per produrre un file PDF. Questo PDF  è ciò che fornirete ai vostri lettori.

Ci sono vari modi diversi con cui descrivere questo processo. Siccome usare LaTeX
è un po' come programmare, spesso si usa il termine 'compilare' il tuo documento, sebbene
'impaginare' sia più accurato.

## Cmpilazione multipla di LaTeX

Per i documenti semplici, è sufficiente compilare il proprio file una sola volta per ottenere l'intero PDF. Ma una volta che si iniziano ad aggiungere elementi più complicati, come riferimenti incrociati, citazioni, figure e tabelle dei contenuti, potrebbe essere necessario eseguire LaTeX più più di una volta. Te lo diremo quando sarà il caso.

## LaTeX o pdfLaTeX o ...

Nella [prossima lezione](lesson-02), vedremo che LaTeX non è un programma unico. Per mantenere le cose semplici, ci concentreremo su un particolare programma LaTeX, pdfLaTeX, per creare i tuoi PDF. Più avanti nel corso, daremo un'occhiata ad altri programmi, e capirai perché potresti volerli usare.
