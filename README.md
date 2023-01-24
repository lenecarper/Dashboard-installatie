# Dashboard-installatie

Waarschijnlijk is het dashboard al voor u geinstalleerd. Dit is een gebruikersvriendelijke installatie, maar kan alsnog uitdagend lijken als u nog nooit hiermee hebt gewerkt.


- BEGINNERS SETUP

<pre>

1. Clone de code uit deze repository door in je terminal < git clone https://github.com/lenecarper/django-dashboard > te runnen.

2. Run < cd django-dashboard > om in de folder te komen.

3. Run < pip install -r requirements.txt > om alle configuratie en imports te installeren.

4. Run < source bin/activate >, hiermee start je een virtuele omgeving in de folder, als het goed is zal het al geïnstalleerd zijn.

5. Run < cd djangoDash > om in de hoofdfolder van het project te komen.

6. Run < python3 manage.py makemigrations - python3 manage.py migrate --run-syncdb - python3 manage.py runserver > om de data te migreren en de webserver te starten.

7. Open je bestanden op je desktop en navigeer naar je projectfolder. Vanuit je 'django-dashboard' folder, kopieer de folder genaamd 'dashing' en open de 'lib' folder. 

8. Vanuit de 'lib' folder, open de folders totdat je in 'site-packages' zit. In de 'django-dashboard' folder staat een folder genaamd 'dashing'. Kopieer en plak deze in de 'site-packages' folder. Het zal vragen of je zeker weet dat je de bestanden wilt vervangen, klik akkoord.

9. Ga terug naar de 'django-dashboard' folder en tab in de 'djangoDash' folder tot je bij het 'settings.py' bestand komt. Open dit bestand en verander de 'MEDIA_ROOT' onder in het bestand naar je eigen gebruikersnaam. Bijvoorbeeld 'MEDIA_ROOT = "/GEBRUIKER/django-dashboard/../../"'

</pre>

- GEBRUIK

<pre>

1. Zorg dat je alles geinstalleerd hebt zoals in de setup hierboven.

2. Run < python3 manage.py runserver > om de webserver te starten.

3. Indien u een error krijgt, kijk aub welk bestand het is en of het op te lossen is. Maak anders een issue aan in de GitHub. 

4. De eerste pagina die u ziet zal het dashboard zijn. Als alles goed is gegaan, zullen er 7 tabs zijn met tekst en een weerbericht etc.

5. Ook is er een pop-up, lees dit goed door en klik op de rode knop om het nooit meer te laten zien. Klik op de groene knop om uw dashboard gegevens te veranderen. (PS: klik op Ctrl+Shift+I of op F12 en ga in het rechter menu naar het tabblad 'Applicatie'. Hier zult u een opslag met 'alerted' zien. Verwijder dit om de pop-up terug te krijgen.)

6. Om bij de dashboard gegevens te komen, ga in de link naar '127.0.0.1/admin' en log in met de gegevens die je gekregen hebt.

7. Om de dashboard gegevens te veranderen kunt u ook in de pop-up klikken. Hierna wordt u doorgestuurd naar een invulformulier. Vul deze in nadat u ingelogd bent en klik op opslaan.

8. Klik rechtsboven op 'View site' in het admin dashboard om terug te gaan naar je dashboard.

</pre>

- Voor eventuele vragen, maak een issue aan in deze GitHub.
