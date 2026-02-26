# TVP VOD Ads – Hosts File Blocklist / Blokada reklam przez plik hosts

## 🇬🇧 English

This repository provides a simple **hosts file blocklist** for disabling video advertisement domains used by **TVP VOD (Telewizja Polska)** streaming services.

### Purpose

TVP VOD service does not respect standard browser-based ad-blocking extensions.  
This project provides a **system-level workaround** by blocking known ad servers via the `hosts` file.

### How It Works

By redirecting ad-related domains to `0.0.0.0`, the operating system cannot establish connections to these servers, effectively preventing ads from loading.

### Hosts File Entries

```txt
# TVP VOD stream ads – add this to your hosts file
0.0.0.0 ads.tvp.pl
0.0.0.0 r.tvp.pl
0.0.0.0 r4---sn-f5f7lnly.c.2mdn.net
0.0.0.0 gcdn.2mdn.net
0.0.0.0 s1.adform.net
```

### Usage

- Disable browser-based ad blockers for TVP VOD website.
- Add the entries above to your system `hosts` file:
  - Linux / macOS: `/etc/hosts`
  - Windows: `C:\Windows\System32\drivers\etc\hosts`
- Flush the DNS cache if required.
- Reload the TVP VOD page

### Disclaimer

- This list is minimal and based on observed behavior.
- Domains and ad delivery mechanisms may change over time.
- Use at your own responsibility.

---

## 🇵🇱 Polski

To repozytorium zawiera prostą **listę blokującą dla pliku `hosts`**, umożliwiającą wyłączenie reklam wideo używanych przez **TVP VOD (Telewizja Polska)**.

### Cel

TVP VOD wyświetla reklamy i nie respektuje standardowych blokerów reklam działających w przeglądarce.
Projekt oferuje **rozwiązanie na poziomie systemu operacyjnego**, polegające na blokowaniu znanych serwerów reklamowych bezpośrednio w pliku `hosts`.

### Jak to działa

Przekierowanie domen powiązanych z reklamami na adres `0.0.0.0` uniemożliwia systemowi nawiązanie połączenia z tymi serwerami, co skutecznie blokuje reklamy.

### Wpisy do pliku hosts

```txt
# TVP VOD stream ads – add this to your hosts file
0.0.0.0 ads.tvp.pl
0.0.0.0 r.tvp.pl
0.0.0.0 r4---sn-f5f7lnly.c.2mdn.net
0.0.0.0 gcdn.2mdn.net
0.0.0.0 s1.adform.net
```

### Instrukcja użycia

- Wyłącz blokery reklam w przeglądarce dla strony tvp vod.
- Dodaj powyższe wpisy do systemowego pliku `hosts`:
  - Linux / macOS: `/etc/hosts`
  - Windows: `C:\Windows\System32\drivers\etc\hosts`
- Wyczyść pamięć podręczną DNS (jeśli wymagane).
- Odswierz strone lub aplikację streamingową.

### Informacja

- Lista jest minimalna i oparta na obserwacjach.
- Domeny mogą ulec zmianie w przyszłości.
- Korzystasz na własną odpowiedzialność.
