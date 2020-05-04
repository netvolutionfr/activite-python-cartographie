4. Changer le zoom

Pour changer le zoom par défaut (à la création de la carte), modifier le code afin d'ajouter le paramètre "zoom" comme
ceci :

```python
c= folium.Map(location=[46.078025, 6.409053],zoom_start=15)
```

À chaque changement, vous devrez exécuter de nouveau le script Python, puis copier / coller le nouveau code du fichier
"maCarte.html" dans le code de la page "index.html" du projet HTML.
