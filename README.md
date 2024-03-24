# Setup

```bash
#Set BRIDGE_IP to the IP-address of the bridge.
BRIDGE_IP=192.168.1.1

# Press the button on the brdige and execute this command within 1 minute of pressing the button
curl -X POST -d '{"devicetype":"my_app"}' -H "Content-Type: application/json" http://${BRIDGE_IP}/api/newdeveloper
```

The output of the above command will be in the format of

```
[
    {
        "success": {
            "username": "API_KEY"
        }
    }
]
```

Copy BRIDGE_IP and API_KEY to bashue.

# Configuration

Configure the menu_rooms function to match your rooms.
