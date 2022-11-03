# menu-project-mj
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jeliti/menu-project-mj/main?filepath=Data_analysis_notebook.ipynb)

## Presentation


Données musicales Spotify
Cet ensemble de données se compose d'environ 600 chansons qui figuraient parmi les meilleures chansons de l'année de 2010 à 2019 (mesurées par Billboard). Vous pouvez explorer des données de chansons intéressantes extraites de Spotify telles que les battements par minute, la quantité de mots prononcés, le volume et l'énergie de chaque chanson.
 
 ceci est un prototype de projet en analyse de donnee
<img src='images/spotify.png' width="100px">

****** Dictionnaire de données ******
<!DOCTYPE html>
<html>
<head>
<style>
table {
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

td, th {
  border: 1px solid #dddddd;
  text-align: left;
  padding: 8px;
}

tr:nth-child(even) {
  background-color: #dddddd;
}
</style>
</head>
<body>
<table>
  <tr>
	 <th>Variable</th>	 <th>Explanation</th>  </tr>
	<tr><td>0</td>	<td>title</td>	       <td> The title of the song</td></tr>
<tr><td>1</td>	<td>	artist	  </td>	       <td>        The artist of the song</td></tr>
<tr><td>2</td>	<td>	top genre</td>	       <td> 	The genre of the song</td></tr>
<tr><td>3</td>	<td>	year	  </td>	       <td>        The year the song was in the Billboard</td></tr>
<tr><td>4</td>	<td>	bpm	</td>	       <td>          Beats per minute: the tempo of the song</td></tr>
<tr><td>5</td>	<td>	nrgy	</td>	       <td> The energy of the song: higher values mean more energetic (fast, loud)</td></tr>
<tr><td>6</td>	<td>	dnce	</td>	       <td> The danceability of the song: higher values mean it's easier to dance to</td></tr>
<tr><td>7</td>	<td>	dB	</td>	       <td> Decibel: the loudness of the song</td></tr>
<tr><td>8</td>	<td>	live	</td>	       <td> Liveness: likeliness the song was recorded with a live audience</td></tr>
<tr><td>9</td>	<td>	val	</td>	       <td> Valence: higher values mean a more positive sound (happy, cheerful)</td></tr>
<tr><td>10</td>	<td>	dur	</td>	       <td> The duration of the song</td></tr>
<tr><td>11</td>	<td>	acous	</td>	       <td> The acousticness of the song: likeliness the song is acoustic</td></tr>
<tr><td>12</td>	<td>	spch	</td>	       <td> Speechines: higher values mean more spoken words</td></tr>
<tr><td>13</td>	<td>	pop	</td>	       <td> Popularity: higher values mean more popular</td></tr>
	</table>

</body>
</html>



 ## : file_folder: Dataset
     cet ensemble de données représente la meilleure chanson par année dans le monde par spotify cet ensemble de données a plusieurs variables sur les chansons et est basé sur le panneau d'affichage

   la data set contient des donnees dates 

##  Analyse
Entraînez et construisez un classificateur pour prédire le genre d'une chanson en fonction des colonnes 3 à 13.
Les scénarios sont des questions plus larges pour vous aider à développer un projet de bout en bout pour votre portefeuille :

Votre amie, qui est une musicienne en herbe, veut faire une chanson à succès et vous a demandé d'utiliser vos compétences en matière de données pour l'aider. Vous avez décidé d'analyser ce qui fait une chanson top, en gardant à l'esprit les changements au fil des ans. Quelles recommandations concrètes pouvez-vous lui donner avant qu'elle n'écrive les paroles, ne fasse des beats et n'enregistre la chanson ? Elle est ouverte à tous les genres !


## Conclusion
