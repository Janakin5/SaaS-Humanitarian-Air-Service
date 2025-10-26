# SaaS-Humanitarian-Air-Service

## Summary

Das Humanitarian Air Service SaaS erkennt automatisch Krisen, optimiert Einsatzplanung und vereinfacht die Disposition von Luftrettungseinsätzen, Charterflügen und medizinischen Transporten


## Background

Es kommt immer wieder zu dramatischen Humanitairen Krisen. Oft ist dabei die Versorgung nur sehr erschwert möglich - der Luftweg ist dabei ein elementarer Bestandteil. 
Viele NGOs & UNHAS verlieren viel Zeit bei der Bedarfsanalyse und Einsatzkoordination, die Flugkapazitäten sind knapp und teilweise schlecht koordiniert.
Zudem treten viele Krisen in gering erschlossenen Gebieten auf, was die Einsatzmöglichkeiten sehr intransparant macht.

Die Lösung ist eine AI-gestützte Plattform, die automatisch:
- Krisen erkennt (z.B. via Satelitenbilder, Newsfeeds, Geografischen Daten)
- Flugplätze vorschlägt (Runway-Checks, Restriktionen - auch bspw. über Satelitenbilder)
- verfügbare Ressourcen abschätzt und zuweist (Flugzeug, Crew, Ausstattung)
- Einsatzpläne erstellt (+ an Crews weiterleitet)


## How is it used?

Eine Krise wird entweder Angegeben oder automatisch vom System erkannt. Die KI analysiert diese in Bezug auf Humanitaire Lufteinsätze genauer:
- Schwere der Situation wird abgeschätz (anhand von früheren Krisen, ansässige Bevölkerung, Folgeereignisse, etc.)
- aktuell verfügbare Flugkapazitäten werden untersucht und die am besten geeigneten Teile/ Crews ausgewählt (auch unter Einbezug der Wetterlage/Möglichkeiten vor Ort, Dienstplänen, etc.)
- eine allgemeine Übersicht wird erstellt (benötigter Treibstoff, Güter die transportiert werden müssen, besonderer Bedarf, Plätze, die ausgeflogen werden müssen, Personal, das benötig wird)
- nach Bestätigung durch einen Menschen können in einer Weiterentwicklung automatische Einsatzpläne erstellt werden


## Data sources and AI methods
Mögliche Datenquellen sind vor allem Satelitenbilder und -daten. Desweiteren müssten Wetter bzw. allgemein Geografische Daten bezogen werden.

## Challenges

Jede Krise ist sehr individuell, außerdem liegt die Umsetzung weiterhin bei den Menschen. Wenn das Programm jedoch falschliegt (bspw. Treibstoffbedarf) treten direkt sehr große Probleme auf, da es sich allgemein um ein sehr sensiblen Bereich handelt. Deswegen müsste rein rechtlich wahrscheinlich alles gegengeprüft werden.

## What next?

Ausgehend von der stark auf die Vorhersage aufgebaute Plattform, sind erweiterungen möglich, bspw. die Erstellung von Einsatzplänen, sodass mit nur einer Freigabe eines Menschen die Flugzeuge abheben können.


## Acknowledgments

* UNHAS (United Nations Humanitarian Air Service)
