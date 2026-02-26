TVP VOD Ads – Hosts File Blocklist

This repository provides a simple hosts file blocklist for disabling video advertisement domains used by TVP VOD (Telewizja Polska) streaming services.

Purpose

TVP VOD streams advertisements and often does not respect standard browser-based ad-blocking extensions. This project offers a system-level workaround by blocking known ad and tracking servers directly via the hosts file.

How It Works

By redirecting ad-related domains to 0.0.0.0, the operating system is unable to establish connections to those servers, effectively preventing ads from loading at the network level.

Hosts File Entries
# TVP VOD stream ads – disable your ad blocker and add this to the hosts file
0.0.0.0 ads.tvp.pl
0.0.0.0 r.tvp.pl
0.0.0.0 2mdn.net

Usage

(Optional) Disable browser-based ad blockers for testing purposes.

Add the entries above to your system hosts file:

Linux / macOS: /etc/hosts

Windows: C:\Windows\System32\drivers\etc\hosts

Flush the DNS cache if required.

Restart your browser or streaming application.

Disclaimer

This blocklist is minimal and based on observed behavior.

TVP may change domains or delivery mechanisms at any time.

Use at your own responsibility.

🇵🇱 TVP VOD Ads – Blokada reklam przez plik hosts

To repozytorium zawiera prostą listę blokującą w pliku hosts, która umożliwia wyłączenie reklam wideo używanych przez TVP VOD (Telewizja Polska).

Cel

TVP VOD emituje reklamy i często nie respektuje standardowych blokerów reklam działających w przeglądarce. Ten projekt stanowi rozwiązanie na poziomie systemu operacyjnego, polegające na blokowaniu znanych serwerów reklamowych i śledzących za pomocą pliku hosts.

Jak to działa

Przekierowanie domen powiązanych z reklamami na adres 0.0.0.0 uniemożliwia systemowi nawiązanie połączenia z tymi serwerami, co skutecznie blokuje reklamy na poziomie sieciowym.

Wpisy do pliku hosts
# TVP VOD stream ads – disable your ad blocker and add this to the hosts file
0.0.0.0 ads.tvp.pl
0.0.0.0 r.tvp.pl
0.0.0.0 2mdn.net
Instrukcja użycia

(Opcjonalnie) wyłącz blokery reklam w przeglądarce – przydatne do testów.

Dodaj powyższe wpisy do systemowego pliku hosts:

Linux / macOS: /etc/hosts

Windows: C:\Windows\System32\drivers\etc\hosts

Wyczyść pamięć podręczną DNS (jeśli wymagane).

Uruchom ponownie przeglądarkę lub aplikację streamingową.

Informacja

Lista jest minimalna i oparta na zaobserwowanym działaniu.

Domeny mogą ulec zmianie w przyszłości.

Korzystasz na własną odpowiedzialność.
