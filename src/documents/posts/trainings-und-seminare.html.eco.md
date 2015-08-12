```
title: Trainings und Seminare
layout: page
```

<img class="whiteborder" src="../images/haende.png" alt="Claudia Dietl" width="400" align="right">


<p>
	Das Angebot wird auf Ihre spezifischen Bedürfnisse abgestimmt.  <br>
	Sie erhalten von mir nach einem ausführlichem Gespräch ein individuelles Seminarangebot inkl. Konzeption und Leitfaden.
</p>

<p>
	Eine Auswahl bisheriger Trainings und Seminare:
</p>

<p><navlist class="linklist">
	<% for document in @getCollection('posts').toJSON(): %>
		<li>
 		<a href="<%= document.url %>"><%= document.title %></a></li>
	<% end %>
</navlist></p>

<p class="linklist">
	<ul>
		<li>Erfolgreiche Verhandlungsführung</li>
		<li>Umgang mit schwierigen Emotionen</li>
		<li>Veränderungsprozesse zielführend gestalten</li> 
		<li>Kreativität im Umsetzen von Lebenszielen</li>
 	</ul>
</p>

<p> <a href="../pdf/trainerprofil.pdf" target="_top" role="button" class="btn"><i class="icon-download"></i>  Trainerprofil als PDF herunterladen</a></p>