affichage du résultat:
label_resultat = tk.Label(app,
                          text="",
                          bg="#0B3D91",
                          fg="yellow",
                          font=("Arial", 14))
label_resultat.pack(pady=10)

affichage est mis à jour :
if resultat:
    label_resultat.config(text=resultat[0])
else:
    label_resultat.config(text="Mot non trouvé")

 L’écran =
label_resultat = tk.Label(...)
 Le texte affiché à l’écran =
label_resultat.config(text=...)
