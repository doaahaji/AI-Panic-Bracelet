# AI Panic Bracelet – Système Intelligent de Détection de Situations de Danger

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-IoT-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/PlatformIO-Embedded-F5822A?style=for-the-badge&logo=platformio&logoColor=white">
  <img src="https://img.shields.io/badge/MQTT-IoT-660066?style=for-the-badge">
  <img src="https://img.shields.io/badge/Node--RED-Dashboard-8F0000?style=for-the-badge&logo=nodered&logoColor=white">
</p>

---

**AI Panic Bracelet** est un système intelligent de détection de situations de danger combinant l'Internet des Objets (IoT), l'Intelligence Artificielle et les systèmes embarqués afin d'améliorer la sécurité des personnes. Le prototype repose sur un microcontrôleur **ESP32** connecté à plusieurs capteurs, notamment le **MAX30105** pour la surveillance de la fréquence cardiaque et le **MPU6050** pour l'analyse des mouvements. Les données collectées sont transmises via le protocole **MQTT** vers une plateforme de supervision où elles sont analysées en temps réel. Le système intègre plusieurs modèles d'intelligence artificielle, dont **YAMNet** pour la détection des cris de détresse, **Wav2Vec2** pour la reconnaissance des émotions vocales et **Edge Impulse** pour la classification des mouvements en situations normales ou dangereuses. Une application développée avec **Flask** et un tableau de bord **Node-RED** permettent de visualiser les informations, de suivre les alertes et de superviser l'état du bracelet en temps réel. En complément de la détection automatique, le dispositif offre un déclenchement manuel d'alerte à l'aide d'un bouton poussoir, un mécanisme d'annulation par double clic, ainsi qu'un retour haptique via un vibreur et un affichage local sur un écran **OLED SSD1306**. Grâce à son architecture multimodale associant données physiologiques, mouvements et analyses audio, AI Panic Bracelet constitue une solution intelligente capable de détecter rapidement des situations potentiellement dangereuses et de transmettre des alertes afin de faciliter une intervention rapide.

<p align="center">
    <img src="images/prototype.png" width="600" alt="Prototype du bracelet">
</p>
