# **IBM Business Partner watsonx.data workshop**

![](./media/Watson%20X_Banner.jpg)

Das hands-on Team begrüßt Sie ganz herzlich zu unserem Workshop, an dem wir die Technologie von [watsonx.data](https://www.ibm.com/de-de/products/watsonx-data) gemeinsam üben werden.

Bitte lesen Sie vorsichtig diese kurze Anleitung, um:

- die technischen Voraussetzungen zu erfahren,
- sich mit dem Ablauf vertraut zu machen,  
- die Zeit am Tag des Workshops optimal zu nutzen  
- die nötigen Vorbereitungen **vor dem Workshop** durchzuführen.

## Agenda  

Das ist die Agenda, die wir für Sie vorbereitet haben.  

=== "Tag 1"  

    | Beginn | Dauer | Inhalt                                                |
    |--------|-------|-------------------------------------------------------|
    |  14:30 | 00:15 | Intro                                                 |
    |  14:45 | 00:30 | <span style="color:blue">Setup check   </span>        |
    |  15:15 | 00:30 | <span style="color:green">Fundamentals </span>        |
    |  15:45 | 00:15 | Exercise 1: Briefing                                  |
    |  16:00 | 01:15 | <span style="color:red"> Exercise 1: hands-on </span> |
    |  17:15 | 00:15 | Recap                                                 |

=== "Tag 2"

    | Beginn | Dauer | Inhalt                                                |
    |--------|-------|-------------------------------------------------------|
    |  09:00 | 00:30 | <span style="color:green">Beyond Fundamentals </span> |
    |  09:30 | 00:15 | Exercise 2: Briefing                                  |
    |  09:45 | 01:00 | <span style="color:red"> Exercise 2: hands-on </span> |
    |  10:45 | 00:30 | <span style="color:green">Adoption Patterns  </span>  |
    |  11:15 | 00:05 | Exercise 3: Briefing                                  |
    |  11:20 | 01:30 | <span style="color:red"> Exercise 3: hands-on </span> |
    |  11:50 | 00:10 | Feedback & Farewell                                   |

Abhängig vom Ablauf in den unterschiedlichen Lokationen können sich die Zeiten leicht ändern aber grundsätzlich gilt es, dass wir  <span style="color:green">Vorträgen</span> mit <span style="color:red">individuelle Übungen</span> an Ihrem System kombinieren. Dabei ist es zu bemerken, dass wir zwei Optionen vorgesehen haben, um die Übungen durchzuführen und wir werden am ersten Tag <span style="color:blue"> die Umgebungen kurz durchchecken </span> bevor es mit den Inhalten losgeht.

## *Hands-on*

Für die individuelle Übungen haben wir eine Auswahl aus der **[watsonx.data Lab](https://db2-dte-poc.github.io/wxddemo/)** vorgesehen, die unsere Kollegen [Georg Baklarz, Daniel Hancock und Deepak Rangarao](https://db2-dte-poc.github.io/wxddemo/wxd-acknowledgements/) für die ganze watsonx Community bereitgestellt haben. Darüber hinaus werden wir auch eigene Übungen vorbereitet, die insbesordere bei der Installation des Produkts sehr interessant sein werden.

## System / Umgebung / Plattform

Die Übungen im *hands-on* Workshop können in zwei Varianten durchgeführt werden. Bitte wählen Sie eine von den folgenden Optionen aus und versuchen Sie die jeweiligen Voraussetzungen **vor dem Workshop** zu erfüllen:

1. entweder auf einem Cloud-System in der **[IBM TechZone](https://techzone.ibm.com/)**
2. oder auf ihrem eigenen Laptop mit einer VMWare- oder VirtualBox-Image (OVA-Datei, 30GB gross)

Als kurze Hilfestellung für die Auswahl ist folgendes zu überlegen:

- Wenn Sie über einem kleinen Laptop verfügen, oder die Ressourcen auf Ihrem Laptop schon knapp sind, ist die Option 2 (VMWare Image) nicht wirklich geeignet. Bitte prüfen Sie die genauen Voraussetzungen in den kommenden Abschnitten dieser Anleitung nach.
- Die TechZone ist eine sehr gute Alternative aber es ist nicht auszuschliessen, dass die Kapazität vom Rechenzentrum Ihrer Auswahl nicht ausreicht, genau wann Sie das System provisionieren lassen. Daher empfiehlt sich, ein paar Tage in Voraus das System zu bestellen und gelegentlich die Bestellung wiederholen, wenn es nicht geklappt hat. In manchen Fällen ist die einzige Option, ein anderes Rechenzentrum zu nutzen.
- Wenn Ihrem Apple-Laptop mit M1/M2 Chips ausgestattet ist, ist die Option 1 (TechZone) die einzige Alternative
- In allen Fällen ist es nötig, zusätzliche Software auf Ihrem Laptop zu installieren: 
    - [Wireguard](https://www.wireguard.com/install/), um das System im TechZone zu erreichen (Option 1)
    - [VMWare Player](https://www.vmware.com/products/workstation-player.html) bzw. [VMWare Fusion Player](https://customerconnect.vmware.com/en/evalcenter?p=fusion-player-personal-13) bzw. [Virtual Box](https://www.virtualbox.org/wiki/Downloads) (Option 2)

Bitte öffnen Sie die folgende Notiz und prüfen Sie die Checkliste von Ihrer Wahl. Dann klicken Sie auf den Hyperlinks, um genauere Einzelheiten zu bekommen und führen Sie die angegeben Schritte / Befehle aus:

??? success "Technische Checkliste"

    === "Option 1: TechZone System"

        - [ ] ich habe eine **[IBM id](https://db2-dte-poc.github.io/wxddemo/wxd-reference-ibmid/)**
        - [ ] ich kann genau **[dieses System](https://db2-dte-poc.github.io/wxddemo/wxd-reference-techzone/)** in der TechZone provisionieren lassen
        - [ ] ich habe **[eine Email](https://db2-dte-poc.github.io/wxddemo/wxd-reference-access/) ** von der TechZone bekommen und mein System ist verfügbar
        - [ ] ich habe das **[Zertifikat heruntergeladen und Wireguard](https://db2-dte-poc.github.io/wxddemo/wxd-reference-wireguard/)** läuft auf meinem Laptop
        - [ ] ich kann mich ans System per ```ssh``` ***[anmelden](https://db2-dte-poc.github.io/wxddemo/wxd-reference-ssh/)***
        - [ ] ich sehe die ***[watsonx.data management console ](https://db2-dte-poc.github.io/wxddemo/wxd-reference-ports/)***

    === "Option 2: VMWare Image"

        - [ ] mein Laptop erfüllt die angegebenen **[hardware requirements ](https://db2-dte-poc.github.io/wxddemo/wxd-vmware)** (auf dem Link klicken und kurz runterscrollen)
        - [ ] ich kann die folgende Software auf meinem Laptop installieren (nicht alle drei, ein Paket reicht)
          - [VMWare Player für Windows](https://www.vmware.com/products/workstation-player.html) 
          - [VMWare Fusion Player für Mac](https://customerconnect.vmware.com/en/evalcenter?p=fusion-player-personal-13)
          - [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
        - [ ] ich kann die 30GB OVA Datei durch eine von diesen Optionen herunterladen:
          - direkter Link: [https://ibm.biz/wxd-vmware](https://ibm.biz/wxd-vmware) 
          - Befehl: ```wget -O watsonxdata.ova https://ibm.biz/wxd-vmware```
          - ich sehe den download-Link auf der [WebSeite der TechZone Reservierung ](https://db2-dte-poc.github.io/wxddemo/wxd-vmware/) , obwohl ich keine Reservierung möchte 
        - [ ] die Virtual-Maschine **[startet](https://db2-dte-poc.github.io/wxddemo/wxd-vmware/#starting-the-vmware-image)**
        - [ ] ich sehe die ***[watsonx.data management console ](https://db2-dte-poc.github.io/wxddemo/wxd-vmware/#vmware-urls/)*** (und die anderen auch)

## Extra Übung

!!! bug "Das müssen wir erweitern"

    watsonx.data war auf den oben beschrieben Umgebungen bereits installiert und konfiguriert denn es wäre nicht machbar, die komplette Installation im Rahmen der verfügbaren Zeit zu üben. Dennoch haben wir eine Anleitung vorbereitet, um watsonx.data auf einem Single Node OpenShift zu aufzusetzen: <https://pages.github.ibm.com/alexander/ibmas-watsonxdata/>



## Haben Sie noch Fragen?  

Bitte kontaktieren Sie uns, um Ihre Anregungen, Vorschläge und Fragen mitzuteilen und sie zu klären. Wir sind gerne für Sie da:


!!! note  "Ihre technischen Ansprechpartner in den IBM Lokationen"

    === "Ehningen"
        :fontawesome-regular-envelope: [Angel González](mailto:angelito@de.ibm.com)  
        :fontawesome-regular-envelope: [Stefan Hummel](mailto:Stefan.Hummel@de.ibm.com)  
    
    === "Frankfurt"
        :fontawesome-regular-envelope: [Sonja Pressler ](mailto:sonja.pressel@de.ibm.com)  
        :fontawesome-regular-envelope: [Tobias Nirschl ](mailto:Tobias.Nirschl@ibm.com)  
        
    === "Hamburg"
        :fontawesome-regular-envelope: [Alexander Seelert](mailto:alexander@de.ibm.com)  
        :fontawesome-regular-envelope: [Olaf Depper ](mailto:OD@de.ibm.com)  

    === "Wien"
        :fontawesome-regular-envelope: [Ronald Bruter](mailto:Ronald_Brutter@at.ibm.com)  
  
  Wir freuen uns darauf, Sie an der Veranstaltung zu treffen.

  ![](./media/team.png)
