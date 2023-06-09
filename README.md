# TCP-Code
TCP und UDP Netzwerkprogramme
Dieses Repository enthält zwei Netzwerkprogramme, die TCP- bzw. UDP-Verbindungen verwenden, um Nachrichten zwischen einem Server und einem Client auszutauschen.

TCP-Programm
Das TCP-Programm besteht aus zwei Teilen: dem Server und dem Client.

Server: Der Server öffnet einen Socket und bindet ihn an eine Portnummer. Er wartet auf eingehende Verbindungen von Clients. Wenn eine Verbindung hergestellt wird, liest der Server die empfangene Nachricht und sendet eine Bestätigungsnachricht zurück an den Client.

Client: Der Client öffnet eine Verbindung zu einem Server, der über eine IP-Adresse und eine Portnummer identifiziert wird. Der Client sendet eine Nachricht an den Server und wartet auf die Bestätigungsnachricht des Servers.

UDP-Programm
Das UDP-Programm besteht ebenfalls aus einem Server- und einem Client-Teil.

Server: Der UDP-Server öffnet einen UDP-Socket und bindet ihn an eine Portnummer. Er empfängt Nachrichten von beliebigen Clients und druckt sie auf der Konsole aus.

Client: Der UDP-Client öffnet eine Verbindung zu einem UDP-Server, der über eine IP-Adresse und eine Portnummer identifiziert wird. Der Client sendet eine Nachricht an den Server.

Verwendung
Kompilieren Sie den Server und den Client für das TCP-Programm:

bash
Copy code
gcc server_tcp.c -o server_tcp
gcc client_tcp.c -o client_tcp
Starten Sie den TCP-Server:

bash
Copy code
./server_tcp <portnummer>
Führen Sie den TCP-Client aus:

bash
Copy code
./client_tcp <hostname> <portnummer>
Kompilieren Sie den Server und den Client für das UDP-Programm:

bash
Copy code
gcc server_udp.c -o server_udp
gcc client_udp.c -o client_udp
Starten Sie den UDP-Server:

bash
Copy code
./server_udp <portnummer>
Führen Sie den UDP-Client aus:

bash
Copy code
./client_udp <hostname> <portnummer>
Hinweis: Ersetzen Sie <portnummer> durch die gewünschte Portnummer und <hostname> durch die IP-Adresse oder den Hostnamen des Servers.
