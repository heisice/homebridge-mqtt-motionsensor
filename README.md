# homebridge-mqtt-motionsensor

Get Motion Sensor status via MQTT in Homebridge

Installation
--------------------
    sudo npm install -g homebridge-mqtt-motionsensor


Sample HomeBridge Configuration
--------------------
    {
      "bridge": {
        "name": "HomeBridge",
        "username": "CC:33:3B:D3:CE:32",
        "port": 51826,
        "pin": "321-45-123"
      },

      "description": "",

      "accessories": [
        {
          "accessory": "mqtt-motionsensor",
          "name": "Living Room",
          "url": "mqtt://localhost",
          "topic": "home/livingroom/motionsensor",
          "username": "username",
          "password": "password"
        }
      ],

      "platforms": []
    }

Contributions Welcome!
--------------------
