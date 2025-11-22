

# **Pcap Analyzer Online**

## **Pcap Analyzer**

A **lightweight online PCAP traffic analysis tool**

**Web PCAP Storage and Analysis Tool**

![img](img/pcap-analyzer-01.png)

---

## **Features**

* Lightweight and easy to read (not suitable for very large packet analysis — can be improved if needed)
* Basic functionality:

  * Upload PCAP files
  * Store PCAP files
  * Download PCAP files
* Packet analysis:

  * Packet list
  * Packet detail viewing
  * Filter support
  * Packet analysis (Source/Destination: IP / Port)
  * Web request extraction
  * DNS request extraction
  * Mail traffic extraction

---

## **File Structure**

```
.
├── app.py (Runs the server)
├── img (Screenshots)
├── server
│   ├── __init__.py (Core)
│   ├── func.py (Utility functions)
│   ├── views.py (Views/Routes)
│   ├── pcapfile (Uploaded file directory)
│   ├── db (Database)
│   ├── static (Static files)
│   └── templates (Templates)
├── readme.md (Project description)
├── requirements.txt (Python dependencies)
├── run.sh (Run script)
└── run.bat (Windows run script)
```

---

## **Installation / Running**

```
$ git clone https://github.com/le4f/pcap-analyzer.git
$ cd pcap-analyzer
$ pip install -r requirements.txt
$ chmod +x run.sh
$ ./run.sh
```

Open in browser:
**[http://127.0.0.1:8080/](http://127.0.0.1:8080/)**

---

## **Screenshots**

![img](img/pcap-analyzer-01.png)
![img](img/pcap-analyzer-02.png)
![img](img/pcap-analyzer-03.png)
![img](img/pcap-analyzer-04.png)
![img](img/pcap-analyzer-05.png)
![img](img/pcap-analyzer-06.png)
![img](img/pcap-analyzer-07.png)
![img](img/pcap-analyzer-08.png)

---

## **Built With**

* **[Flask](http://flask.pocoo.org)**
* **[Semantic-UI](http://semantic-ui.com)**
* **[jQuery](http://jquery.com/)**
* **[PyShark](http://kiminewt.github.io/pyshark/)**
* **[Chartkick](https://github.com/mher/chartkick.py)**
* **[Highcharts](http://api.highcharts.com/highcharts)**


