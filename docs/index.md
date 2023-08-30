# **DACH watsonx.data Partner Roadshow**

![](./media/Watson%20X_Banner.jpg)

Das hands-on Team begrüßt Sie ganz herzlich zu unserem Workshop, in dem wir die Technologie von [watsonx.data](https://www.ibm.com/de-de/products/watsonx-data) gemeinsam üben werden.

Bitte lesen Sie diese kurze Anleitung sorgfältig, um:

- die technischen Voraussetzungen zu erfahren,
- sich mit dem Ablauf vertraut zu machen,  
- die Zeit am Tag des Workshops optimal zu nutzen und  
- die nötigen Vorbereitungen **vor dem Workshop** durchzuführen.

## Technische Agenda  

Das ist die Agenda, die wir für Sie vorbereitet haben:  

!!! note  "DACH watsonx.data Partner Roadshow. Technical hands-on Agenda"

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
        |  09:30 | 00:30 | <span style="color:green">Beyond Fundamentals </span> |
        |  10:00 | 00:15 | Exercise 2: Briefing                                  |
        |  10:15 | 01:00 | <span style="color:red"> Exercise 2: hands-on </span> |
        |  11:15 | 00:30 | <span style="color:green">Adoption Patterns  </span>  |
        |  11:45 | 00:05 | Exercise 3: Briefing                                  |
        |  11:50 | 01:30 | <span style="color:red"> Exercise 3: hands-on </span> |
        |  12:20 | 00:10 | Feedback & Farewell                                   |

Abhängig vom Ablauf in den unterschiedlichen Lokationen können sich die Zeiten leicht ändern aber grundsätzlich gilt es, dass wir  <span style="color:green">Vorträge</span> mit <span style="color:red">individuellen Übungen</span> an Ihrem System kombinieren. Dabei ist es zu bemerken, dass wir zwei Optionen vorgesehen haben, um die Übungen durchzuführen. Wir werden am ersten Tag <span style="color:blue"> die Umgebungen kurz testen </span> bevor es mit den Inhalten losgeht.

## *Hands-on*  

Für die individuelle Übungen haben wir eine Auswahl aus der **[watsonx.data Lab](https://db2-dte-poc.github.io/wxddemo/)** vorgesehen, die unsere Kollegen [Georg Baklarz, Daniel Hancock und Deepak Rangarao](https://db2-dte-poc.github.io/wxddemo/wxd-acknowledgements/) für die ganze watsonx Community bereitgestellt haben. Darüber hinaus haben wir auch eigene Übungen vorbereitet, die bei der Installation des Produkts sehr nützlich sein können.

## System / Umgebung / Plattform

Die Übungen im *hands-on* Workshop können in zwei Varianten durchgeführt werden. Bitte wählen Sie eine von den folgenden Optionen aus und versuchen Sie die jeweiligen Voraussetzungen **vor dem Workshop** zu erfüllen:

1. entweder auf einem Cloud-System in der **[IBM TechZone](https://techzone.ibm.com/)**
2. oder auf ihrem eigenen Laptop mit einem VMWare- oder VirtualBox-Image (OVA-Datei, 30GB gross)

Als kurze Hilfestellung für die Auswahl ist folgendes zu überlegen:

- Wenn Sie über einem kleinen Laptop verfügen, oder die Ressourcen auf Ihrem Laptop schon knapp sind, ist die Option 2 (VMWare Image) nicht wirklich geeignet. Bitte prüfen Sie die genauen Voraussetzungen in den kommenden Abschnitten dieser Anleitung.
- Die TechZone ist eine sehr gute Alternative.  Es läßt sich aber leider nicht ausschließen, dass die Kapazitäten der Cloud-Region Ihrer Auswahl nicht ausreichen, um eine Umgebung zu provisionieren. Daher empfiehlt sich, die Reservierung ein paar Tage vor Beginn des Workshops  vorzunehmen. Sollte der erste Versuch nicht erfolgreich sein, wiederholen Sie bitte erneut, eine Umgebung zu reservieren. Eine Lösung ist es manchmal auch, die Cloud-Region zu wechseln.
- Wenn Ihr Apple-Laptop mit M1/M2 Chips ausgestattet ist, ist die Option 1 (TechZone) die einzige Alternative
- In allen Fällen ist es nötig, zusätzliche Software auf Ihrem Laptop zu installieren:  
    - [Wireguard](https://www.wireguard.com/install/) (VPN Software), um das System im TechZone zu erreichen (Option 1)
    - [VMWare Player](https://www.vmware.com/products/workstation-player.html) bzw. [VMWare Fusion Player](https://customerconnect.vmware.com/en/evalcenter?p=fusion-player-personal-13) bzw. [Virtual Box](https://www.virtualbox.org/wiki/Downloads) (Option 2)

Bitte prüfen Sie die Checkliste Ihrer Wahl. Klicken Sie auf den Hyperlinks, um genauere Einzelheiten zu bekommen und führen Sie die angegeben Schritte / Befehle aus:

!!! success "Technische Checkliste"

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
        - [ ] ich sehe die ***[watsonx.data management console ](https://db2-dte-poc.github.io/wxddemo/wxd-vmware/#vware-urls/)*** (und die anderen consoles auch)

## Installation von watsonx.data  

Zwei Versionen von watsonx.data stehen zur Verfügung, mit denen wir im Workshop arbeiten werden:

- **"Developer Edition":** Diese Version wird hauptsächlich im Workshop verwendet und sie ist bereits vorinstalliert, wenn sie entweder über die IBM TechZone provisioniert wird oder als OVA-Image heruntergeladen wird, wie in der technischen Checkliste beschrieben ist. Die "Developer Edition" wurde bereits vorab  eingerichtet, um einen schnellen Einstieg in den Übungen des Workshops zu ermöglichen.
- **"Standalone Edition"**: Diese Version muss auf einer OpenShift-Umgebung installiert werden und dementsprechend werden zusätzliche Voraussetzungen benötigt. Wir haben eine zusätzliche Übung und eine [separate Anleitung](https://pages.github.ibm.com/alexander/ibmas-watsonxdata/) dafür vorbereitet.

!!! warning "Lizenz für watsonx.data"  

    In dieser zusätzlichen Übung wird kein *"developer edition"* angewendet, sondern das Standard-Produkt. Dementsprechend ist ein gültiges Lizenz für die erfolgreiche Installation nötig. Ob Sie als IBM Business Partner über so ein Lizenz verfügen, können Sie auf der WebSeite von **[MyIBM](https://myibm.ibm.com/dashboard/)** prüfen. Klicken Sie auf dem Kachel ***Container Software & Entitlement Keys*** oder nutzen Sie **[den direkten Link](https://myibm.ibm.com/products-services/containerlibrary)**, wo sie Ihre "active entitlement keys" sehen bzw. beantragen können.      

Während im Workshop hauptsächlich mit der "Developer Edition" gearbeitet wird, kann parallel dazu die Installation der "Standalone Edition" mit einem OpenShift Single Node Cluster (SNO) erfolgen, um sich mit dem Installationsprozess vertraut zu machen. Die Installation benötigt ca. 2,5 Stunden und kann im Hintergrund parallel zum Workshop stattfinden.

Die Installation der "Standalone Edition" erfolgt in zwei Schritten: Zuerst muss die Hardware bereitgestellt werden, indem das Single Node Cluster (SNO) in der TechZone provisoniert wird. Dies ist der erste Schritt. Danach können Sie die Installation von watsonx.data fortsetzen.

!!! info "Bitte beachten Sie:"

        Wir möchten darauf hinweisen, dass diese Installation einen tieferen technischen Hintergrund erfordert. Unser Hauptziel ist es, der technischen Gruppe eine praxisnahe Workshop-Erfahrung zu bieten.

### Voraussetzungen zur Installation von watsonx.data

Falls Sie die "Standalone Edition" installieren möchten, würden wir Sie darum bitten, die entsprechende Umgebung **vor dem Workshop**  wie folgt zu provisionieren:

- **SNO Cluster**: zuerst beachten Sie bitte die zusätzlichen Voraussetzungen, die  **[hier im *"Step 1"*](https://pages.github.ibm.com/alexander/ibmas-watsonxdata/Requirements/)** dokumentiert sind und dann befolgen Sie den Prozess zur Provisionierung des Single Node Clusters (SNO) gemäß den Anweisungen.
- **Zugriff Check**: Wenn das System provisioniert ist, prüfen Sie bitte, ob Sie sich anmelden können, indem Sie den ***["Step 2" ](https://pages.github.ibm.com/alexander/ibmas-watsonxdata/Prepare%20the%20Installation/ )*** zumindest bis zum Punkt 2.2.3 durchführen. Die restlichen Schritten ab dem Punkt 2.3 können wir während des Workshops gemeinsam durchführen.

## Haben Sie noch Fragen?  

Bitte kontaktieren Sie uns, um Ihre Anregungen, Vorschläge und Fragen mitzuteilen und sie zu klären. Wir sind gerne für Sie da:

!!! note  "Ihre technischen Ansprechpartner in den IBM Lokationen"

    === "Ehningen"
        :fontawesome-regular-envelope: [Angel González](mailto:angelito@de.ibm.com)  
        :fontawesome-regular-envelope: [Stefan Hummel](mailto:Stefan.Hummel@de.ibm.com)  
    
    === "Frankfurt"
        :fontawesome-regular-envelope: [Sonja Pressel](mailto:sonja.pressel@de.ibm.com)  
        :fontawesome-regular-envelope: [Tobias Nirschl ](mailto:Tobias.Nirschl@ibm.com)  
        
    === "Hamburg"
        :fontawesome-regular-envelope: [Alexander Seelert](mailto:alexander@de.ibm.com)  
        :fontawesome-regular-envelope: [Olaf Depper](mailto:OD@de.ibm.com)  

    === "Wien"
        :fontawesome-regular-envelope: [Ronald Brutter](mailto:Ronald_Brutter@at.ibm.com)  
  
  Wir freuen uns darauf, Sie an der Veranstaltung zu treffen.

  ![](./media/team.png)
