---
marp: true
theme: gaia
color: #000
colorSecondary: #333
backgroundColor: #fff
style: |
    section.lead h1 {
    text-align: center;
    }


---
<!-- _class: lead -->
# Reverse Proxy


---
<!-- _class: lead -->
## Reverse Proxy
<br>

- Pośredniczy w komunikacji między światem zewnętrznym a serwisami
- Zoptymalizowany do szybkiej obsługi zapytań HTTP
- Implementuje warstwę szyfrowania TLS
- Może obsługiwać wiele serwisów na standardowych portal 80 i 443
- Automatyzacja przekierowań i kodów odpowiedzi HTTP

---
<!-- _class: lead -->
## Przykłady
<br>

- Nginx
- Apache HTTP Server
- Envoy

---
<!-- _class: lead -->
## TLS
<br>

- Zapewnia szyfrowanie w trakcie przesyłu danych
- Oparte o certyfikaty wystawione przez zaufane Certificate Authority
- Uniemożliwia ataki typu man-in-the-middle

---
<!-- _class: lead -->
## Let's Encrypt
<br>

- Umożliwia darmowe zamówienie certyfikatów TLS
- Zaufane dla wszystkich współczesnych przeglądarek
- Łatwe odnawianie certyfikatów
- Dla wielu reverse proxy gotowe automatyczne integracje
