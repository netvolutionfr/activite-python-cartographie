# 5. Ajouter un marqueur

Saisissez le code suivant :

```python
import folium
c= folium.Map(location=[46.078025, 6.409053],zoom_start=20)
folium.Marker([46.078637266899,  6.4111924884134]).add_to(c)
c.save('maCarte.html')
```

Que constatez-vous ?

Modifiez les coordonnées et le zoom de la carte pour centrer la carte sur Boulogne-sur-Mer, et placer le marqueur sur
le lycée St Joseph.
