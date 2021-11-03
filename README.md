Jawność sprzyja zwierzętom!
===========================

Strona kampanii "Jawność sprzyja zwierzętom!" Stowarzyszenia Sieć Obywatelska Watchdog Polska.

Jest to fork projektu repozytorium [twofactorauth](https://github.com/2factorauth/twofactorauth) odpowiedzialnego za [TwoFactorAuth.org](https://twofactorauth.org) dostosowanego do potrzeb specyfiki kampanii.

## Cel

Celem jest przyjęcie przez Sejm poprawek dotyczących wzmocnienia kontroli i jawności badań nad zwierzętami.

## Rozwój

Jeżeli chcesz pomóc wprowadzić zmiany, przeczytaj całe wytyczne w [podręczniku](CONTRIBUTING.md).

## Uruchomienie lokalne

Projekt jest zbudowany na [Jekyll](https://jekyllrb.com/) z użyciem gemu [GitHub-pages](https://github.com/github/pages-gem).
W celu uruchomienia storny lokalnie, konieczne jest zainstalowanie ``bundler`` i wszystkich zależności, a następnie użycie Jekyll, aby dostarczać stronę. Jeśli komenda `gem` nie jest dostępna, konieczne jest zainstalowanie Ruby z RubyGems.
Gdy Ruby i RubyGems są zainstalowane i dostępne z poziomu wiersza poleceń, dwa-skladniki można ustawić za pomocą następujących poleceń.

```
gem install bundler
cd ~/dwa-skladniki
bundle install
jekyll serve
```

Strona powinna być następnie dostępna z `http://localhost:4000`.

Rekomendowane jest wykorzystanie Ruby 2.4.0.

## Licencja

Kod źródłowy jest dostepny na licencji MIT. Aby uzyskać więcej informacji, przeczytaj [plik licencji][LICENSE] dostępny wraz z kodem źródłowym. Jest to fork projektu [twofactorauth](https://github.com/2factorauth/twofactorauth) odpowiedzialnego za [TwoFactorAuth.org](https://twofactorauth.org) dostosowanego do krajowej specyfiki.

[contrib]: /CONTRIBUTING.md
[license]: /LICENSE
