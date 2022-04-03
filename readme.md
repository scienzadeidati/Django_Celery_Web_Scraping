# Costruire uno scraper di feed RSS con Python
Questo è un progetto creato per illustrare le basi del web scraping estraendo informazioni dal [feed RSS di HackerNews](https://news.ycombinator.com/rss). Questo si basa da un semplice web scraper in `scraping.py`, in uno strumento di scraping automatizzato in `tasks.py`.

## Articoli

1. Creazione di uno scraper di feed RSS con Python è disponibile [qui](https://scienzadeidati.com/blog/creazione-di-uno-scraper-di-feed-rss-con-python).

2. Scraping web automatizzato con Python e Celery è disponibile [qui](https://scienzadeidati.com/blog/web-scraping-automatizzato-python-celery).

3. Realizzazione di un'applicazione di scraping web con Python, Celery e Django [here]().


## Comandi di scraping automatizzati
I seguenti comandi sono usati per avviare lo scraping pianificato con Celery in `tasks.py`.

Avvio del nostro server RabbitMQ (terminale n. 1):
```
rabbitmq-server
```

Avvio dello scraping e applicazione Django (terminale #2):
```
python manage.py runserver
```

MIT License.