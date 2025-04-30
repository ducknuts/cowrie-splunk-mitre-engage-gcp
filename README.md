# cowrie-splunk-mitre-engage-gcp
Afsluttende projekt ved KEA (IT-teknolog)

Resumé:
Med ønsket om at forstå honeypots og hvordan de kan bidrage til sikre netværk, bygges der et miljø til analyse. Miljøet bygges på Google Cloud Platform, og indeholder to virtuelle maskiner med hhv. honeypotten Cowrie + en Universal Forwarder, og Splunk Enterprise. Cowrie indsamler data, sender det til Splunk via Universal Forwarderen, og det visualiseres i et moderne dashboard i Splunk. Hele processen styres af hhv. Kanban og MITREs Engage-framework, og konkluderer at honeypots kan bidrage til sikkerhed ved at informere om hvad der foregår på netværket, og at det er essentielt at visualisere dataen, for at effektivisere arbejdet med dataen. Der er mulighed for at udbygge miljøet med flere honeypots, andre porte, andre protokoller m.m., men stadig ved brug af Splunk og MITRE Engage.
