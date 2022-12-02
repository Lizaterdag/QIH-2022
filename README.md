# Quantum Internet Hackathon 2022
This hackathon is a continuation of our previous Pan-European Hackathon in 2019 and a prequel to a series of planned events. The RIPE NCC is joined by the Quantum Internet Alliance (QIA), GÉANT, PSNC, SURF, QuTech and several universities to organise the Quantum Internet Hackathon 2022.

# Results (temporary version)

* https://github.com/becha42/ClimateJustice/blob/main/ReportHackathon2022
* https://github.com/brunorijsman/quantum-internet-hackathon-2022/
* 

## Challenges

Here's an overview of the challenges for this hackathon:

* Challenge 1: Quantum Key Distribution
* Challenge 2: APIs for Quantum Protocols
* Challenge 3: Little Green Qubits ([main repository for the challenge](https://github.com/becha42/ClimateJustice#little-green-qubits))

### 1. QKD Challenge

This challenge will require you to implement your own QKD protocol using QNE-ADK and test it against an eavesdropper. It consists of four parts:

1. Implement a basic QKD protocol
2. Implement an eavesdropper for your protocol and try to detect their presence
3. Extend your protocol to be able to distinguish between an eavesdropper and channel noise
4. (Open-ended) Authentication for QKD protocols

👉 Link to a repository with a more detailed description: [here](https://github.com/hjir/QIH22-QKD)

**Skills required:**
Knowledge of QKD protocols is not required, but would be helpful. You will be implementing the protocol in QNE-ADK, so you should be somewhat comfortable with using Python.

### 2. APIs for Quantum Protocols Challenge

This is an open-ended set of challenges about APIs for quantum protocols. There is already one such API: [the ETSI QKD API](https://www.etsi.org/deliver/etsi_gs/QKD/001_099/004/01.01.01_60/gs_QKD004v010101p.pdf). There are three sub-challenges:

1. Design and implement an API (similar to the ETSI QKD API) for any protocol from the [Quantum Protocol Zoo](https://wiki.veriqloud.fr/index.php?title=Main_Page)
2. Integrate such API within an already existing open-source app (e.g. Telegram, OpenSSL)
3. Connect the API to QNE-ADK

If you did not implement your own API in the first step, you can still follow sub-challenges 2. and/or 3. using the already implemented QKD API.

👉 Link to a repository with a more detailed description: [here](https://github.com/hjir/QIH22-API)

**Skills required:** This challenge requires you to have some programming experience. No quantum protocol knowledge is required. If you want to do sub-challenge 2, you should be comfortable with whatever language your chosen app is written in. QNE-ADK uses Python which is needed for sub-challenge 3.

### 3. "Little Green Qubits" 

This is a theoretical / conceptual challenge, trying to answer questions:

* Can Quantum Internet be environmentally sustainable?
* How can Quantum Internet contribute to Climate Justice?

👉 Link to a repository with a more detailed description:  ([link](https://github.com/becha42/ClimateJustice#little-green-qubits))

## General Ideas & Documentation

* Using SimulaQron to simulate quantum network http://www.simulaqron.org/
* Integrating QKD into OpenSSL to enable running quantum encrypted TLS connections
* Design and implement applications that use Quantum Protocol Zoo
* Use the QNE Application Development Kit https://www.quantum-network.com/adk/
* Designing protocols for resource sharing among multiple nodes for routing information within a quantum network

## Useful Links 
* Zoom link: https://ripe.zoom.us/j/94200226954?pwd=NWJuNnh1eUpTSi9IUnZiVGdXYVZZUT09
* Original announcement: https://labs.ripe.net/author/karla-white/take-part-in-the-quantum-internet-hackathon-2022/
* Slack invite: https://join.slack.com/t/quantumintern-wig3176/shared_invite/zt-1jvupxck6-b~EvFGJTdq~Oj5mGDL3O0A
* 2019 hackathon repository with projects: https://github.com/PEQI19/challenges
* How Hackathons Work https://github.com/Lizaterdag/QIH-2022/blob/main/How%20RIPE%20NCC%20hackathons%20work%20TXT.pdf
* Slides of the Introduction: https://github.com/Lizaterdag/QIH-2022/blob/main/intro-to-hackathons-QIH-2022.pdf
* Video recording of the intro webinar https://youtu.be/OX1aOkhcQno  
* presentation slides: https://drive.google.com/file/d/1qxee4CL3QElLgWo37ILNfHgWLIj0tru4/view?usp=share_link  


# Learn More about Quantum Computing & Networking

* https://qt.eu/discover-quantum/
* https://qtedu.eu/
* https://www.qmunity.tech/tutorials
* https://wiki.geant.org/display/NETDEV/Quantum+Fundamentals
* https://ripe74.ripe.net/archives/video/72/
* Quantum Internet Community Introduction https://ripe85.ripe.net/archives/video/896/ , Ivana Golub, October 2022, RIPE86
