This ESP8266-based device connects to Wi-Fi, fetches live USD exchange rates (EUR, GBP, ZAR) from ExchangeRate-API every 60 seconds, 
and displays them on a 1.14" color LCD. The screen auto-flips 
every 5 seconds between the current rates and the last update timestamp — no buttons needed.*
WiFi connection – Connects to your local network.

HTTPS request – Fetches JSON data from a free API (uses insecure SSL for simplicity).

JSON parsing – Extracts EUR, GBP, ZAR rates and the UTC update time.

LCD display – Shows rates on page 0, date & time on page 1.

Auto page flip – Cycles every 5 seconds.

Periodic refresh – Fetches new rates every minute.
