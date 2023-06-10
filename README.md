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

