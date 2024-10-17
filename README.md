<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Internetes Kommunikáció Szabályai: Protokollok</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }
        h1, h2, h3 {
            color: #333;
        }
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <h1>Internetes Kommunikáció Szabályai: Protokollok</h1>

    <h2>Bevezetés</h2>
    <p>Az internetes kommunikációban a protokollok a legfontosabb szerepet játsszák, hiszen ezek határozzák meg, hogy az adatok hogyan cserélődnek a különböző eszközök között. Az alábbiakban bemutatjuk a legfontosabb protokollokat, azok feladatait és az OSI vagy TCP/IP modellek keretein belül való elhelyezkedésüket.</p>

    <h2>1. Protokollok és Rétegek</h2>

    <h3>1.1 OSI Modell</h3>
    <p>Az OSI (Open Systems Interconnection) modell hét rétegből áll. Ezek a következők:</p>
    <ul>
        <li><strong>Fizikai réteg</strong>: Fizikai eszközök és médiák, például kábelek és átvitel.</li>
        <li><strong>Adatkapcsolati réteg</strong>: Hálózati eszközök közötti adatátvitel.</li>
        <li><strong>Hálózati réteg</strong>: Címzés és adatcsomagok irányítása.</li>
        <li><strong>Szállítási réteg</strong>: Adatok megbízható vagy nem megbízható átvitele.</li>
        <li><strong>Viszony réteg</strong>: A kommunikáló alkalmazások közötti kapcsolat.</li>
        <li><strong>Megjelenítési réteg</strong>: Adatok formátumának és kódolásának kezelése.</li>
        <li><strong>Alkalmazási réteg</strong>: A felhasználói alkalmazások és a hálózat közötti interfész.</li>
    </ul>

    <h3>1.2 TCP/IP Modell</h3>
    <p>A TCP/IP modell négy rétegből áll:</p>
    <ul>
        <li><strong>Link réteg</strong>: Hálózati eszközök közötti kommunikáció.</li>
        <li><strong>Internetes réteg</strong>: Címzés és forgalomirányítás.</li>
        <li><strong>Szállítási réteg</strong>: Adatok megbízható átvitele (TCP) vagy nem megbízható (UDP).</li>
        <li><strong>Alkalmazási réteg</strong>: Felhasználói alkalmazások interfésze.</li>
    </ul>

    <h2>2. Fontosabb Protokollok</h2>

    <h3>2.1 HTTP/HTTPS</h3>
    <ul>
        <li><strong>Protokoll neve</strong>: HTTP (Hypertext Transfer Protocol) / HTTPS (HTTP Secure)</li>
        <li><strong>Feladatok</strong>: Weboldalak adatainak átvitele, biztonságos kommunikáció (HTTPS).</li>
        <li><strong>Réteg</strong>: Alkalmazási réteg</li>
    </ul>
    <img src="https://example.com/http_https_diagram.png" alt="HTTP/HTTPS Diagram">

    <h3>2.2 FTP</h3>
    <ul>
        <li><strong>Protokoll neve</strong>: FTP (File Transfer Protocol)</li>
        <li><strong>Feladatok</strong>: Fájlok átvitele a hálózaton.</li>
        <li><strong>Réteg</strong>: Alkalmazási réteg</li>
    </ul>

    <h3>2.3 TCP</h3>
    <ul>
        <li><strong>Protokoll neve</strong>: TCP (Transmission Control Protocol)</li>
        <li><strong>Feladatok</strong>: Megbízható adatátvitel, hibajavítás.</li>
        <li><strong>Réteg</strong>: Szállítási réteg</li>
    </ul>

    <h3>2.4 UDP</h3>
    <ul>
        <li><strong>Protokoll neve</strong>: UDP (User Datagram Protocol)</li>
        <li><strong>Feladatok</strong>: Gyors, de nem megbízható adatátvitel.</li>
        <li><strong>Réteg</strong>: Szállítási réteg</li>
    </ul>

    <h3>2.5 IP</h3>
    <ul>
        <li><strong>Protokoll neve</strong>: IP (Internet Protocol)</li>
        <li><strong>Feladatok</strong>: Címzés és adatcsomagok irányítása.</li>
        <li><strong>Réteg</strong>: Internetes réteg</li>
    </ul>
    <img src="https://example.com/tcp_ip_model.png" alt="TCP/IP Modell">

    <h2>3. Összegzés</h2>
    <p>A protokollok alapvető szerepet játszanak az internetes kommunikációban, mivel lehetővé teszik az adatok hatékony és megbízható átvitelét. Az OSI és TCP/IP modellek segítségével könnyen megérthetjük, hogyan működnek ezek a protokollok és milyen feladatokat látnak el.</p>

    <h3>Ajánlott Források</h3>
    <ul>
        <li><a href="https://www.ietf.org/rfc/rfc2616.txt">RFC 2616: HTTP/1.1</a></li>
        <li><a href="https://www.ietf.org/rfc/rfc791.txt">RFC 791: IP</a></li>
        <li><a href="https://www.ietf.org/rfc/rfc793.txt">RFC 793: TCP</a></li>
    </ul>

</body>
</html>
