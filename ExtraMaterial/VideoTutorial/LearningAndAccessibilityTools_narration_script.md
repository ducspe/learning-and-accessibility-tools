# Narration script (v6): Ideas and Tools for Creating Accessible Research and Educational Material

Standalone version: no references to a specific event. Each language is narrated from its own text, with its own pacing.

| Narration | Voice (Piper, local) | Duration |
|---|---|---|
| English | `en_US-hfc_female-medium` | 5:30.5 |
| German | `de_DE-thorsten-high` | 5:54.2 |
| Romanian | `ro_RO-mihai-medium` | 6:32.8 |

Timestamps show when each sentence starts in the English / German / Romanian video. **[highlight]** marks sentences during which part of the slide is spotlighted. Pronunciation hints (e.g. LaTeX → "Lah-tek" / "Latec") are used for the audio only; subtitles keep the real spelling.

## Slide 1: Title

**1.** `0:00.9 / 0:00.8 / 0:00.8` **[highlight]**
- EN: Welcome. This short tutorial brings together practical examples of ideas and tools for creating accessible research and educational material.
- DE: Willkommen. Dieses kurze Tutorial fasst praktische Beispiele für Ideen und Werkzeuge zusammen, mit denen sich zugängliche Forschungs- und Lehrmaterialien erstellen lassen.
- RO: Bun venit. Acest scurt tutorial reunește exemple practice de idei și instrumente pentru crearea de materiale de cercetare și educaționale accesibile.

**2.** `0:10.3 / 0:10.8 / 0:11.3`
- EN: The aim is to make research and teaching material easier to create, easier to understand, and easier to revisit.
- DE: Ziel ist es, Forschungs- und Lehrmaterial leichter erstellen, leichter verstehen und leichter wieder aufgreifen zu können.
- RO: Scopul este ca materialele de cercetare și de predare să fie mai ușor de creat, mai ușor de înțeles și mai ușor de revăzut.

**3.** `0:18.2 / 0:17.9 / 0:19.4`
- EN: The presentation also demonstrates its own approach: the same slides and speaker notes can guide a live presenter or, as here, an AI-generated tutorial.
- DE: Die Präsentation demonstriert zugleich ihren eigenen Ansatz: Dieselben Folien und Sprechernotizen können eine vortragende Person leiten oder, wie hier, ein KI-generiertes Tutorial.
- RO: Prezentarea își demonstrează și propria abordare: aceleași slide-uri și note ale vorbitorului pot ghida un prezentator sau, ca aici, un tutorial generat cu AI.

## Slide 2: LaTeX Formula Generator

**4.** `0:29.0 / 0:29.0 / 0:32.2` **[highlight]**
- EN: The first tool is a LaTeX formula generator.
- DE: Das erste Werkzeug ist ein LaTeX-Formelgenerator.
- RO: Primul instrument este un generator de formule LaTeX.

**5.** `0:32.4 / 0:32.3 / 0:36.1`
- EN: Instead of remembering LaTeX syntax, you describe the equation in ordinary language.
- DE: Statt sich die LaTeX-Syntax zu merken, beschreiben Sie die Gleichung in normaler Sprache.
- RO: În loc să rețineți sintaxa LaTeX, descrieți ecuația în limbaj obișnuit.

**6.** `0:37.9 / 0:37.4 / 0:41.4` **[highlight]**
- EN: Here, the prompt at the bottom left asks for the integral of f of x, where f of x is x to the fourth power plus three.
- DE: Hier fragt der Prompt unten links nach dem Integral von f von x, wobei f von x gleich x hoch vier plus drei ist.
- RO: Aici, promptul din stânga jos cere integrala lui f de x, unde f de x este x la puterea a patra plus trei.

**7.** `0:45.3 / 0:44.3 / 0:49.7` **[highlight]**
- EN: The assistant inserts the matching LaTeX code into the document, and you can choose to keep or undo the change.
- DE: Der Assistent fügt den passenden LaTeX-Code in das Dokument ein, und Sie können die Änderung behalten oder rückgängig machen.
- RO: Asistentul inserează codul LaTeX corespunzător în document, iar dumneavoastră puteți alege să păstrați sau să anulați modificarea.

**8.** `0:52.2 / 0:51.6 / 0:58.2` **[highlight]**
- EN: On the right is the compiled result: f of x equals x to the fourth plus three, and its integral, x to the fifth over five, plus three x, plus C.
- DE: Rechts sehen Sie das kompilierte Ergebnis: f von x gleich x hoch vier plus drei, und das Integral, x hoch fünf durch fünf, plus drei x, plus C.
- RO: În dreapta este rezultatul compilat: f de x egal cu x la puterea a patra plus trei, iar integrala sa, x la puterea a cincea supra cinci, plus trei x, plus C.

**9.** `1:02.6 / 1:01.4 / 1:11.4` **[highlight]**
- EN: This example uses OpenAI's Prism, linked at the bottom of the slide.
- DE: Dieses Beispiel nutzt Prism von OpenAI, unten auf der Folie verlinkt.
- RO: Acest exemplu folosește Prism de la OpenAI, cu linkul în partea de jos a slide-ului.

**10.** `1:07.1 / 1:06.2 / 1:17.9` **[highlight]**
- EN: Whatever the tool, always check that the generated equation and notation match the mathematics you intended.
- DE: Unabhängig vom Werkzeug sollten Sie immer prüfen, ob die erzeugte Gleichung und Notation der beabsichtigten Mathematik entsprechen.
- RO: Indiferent de instrument, verificați întotdeauna că ecuația și notația generate corespund matematicii pe care ați avut-o în vedere.

> **Flags for review**
> - The screenshot interface is in German ("Werkzeuge", "Kompiliere", "Alles behalten"); not narrated.

## Slide 3: Claude Videos Anchored in Presentation Slides

**11.** `1:14.2 / 1:14.5 / 1:27.2` **[highlight]**
- EN: Next: creating videos with Claude, anchored in presentation slides.
- DE: Als Nächstes: Videos mit Claude erstellen, verankert in Präsentationsfolien.
- RO: Urmează: crearea de videoclipuri cu Claude, ancorate în slide-urile prezentării.

**12.** `1:18.9 / 1:19.3 / 1:33.4` **[highlight]**
- EN: Start with your own slides. They define the content and the sequence, and act as the ground truth that keeps the video focused on the subject matter.
- DE: Beginnen Sie mit Ihren eigenen Folien. Sie legen Inhalt und Reihenfolge fest und dienen als verlässliche Grundlage, die das Video beim Thema hält.
- RO: Începeți cu propriile slide-uri. Ele definesc conținutul și succesiunea și servesc drept reper care menține videoclipul concentrat pe subiect.

**13.** `1:27.7 / 1:28.1 / 1:43.1` **[highlight]**
- EN: Writing your own narrative anchors the AI agent and helps to avoid hallucinations.
- DE: Ein eigener Erzählstrang verankert den KI-Agenten und hilft, Halluzinationen zu vermeiden.
- RO: Propria narațiune ancorează agentul AI și ajută la evitarea halucinațiilor.

**14.** `1:33.1 / 1:33.7 / 1:48.8` **[highlight]**
- EN: Speaker notes then supply the explanations, for you as the presenter and as guidance for the AI.
- DE: Die Sprechernotizen liefern dann die Erklärungen, für Sie als vortragende Person und als Leitfaden für die KI.
- RO: Notele vorbitorului oferă apoi explicațiile, pentru dumneavoastră ca prezentator și ca ghid pentru AI.

**15.** `1:38.7 / 1:40.4 / 1:56.0`
- EN: With the slides and notes, Claude can use narration and video tools to assemble a complete tutorial, like this one.
- DE: Mit Folien und Notizen kann Claude Sprach- und Videowerkzeuge nutzen, um ein vollständiges Tutorial zusammenzustellen, so wie dieses.
- RO: Pe baza slide-urilor și a notelor, Claude poate folosi instrumente de narațiune și video pentru a asambla un tutorial complet, ca acesta.

**16.** `1:45.8 / 1:48.3 / 2:05.1` **[highlight]**
- EN: For the voice, you can choose an open-source voice model, as in this video, or a service such as ElevenLabs for a more natural voice with better intonation.
- DE: Als Stimme können Sie ein Open-Source-Stimmmodell wählen, wie in diesem Video, oder einen Dienst wie ElevenLabs für eine natürlichere Stimme mit besserer Intonation.
- RO: Pentru voce, puteți alege un model de voce open-source, ca în acest videoclip, sau un serviciu precum ElevenLabs, pentru o voce mai naturală, cu o intonație mai bună.

**17.** `1:55.1 / 1:57.2 / 2:16.4` **[highlight]**
- EN: You could even clone your own voice. That is optional, and a question worth discussing.
- DE: Sie könnten sogar Ihre eigene Stimme klonen. Das ist optional und eine Frage, über die es sich zu diskutieren lohnt.
- RO: Ați putea chiar să vă clonați propria voce. Este opțional și ridică o întrebare care merită discutată.

**18.** `2:00.9 / 2:04.2 / 2:23.5` **[highlight]**
- EN: You can also ask for subtitles in different languages, for more inclusion and accessibility.
- DE: Sie können auch Untertitel in verschiedenen Sprachen anfordern, für mehr Inklusion und Barrierefreiheit.
- RO: Puteți cere și subtitrări în diferite limbi, pentru mai multă incluziune și accesibilitate.

**19.** `2:06.4 / 2:10.6 / 2:29.2` **[highlight]**
- EN: On the right are example videos made this way, on AlphaFold 2, diffusion, and tokenization, available at the link below.
- DE: Rechts sehen Sie Beispielvideos, die so entstanden sind, zu AlphaFold 2, Diffusion und Tokenisierung, abrufbar über den Link unten.
- RO: În dreapta sunt exemple de videoclipuri realizate astfel, despre AlphaFold 2, difuzie și tokenizare, disponibile la linkul de mai jos.

**20.** `2:14.3 / 2:19.0 / 2:38.5`
- EN: Before publishing, review the narration, the visuals, and the subtitles.
- DE: Prüfen Sie vor der Veröffentlichung die Sprachausgabe, die Visualisierungen und die Untertitel.
- RO: Înainte de publicare, verificați narațiunea, elementele vizuale și subtitrările.

> **Flags for review**
> - "like this one" (the video being an example of the approach) is an addition to the notes.

## Slide 4: Using Video Transcripts for References

**21.** `2:19.5 / 2:25.2 / 2:44.9` **[highlight]**
- EN: The third idea: using video transcripts for references.
- DE: Die dritte Idee: Videotranskripte als Referenz nutzen.
- RO: A treia idee: folosirea transcrierilor video pentru referințe.

**22.** `2:23.8 / 2:29.1 / 2:50.2` **[highlight]**
- EN: Long recorded lectures, like this one on machine learning for protein structure prediction, are hard to search by scrubbing through them.
- DE: Lange aufgezeichnete Vorlesungen, wie diese über maschinelles Lernen zur Vorhersage von Proteinstrukturen, lassen sich durch bloßes Vorspulen nur schwer durchsuchen.
- RO: Prelegerile lungi înregistrate, precum aceasta despre învățarea automată pentru predicția structurii proteinelor, sunt greu de căutat doar derulând prin ele.

**23.** `2:31.4 / 2:38.5 / 3:00.3` **[highlight]**
- EN: The lecture is linked at the top left of the slide.
- DE: Die Vorlesung ist oben links auf der Folie verlinkt.
- RO: Linkul către prelegere se află în stânga sus pe slide.

**24.** `2:34.7 / 2:41.8 / 3:04.4` **[highlight]**
- EN: On YouTube, you can open the transcript with the Show transcript button below the video.
- DE: Auf YouTube öffnen Sie das Transkript über die Schaltfläche „Show transcript“ unter dem Video.
- RO: Pe YouTube, puteți deschide transcrierea cu butonul „Show transcript” de sub videoclip.

**25.** `2:40.0 / 2:47.3 / 3:09.9` **[highlight]**
- EN: It opens a panel where every line of spoken text is linked to a timestamp.
- DE: Es öffnet sich ein Bereich, in dem jede Zeile des gesprochenen Textes mit einem Zeitstempel verknüpft ist.
- RO: Se deschide un panou în care fiecare rând de text rostit este legat de un marcaj de timp.

**26.** `2:44.6 / 2:53.3 / 3:16.0` **[highlight]**
- EN: Give an AI assistant the video's URL and ask it to read the transcript and return the timestamp of a specific explanation. You can also supply the transcript directly.
- DE: Geben Sie einem KI-Assistenten die URL des Videos und bitten Sie ihn, das Transkript zu lesen und den Zeitstempel einer bestimmten Erklärung zu nennen. Sie können das Transkript auch direkt bereitstellen.
- RO: Dați unui asistent AI adresa URL a videoclipului și cereți-i să citească transcrierea și să indice marcajul de timp al unei anumite explicații. Puteți furniza și transcrierea direct.

**27.** `2:54.5 / 3:04.8 / 3:29.0`
- EN: Automatic transcripts can contain errors, so watch the actual passage and check its context before citing or sharing it.
- DE: Da automatische Transkripte Fehler enthalten können, sollten Sie sich die betreffende Stelle selbst ansehen und den Kontext prüfen, bevor Sie sie zitieren oder teilen.
- RO: Transcrierile automate pot conține erori, așa că urmăriți pasajul propriu-zis și verificați-i contextul înainte de a-l cita sau distribui.

> **Flags for review**
> - The sentence pointing to the lecture link at the top left is not in the notes; the link is new on the slide.
> - The visible YouTube transcript contains recognition errors; the narration's general warning covers this.

## Slide 5: Interactive Graphs

**28.** `3:02.6 / 3:15.1 / 3:39.4` **[highlight]**
- EN: The fourth idea is interactive graphs.
- DE: Die vierte Idee sind interaktive Diagramme.
- RO: A patra idee: graficele interactive.

**29.** `3:05.9 / 3:18.1 / 3:42.5` **[highlight]**
- EN: When many curves share one plot, as in the lower chart, following any single one is difficult.
- DE: Wenn sich viele Kurven ein Diagramm teilen, wie unten zu sehen, ist es schwer, einer einzelnen zu folgen.
- RO: Când multe curbe împart același grafic, ca în graficul de jos, este dificil să urmăriți una singură.

**30.** `3:11.5 / 3:24.4 / 3:49.8` **[highlight]**
- EN: Both charts show ROC curves per forecast lead time, comparing a neural network with a baseline. In the upper chart, one scenario stands out while the others fade into the background.
- DE: Beide Diagramme zeigen ROC-Kurven je Vorhersagehorizont und vergleichen ein neuronales Netz mit einer Baseline. Im oberen Diagramm hebt sich ein Szenario deutlich ab, während die anderen in den Hintergrund treten.
- RO: Ambele grafice arată curbe ROC pentru fiecare orizont de prognoză, comparând o rețea neuronală cu un model de referință. În graficul de sus, un scenariu iese în evidență, iar celelalte trec în fundal.

**31.** `3:23.6 / 3:37.1 / 4:04.3` **[highlight]**
- EN: That is because a forecast scenario was selected in the legend, which makes its graph more salient.
- DE: Das liegt daran, dass in der Legende ein Vorhersageszenario ausgewählt wurde, wodurch seine Kurve stärker hervortritt.
- RO: Asta pentru că un scenariu de prognoză a fost selectat în legendă, ceea ce face graficul său mai vizibil.

**32.** `3:29.5 / 3:43.8 / 4:11.2` **[highlight]**
- EN: This is possible because Weights and Biases supports Vega-Lite, a language for customizing charts for accessibility.
- DE: Möglich ist das, weil Weights and Biases Vega-Lite unterstützt, eine Sprache, mit der sich Diagramme barrierearm anpassen lassen.
- RO: Acest lucru este posibil deoarece Weights and Biases acceptă Vega-Lite, un limbaj pentru personalizarea graficelor în vederea accesibilității.

**33.** `3:36.6 / 3:51.6 / 4:19.9` **[highlight]**
- EN: With it, you can adjust colors, labels, and legends, and add interactive highlighting when hovering over or clicking on lines.
- DE: Damit lassen sich Farben, Beschriftungen und Legenden anpassen und interaktive Hervorhebungen beim Überfahren oder Anklicken von Linien hinzufügen.
- RO: Cu el puteți ajusta culorile, etichetele și legendele și puteți adăuga evidențiere interactivă la trecerea cursorului peste linii sau la clic pe ele.

**34.** `3:44.1 / 4:00.4 / 4:29.8`
- EN: Choices like these make comparisons easier to follow. So aim for readable colors and clear labels, as well as interactive highlighting.
- DE: Solche Gestaltungsentscheidungen machen Vergleiche leichter nachvollziehbar. Achten Sie also auf gut lesbare Farben und klare Beschriftungen sowie auf interaktive Hervorhebungen.
- RO: Astfel de alegeri fac comparațiile mai ușor de urmărit. Alegeți deci culori ușor de citit și etichete clare, precum și evidențiere interactivă.

> **Flags for review**
> - The notes don't say what the plotted data are. The narration describes them from the chart titles ("ROC Curves per Lead: ANN vs Baseline") as ROC curves per forecast lead time, neural network vs. baseline. Please verify.

## Slide 6: Intuitive Visualization and Animation Libraries

**35.** `3:52.9 / 4:11.4 / 4:40.3` **[highlight]**
- EN: The last idea: intuitive visualization and animation libraries.
- DE: Die letzte Idee: Bibliotheken für intuitive Visualisierung und Animation.
- RO: Ultima idee: biblioteci pentru vizualizare intuitivă și animație.

**36.** `3:57.7 / 4:16.8 / 4:45.2` **[highlight]**
- EN: Visualization and animation can make a mathematical process easier to follow, step by step.
- DE: Visualisierungen und Animationen können einen mathematischen Prozess Schritt für Schritt leichter nachvollziehbar machen.
- RO: Vizualizarea și animația pot face un proces matematic mai ușor de urmărit, pas cu pas.

**37.** `4:04.1 / 4:23.5 / 4:51.5` **[highlight]**
- EN: At the top is smalldiffusion, a library focused on diffusion models. These panels show how its output changes as the guidance scale, labelled CFG scale, goes from zero to three.
- DE: Oben sehen Sie smalldiffusion, eine Bibliothek für Diffusionsmodelle. Die Bilder zeigen, wie sich die Ausgabe verändert, wenn die Guidance-Skala, hier als „CFG Scale“ bezeichnet, von null auf drei steigt.
- RO: Sus este smalldiffusion, o bibliotecă dedicată modelelor de difuzie. Aceste panouri arată cum se schimbă rezultatul pe măsură ce scala de ghidare, notată „CFG Scale”, crește de la zero la trei.

**38.** `4:15.5 / 4:35.4 / 5:05.3` **[highlight]**
- EN: Below is Manim, a more general mathematical animation engine, shown here with a curve, a secant line, and the area beneath it.
- DE: Darunter sehen Sie Manim, eine allgemeinere Engine für mathematische Animationen, hier mit einer Kurve, einer Sekante und der Fläche darunter.
- RO: Dedesubt este Manim, un motor mai general de animație matematică, prezentat aici cu o curbă, o secantă și aria de sub ea.

**39.** `4:24.2 / 4:43.8 / 5:13.9` **[highlight]**
- EN: Because the animation is generated from code, libraries like these help reduce the hallucinations that often arise from purely video-based generators.
- DE: Da die Animation aus Code erzeugt wird, helfen solche Bibliotheken, die Halluzinationen zu verringern, die bei rein videobasierten Generatoren häufig auftreten.
- RO: Deoarece animația este generată din cod, astfel de biblioteci ajută la reducerea halucinațiilor care apar adesea la generatoarele bazate exclusiv pe video.

**40.** `4:33.4 / 4:52.9 / 5:23.8` **[highlight]**
- EN: You can give them to an AI agent as dependencies, so it can build the visual explanation for you.
- DE: Sie können sie einem KI-Agenten als Abhängigkeiten mitgeben, damit er die visuelle Erklärung für Sie erstellt.
- RO: Le puteți oferi unui agent AI ca dependențe, astfel încât acesta să construiască explicația vizuală pentru dumneavoastră.

**41.** `4:39.1 / 4:59.0 / 5:32.2`
- EN: As always, inspect the code and check that the animation represents the concept correctly.
- DE: Prüfen Sie wie immer den Code und kontrollieren Sie, ob die Animation das Konzept korrekt darstellt.
- RO: Ca întotdeauna, inspectați codul și verificați dacă animația reprezintă corect conceptul.

**42.** `4:44.7 / 5:04.8 / 5:38.2`
- EN: A good way to start is with one concept that would benefit from a visual explanation. Then review and refine the result.
- DE: Ein guter Einstieg ist ein einzelnes Konzept, das von einer visuellen Erklärung profitieren würde. Prüfen und verfeinern Sie anschließend das Ergebnis.
- RO: Un bun punct de plecare este un singur concept care ar beneficia de o explicație vizuală. Apoi verificați și rafinați rezultatul.

> **Flags for review**
> - The notes don't explain the "CFG Scale = 0..3" panels; the narration only says they show how the output changes with the guidance scale.
> - The description of the Manim image (curve, secant line, area beneath) comes from the picture, not the notes.

## Slide 7: References

**43.** `4:52.4 / 5:14.6 / 5:48.2` **[highlight]**
- EN: Finally, this slide collects the links to the tools and examples used throughout the presentation.
- DE: Zum Schluss fasst diese Folie die Links zu den Werkzeugen und Beispielen aus der gesamten Präsentation zusammen.
- RO: În final, acest slide reunește linkurile către instrumentele și exemplele folosite pe parcursul prezentării.

**44.** `4:58.2 / 5:20.8 / 5:56.0` **[highlight]**
- EN: Prism for LaTeX editing, the video tutorial examples, Weights and Biases for experiment tracking, and Vega-Lite for interactive graphs.
- DE: Prism für die Bearbeitung von LaTeX, die Beispiel-Videotutorials, Weights and Biases für das Experiment-Tracking und Vega-Lite für interaktive Diagramme.
- RO: Prism pentru editarea LaTeX, exemplele de tutoriale video, Weights and Biases pentru urmărirea experimentelor și Vega-Lite pentru grafice interactive.

**45.** `5:06.9 / 5:30.3 / 6:05.3` **[highlight]**
- EN: Then smalldiffusion for diffusion model visualizations, Manim for mathematical animations, and the example video with timestamps.
- DE: Außerdem smalldiffusion für Visualisierungen von Diffusionsmodellen, Manim für mathematische Animationen und das Beispielvideo mit Zeitstempeln.
- RO: Apoi smalldiffusion pentru vizualizarea modelelor de difuzie, Manim pentru animații matematice și videoclipul exemplu cu marcaje de timp.

**46.** `5:15.1 / 5:39.3 / 6:13.8` **[highlight]**
- EN: The project page gathers everything in one place: the downloadable presentation, the poster, the video, voice samples, and resource links.
- DE: Die Projektseite bündelt alles an einem Ort: die Präsentation zum Herunterladen, das Poster, das Video, Stimmbeispiele und Links zu den Ressourcen.
- RO: Pagina proiectului reunește totul într-un singur loc: prezentarea descărcabilă, posterul, videoclipul, mostrele de voce și linkurile către resurse.

> **Flags for review**
> - What the project page offers (presentation, poster, video, voice samples, links) is taken from the notes; the page itself was not checked.

## Slide 8: Closing

**47.** `5:25.3 / 5:48.5 / 6:25.7`
- EN: That's all for this overview. Thank you for watching.
- DE: Das war's für diesen Überblick. Vielen Dank fürs Zuschauen.
- RO: Aceasta a fost prezentarea generală. Vă mulțumim pentru vizionare.

> **Flags for review**
> - Slide 8 has no speaker notes; a short closing line was added.
> - The "That's all Folks!" end card resembles the Looney Tunes closing title (a Warner Bros. trademark); consider replacing it for open publication.
