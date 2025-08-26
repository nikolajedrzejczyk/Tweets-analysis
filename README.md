# Tweets-analysis
Sentiment and emotion analysis of tweets related to Selena Gomez and Hailey Bieber using Python.  
(Analiza sentymentu i emocji w tweetach o Selenie Gomez i Hailey Bieber w Pythonie.)

---

## Opis projektu:  
Celem badania było zrozumienie, jak użytkownicy Twittera reagowali emocjonalnie na medialny konflikt pomiędzy Seleną Gomez a Hailey Bieber, a także sprawdzenie, które emocje dominowały w treści publikowanych tweetów. Analiza objęła trzy grupy danych:  
- tweety dotyczące **Seleny Gomez**  
- tweety dotyczące **Hailey Bieber**  
- tweety dotyczące ich **obu razem**  

Projekt został zrealizowany w języku **Python** z wykorzystaniem bibliotek do analizy tekstu i przetwarzania języka naturalnego. [Czerwiec 2023]
 
Projekt wykonany w ramach studiów. 

--- 

## Wykorzystane biblioteki:
   - pandas
   - snscrape
   - pandas
   - nltk
   - wordcloud
   - matplotlib
   - plotly
   - NRCLex
---

## Etapy analizy:  
1. **Pobranie danych z Twittera:**  
   - zastosowano `snscrape` do pozyskania tweetów z wybranego okresu  
   - pobrano osobno tweety o Selenie, Hailey oraz o nich razem
   - utworzono listy i ramki danych dla dalszej analizy

2. **Wstępne przetwarzanie danych (preprocessing):**  
   - czyszczenie treści tweetów 
   - normalizacja tekstu
   - tokenizacja i usunięcie stopwords  
   - lematyzacja słów

3. **Analiza ogólna:**  
   - zliczenie tweetów w czasie i przedstawienie trendów
   - wizualizacje chmur najczęściej używanych słów  

4. **Analiza sentymentu – dwa podejścia:**  
   - **VADER (NLTK):** klasyfikacja tweetów jako pozytywne, negatywne lub neutralne
   - **NRC Lexicon (NRCLex):** identyfikacja
