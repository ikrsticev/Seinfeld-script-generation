# Seinfeld-script-generation
Generiranje teksta Seinfeld skripte koristeći neuronske mreže

Naš "dataset" je ubiti Seinfield.txt koji smo trebali podijeliti na skup za treniranje i skup za testiranje. To sam učinio tako da sam uzeo skup znakova (train) i njemu pridružio skup znakova pomaknut udesno (test). Npr za Seinfield je input "Seinfiel" a željeni output "einfield". Model ne priča vrlo smisleno ali ima neki koncept vokabulara i gramatike, i uglavnom je upamtio likove. Tekst datoteka ima preko 3 milijuna znakova. Uspješnost modela, osim svojom subjektivnom procjenom, sam mjerio preko loss-a modela. Najbolji rezultat koji sam dobio je 0.7 loss.
