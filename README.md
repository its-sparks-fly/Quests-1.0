# Quests-1.0
Erweitert MyBB um ein Foren RPG-Questsystem, das es Usern erlaubt, das Inplay mit vom Team versandten oder selbst entworfenen Aufgaben aufzupeppen.

<ul>
<li> Einsenden von kleinen Aufgaben ("Miniquests") in einen Quest-Würfel
<li> Ziehen von zufälligen Miniquests aus eben jenem Würfel
<li> Teammitglieder können Quests an einzelne oder eine Gruppe von Charakteren senden
<li> Übersicht offener Quests
<li> Übersicht erledigter Quests (+ deren Lösungen)
<li> Übersicht eingesandter Quests (+ deren Lösungen)
<li> Einsenden von Quest-Lösungen direkt über das mitgelieferte QuestCp
<li> Eingesandte und gelöste Threads müssen von Teammitgliedern freigeschaltet werden
<li> User werden per PN über ihnen zugesandte Quests informiert
</ul>

<h1>Plugin funktionsfähig machen</h1>
<ul>
<li>Die Plugin-Datei ladet ihr in den angegebenen Ordner <b>inc/plugins</b> hoch. 
<li>Den Ordner inc/plugins/quests ladet ihr ebenfalls in <b>inc/plugins</b>.
<li>Die Datei quests.php ladet ihr in euer <b>Hauptverzeichnis</b>, also dorthin, wo zB. auch index.php und modcp.php liegen.
<li>Das Plugin muss nun im Admin CP unter <b>Konfiguration - Plugins</b> installiert und aktiviert werden.
<li>Das QuestCP wird über http://eureseite.de/quests.php aufgerufen!
<li>Das QuestCP kann nun genutzt werden, ohne, dass noch weitere Einstellungen von Nöten sind.
</ul><br />

<h1>Template-Änderungen</h1>
Folgende Templates werden durch dieses Plugin <i>neu hinzugefügt</i>:
<ul>
<li>quests
<li>quests_accept
<li>quests_accept_bit
<li>quests_accept_done
<li>quests_accept_done_bit
<li>quests_accept_done_market_bit
<li>quests_active
<li>quests_active_bit
<li>quests_active_market_bit
<li>quests_add
<li>quests_done
<li>quests_done_bit
<li>quests_done_market_bit
<li>quests_mine
<li>quests_mine_bit
<li>quests_miniquests
<li>quests_nav
<li>quests_nav_team
<li>quests_senduser
</ul>

Folgende Templates werden durch dieses Plugin <i>bearbeitet</i>:
<ul>
<li>index
</ul>

<h1>Demo</h1><br />
<center>

<img src="http://eightletters.de/plugins/screens/quests1.jpg" /><br />
http://eightletters.de/plugins/screens/quests1.jpg<br /><br />

<img src="http://eightletters.de/plugins/screens/quests2.jpg" /><br />
http://eightletters.de/plugins/screens/quests2.jpg<br /><br />

<img src="http://eightletters.de/plugins/screens/quests3.jpg" /><br />
http://eightletters.de/plugins/screens/quests3.jpg<br /><br />

<img src="http://eightletters.de/plugins/screens/quests4.jpg" /><br />
http://eightletters.de/plugins/screens/quests4.jpg<br /><br />

<img src="http://eightletters.de/plugins/screens/quests5.jpg" /><br />
http://eightletters.de/plugins/screens/quests5.jpg<br /><br />

<img src="http://eightletters.de/plugins/screens/quests6.jpg" /><br />
http://eightletters.de/plugins/screens/quests6.jpg<br /><br />

<img src="http://eightletters.de/plugins/screens/quests7.jpg" /><br />
http://eightletters.de/plugins/screens/quests7.jpg<br /><br />

<img src="http://eightletters.de/plugins/screens/quests8.jpg" /><br />
http://eightletters.de/plugins/screens/quests8.jpg<br /><br />

</center>

Lokal unter MyBB 1.8.8 getestet und es funktionierte alles - da es allerdings nicht im alltäglichen Forengebrauch zum Test kam, kann es natürlich sein, dass es die ersten Härtetests aus diversen Gründen nicht besteht. Sollte es zu Fehlermeldungen oder Problemen kommen, könnt ihr euch jederzeit <b><u>hier im Thread</u></b> melden.


<h1>Weitere Anmerkungen</h1>
Das Quest-System war so ziemlich mein erstes Projekt. Ich sitze mittlerweile seit einem Jahr fast stetig daran und Interessenten können sich ziemlich darauf verlassen, dass die "Produktion" hier noch nicht vorbei ist. <3 Ich und User meiner Foren haben immer weitere, tolle Ideen, die mit großer Sicherheit hier verbaut werden. Daher ist die Entwicklung hieran noch lange nicht abgeschlossen und es wird in Zukunft regelmäßig coole Updates geben! So ist zB. geplant, komplette Plot-Lines mit verschiedenen Unteraufgaben verteilen zu können, sodass man auch sieht, dass diese Quest-"Gruppe" zueinander gehört. Das wird besonders Foren mit einem roten Story-Faden zu Gute kommen. Bis dahin müsst ihr euch aber hiermit zufrieden geben! Ideen und Vorschläge nehme ich gerne per PN entgegen. <3 
